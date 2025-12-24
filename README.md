<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Lamborghini</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #0b0b0b;
            color: white;
        }

        header {
            background: black;
            padding: 20px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            color: #f5c400;
            margin: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
            font-weight: bold;
        }

        .hero {
            height: 90vh;
            background: linear-gradient(
                rgba(0,0,0,0.6),
                rgba(0,0,0,0.6)
            ),
            url("https://images.unsplash.com/photo-1549921296-3a6b5f6b89f3") center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            padding-left: 50px;
        }

        .hero h2 {
            font-size: 50px;
            margin: 0;
        }

        .hero p {
            font-size: 20px;
            max-width: 500px;
        }

        .btn {
            margin-top: 20px;
            display: inline-block;
            padding: 12px 25px;
            background: #f5c400;
            color: black;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
            width: fit-content;
        }

        .section {
            padding: 60px 40px;
            text-align: center;
        }

        .cards {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }

        .card {
            background: #111;
            padding: 30px;
            width: 250px;
            border-radius: 10px;
        }

        footer {
            background: black;
            text-align: center;
            padding: 20px;
            font-size: 14px;
            color: gray;
        }
    </style>
</head>

<body>

<header>
    <h1>LAMBORGHINI</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Models</a>
        <a href="#">Specs</a>
        <a href="#">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Unleash the Bull</h2>
    <p>Experience extreme performance, bold design, and Italian excellence.</p>
    <a class="btn" href="#">Explore Models</a>
</section>

<section class="section">
    <h2>Performance Specs</h2>
    <div class="cards">
        <div class="card">
            <h3>Top Speed</h3>
            <p>350 km/h</p>
        </div>
        <div class="card">
            <h3>0–100 km/h</h3>
            <p>2.8 seconds</p>
        </div>
        <div class="card">
            <h3>Engine</h3>
            <p>V12 Naturally Aspirated</p>
        </div>
    </div>
</section>

<footer>
    © 2025 Lamborghini Fan Page • Educational Use Only
</footer>

</body>
</html>
