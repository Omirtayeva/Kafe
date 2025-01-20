<!DOCTYPE html>
<html lang="kk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Дәмді әлем</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background: url('https://example.com/your-background.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }
        header {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 15px;
        }
        header .navbar-brand {
            font-size: 24px;
            font-weight: bold;
            color: #fff;
        }
        header .nav-link {
            color: #fff;
            font-size: 18px;
        }
        header .nav-link:hover {
            color: #ff4500;
        }
        section {
            padding: 50px 20px;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            text-align: center;
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">Дәмді әлем</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link" href="#main">Басты әлем</a></li>
                        <li class="nav-item"><a class="nav-link" href="#menu">Ас мәзірі</a></li>
                        <li class="nav-item"><a class="nav-link" href="#cashback">Артықшылықтар</a></li>
                        <li class="nav-item"><a class="nav-link" href="#promo">Қызықты ұсыныстар</a></li>
                        <li class="nav-item"><a class="nav-link" href="#reservation">Брондау</a></li>
                        <li class="nav-item"><a class="nav-link" href="#feedback">Пікірлер</a></li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Main Section -->
    <section id="main" class="text-center">
        <div class="container">
            <h1>Дәмді әлемге қош келдіңіз!</h1>
            <p>Сізді ерекше дәмдер мен жылы қарым-қатынас күтіп тұр. Күн сайын біз сіз үшін ең жақсысын дайындаймыз.</p>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="bg-dark text-white">
        <div class="container">
            <h2 class="text-center">Ас мәзірі</h2>
            <!-- Мәзір контентін осында қосыңыз -->
        </div>
    </section>

    <!-- Cashback Section -->
    <section id="cashback" class="text-center">
        <div class="container">
            <h2>Артықшылықтар</h2>
            <p>Бізде тамақтану арқылы ерекше сыйлықтарға ие болыңыз және әр тапсырысыңыздан жеңілдік алыңыз.</p>
        </div>
    </section>

    <!-- Promo Section -->
    <section id="promo" class="bg-dark text-white text-center">
        <div class="container">
            <h2>Қызықты ұсыныстар</h2>
            <p>Әр бейсенбі - пицца күні! Үш пицца алсаңыз, төртіншісі тегін.</p>
        </div>
    </section>

    <!-- Reservation Section -->
    <section id="reservation" class="text-center">
        <div class="container">
            <h2>Орынға тапсырыс беріңіз</h2>
            <form>
                <input type="text" class="form-control" placeholder="Есіміңіз" required>
                <input type="datetime-local" class="form-control" required>
                <button type="submit" class="btn btn-primary">Тапсырыс беру</button>
            </form>
        </div>
    </section>

    <!-- Feedback Section -->
    <section id="feedback" class="bg-dark text-white text-center">
        <div class="container">
            <h2>Сіздің пікіріңіз</h2>
            <form>
                <input type="text" class="form-control" placeholder="Атыңыз" required>
                <textarea class="form-control" rows="4" placeholder="Пікіріңізді жазыңыз" required></textarea>
                <button type="submit" class="btn btn-primary">Жіберу</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2024 Дәмді әлем. Барлық құқықтар қорғалған.</p>
    </footer>

    <!-- Bootstrap Scripts -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
