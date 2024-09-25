<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ivy and Thyme - Fancy Restaurant</title>
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Ivy and Thyme</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#reservations">Reservations</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Welcome to Ivy and Thyme</h2>
            <p>Experience exquisite dining with a touch of elegance.</p>
            <a href="#reservations" class="btn">Make a Reservation</a>
        </div>
    </section>

    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>At Ivy and Thyme, we offer a fine dining experience with carefully crafted dishes made from the freshest ingredients.</p>
        </div>
    </section>

    <section id="menu">
        <div class="container">
            <h2>Our Menu</h2>
            <ul>
                <li>Grilled Salmon with Lemon Butter</li>
                <li>Filet Mignon with Garlic Mashed Potatoes</li>
                <li>Vegetarian Risotto with Seasonal Vegetables</li>
                <li>Chocolate Lava Cake with Vanilla Ice Cream</li>
            </ul>
        </div>
    </section>

    <section id="reservations">
        <div class="container">
            <h2>Reservations</h2>
            <form id="reservation-form">
                <input type="text" placeholder="Your Name" required>
                <input type="email" placeholder="Your Email" required>
                <input type="date" required>
                <input type="time" required>
                <input type="number" placeholder="Number of Guests" required>
                <button type="submit">Reserve Now</button>
            </form>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: info@ivyandthyme.com</p>
            <p>Phone: +123 456 7890</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 Ivy and Thyme. All Rights Reserved.</p>
            <div class="socials">
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
