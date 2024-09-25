<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ivy and Thyme - Fancy Restaurant</title>
    <link href="https://fonts.googleapis.com/css2?family=EB+Garamond&family=Nunito:wght@400;700&family=Oswald:wght@400&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        * {
            box-sizing: border-box;
        }

        body {
            font-family: 'Nunito', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #132620ff; /* Dark background */
            color: #efe9e1ff; /* Light text color */
        }

        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }

        header {
            background: #322d29ff;
            padding: 20px 0;
        }

        header h1 {
            float: left;
            margin: 0;
            font-family: 'EB Garamond', serif;
            color: #efe9e1ff; /* Light text color */
        }

        nav {
            float: right;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline;
            margin-left: 20px;
        }

        nav ul li a {
            color: #efe9e1ff; /* Light text color */
            text-decoration: none;
        }

        #hero {
            background: url('https://source.unsplash.com/1600x900/?restaurant') no-repeat center center/cover;
            color: #efe9e1ff; /* Light text color */
            padding: 100px 0;
            text-align: center;
        }

        .btn {
            background: #d7ad61ff; /* Button color */
            color: #322d29ff; /* Dark text color for button */
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }

        section {
            padding: 60px 0;
            text-align: center;
        }

        h2 {
            margin-bottom: 20px;
            color: #efe9e1ff; /* Light text color */
            font-family: 'Oswald', sans-serif;
        }

        p {
            color: #c5ac8fff; /* Light text color for paragraph */
        }

        form {
            display: grid;
            gap: 10px;
            max-width: 400px;
            margin: auto;
        }

        input, button {
            padding: 10px;
            width: 100%;
            border-radius: 5px;
        }

        input {
            border: 1px solid #5e503fff; /* Border color */
            color: #322d29ff; /* Dark text color for input */
        }

        button {
            background: #72383dff; /* Button color */
            color: #efe9e1ff; /* Light text color for button */
            border: none;
            cursor: pointer;
        }

        footer {
            background: #322d29ff;
            text-align: center;
            padding: 20px 0;
        }

        .socials a {
            margin: 0 10px;
            color: #efe9e1ff; /* Light text color */
        }
    </style>
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

    <script>
        document.getElementById('reservation-form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your reservation! We will contact you soon.');
        });
    </script>
</body>
</html>
    
