# codsofttask2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real Estate Landing Page</title>
    <style>
        /* Reset some default styles */
        body, h1, h2, p {
            margin: 0;
            padding: 0;
        }

        /* Global styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }

        /* Header styles */
        header {
            background-color: #614040;
            color: #fff;
            text-align: center;
            padding: 2em 0;
        }

        /* Navigation styles */
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 1em 0;
        }

        nav a {
            color: #ef7f7f;
            text-decoration: none;
            margin: 0 1em;
            padding: 0.5em;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #ffc107;
        }

        /* Main content styles */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2em;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .property-card {
            border: 1px solid #ddd;
            background-color: #fff;
            margin-bottom: 2em;
            padding: 1.5em;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: calc(33.33% - 2em);
        }

        .property-card img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .property-title {
            font-size: 1.5rem;
            margin: 0.5em 0;
        }

        .property-description {
            color: #f57e7e;
            margin-bottom: 1.5em;
        }

        .property-price {
            font-size: 1.2rem;
            color: #ffc107;
        }

        /* Footer styles */
        footer {
            text-align: center;
            padding: 2em 0;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Real Estate Properties</h1>
        <p>Your Trusted Source for Properties</p>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Featured Properties</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <div class="property-card">
            <img src="home.jpg" alt="Property 1">
            <h2 class="property-title">Modern Villa</h2>
            <p class="property-description">Spacious 4-bedroom villa with a stunning view.</p>
            <p class="property-price">Price: $1,200,000</p>
        </div>

        <div class="property-card">
            <img src="house.jpg" alt="Property 2">
            <h2 class="property-title">Luxury Apartment</h2>
            <p class="property-description">Luxurious 3-bedroom apartment in the city center.</p>
            <p class="property-price">Price: $800,000</p>
        </div>
        <!-- Add more property cards here -->
    </div>

    <footer>
        <p>&copy; 2023 Real Estate Agency. All rights reserved.</p>
    </footer>
</body>
</html>
