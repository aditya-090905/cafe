<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Eats Cafe</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #333;
            padding: 10px 20px;
            color: white;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
        }

        header nav ul li {
            display: inline;
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
        }

        h1, h2 {
            text-align: center;
            color: #333;
        }

        .menu-item {
            text-align: center;
            margin-bottom: 20px;
        }

        .menu-item img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 0 auto;
        }

        form input, form button {
            display: block;
            margin: 10px auto;
            padding: 10px;
            width: 80%;
            max-width: 300px;
        }

        #map {
            display: block;
            margin: 20px auto;
        }

        .testimonial {
            margin: 20px auto;
            text-align: center;
            width: 80%;
            max-width: 500px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#reservation">Reservation</a></li>
                <li><a href="#location">Location</a></li>
                <li><a href="#testimonials">Testimonials</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h1>Welcome to Aditya's Cafe</h1>
        <p>Your favorite spot for delicious food and great vibes!</p>
    </section>

    <!-- Menu Section -->
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <img src="https://th.bing.com/th/id/OIP.2FhXIw0nViNYFTOoi7uNxQHaE7?w=278&h=185&c=7&r=0&o=5&pid=1.7" alt="Grilled Chicken Salad">
            <h3>Grilled Chicken Salad</h3>
            <p>A fresh mix of greens with grilled chicken.</p>
            <p>₹500</p>
        </div>
        <div class="menu-item">
            <img src="https://th.bing.com/th?id=OSK.4524fe87dcac2014a8c79419dd0805ae&w=205&h=136&rs=2&qlt=80&o=6&cdv=1&pid=16.1" alt="Pasta Primavera">
            <h3>Pasta Primavera</h3>
            <p>A classic pasta with seasonal veggies.</p>
            <p>₹250</p>
        </div>
        <div class="menu-item">
            <img src="data:image/jpeg;base64,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" alt="Chocolate Cake">
            <h3>Chocolate Cake</h3>
            <p>Decadent chocolate cake with a rich frosting.</p>
            <p>₹200</p>
        </div>
    </section>

    <!-- Reservation Section -->
    <section id="reservation">
        <h2>Reserve a Table</h2>
        <form action="submit_reservation.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="date">Date:</label>
            <input type="date" id="date" name="date" required>

            <label for="time">Time:</label>
            <input type="time" id="time" name="time" required>

            <label for="people">Number of People:</label>
            <input type="number" id="people" name="people" required>

            <button type="submit">Reserve Now</button>
        </form>
    </section>

    <!-- Location Section -->
    <section id="location">
        <h2>Our Location</h2>
        <p>123 Delicious St, Foodtown, FT 12345</p>
        <div id="map">
            <iframe src="https://www.google.com/maps/embed?pb=YOUR_GOOGLE_MAPS_EMBED_URL_HERE" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials">
        <h2>Customer Reviews</h2>
        <div class="testimonial">
            <p>"Best food in town! The pasta was amazing!" - Jane D.</p>
        </div>
        <div class="testimonial">
            <p>"A cozy atmosphere and friendly service. Highly recommend the grilled chicken salad." - Mark T.</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Delicious Eats Cafe. All rights reserved.</p>
    </footer>

</body>
</html>
