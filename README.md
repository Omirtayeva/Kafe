<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1rem;
            font-size: 1.2rem;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            background-image: url('restaurant.jpg');
            background-size: cover;
            background-position: center;
            height: 50vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
        }
        .section {
            padding: 2rem;
            text-align: center;
        }
        .menu-item {
            margin: 1rem 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Our Restaurant</h1>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h1>Delicious Food, Great Atmosphere</h1>
    </div>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>We serve the best dishes made with fresh ingredients and lots of love. Join us for an unforgettable dining experience.</p>
    </section>

    <section id="menu" class="section">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <h3>Pizza</h3>
            <p>Classic Margherita, Pepperoni, and more.</p>
        </div>
        <div class="menu-item">
            <h3>Pasta</h3>
            <p>Spaghetti, Alfredo, and other Italian favorites.</p>
        </div>
        <div class="menu-item">
            <h3>Desserts</h3>
            <p>Cheesecake, Brownies, and Ice Cream.</p>
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: contact@restaurant.com</p>
        <p>Phone: +123-456-7890</p>
        <p>Address: 123 Food Street, Food City</p>
    </section>

    <footer>
        <p>&copy; 2025 Our Restaurant. All rights reserved.</p>
    </footer>
</body>
</html>
