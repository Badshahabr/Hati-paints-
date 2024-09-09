<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HatiPaints - Custom Paints and Catalog</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .container {
            padding: 20px;
        }
        .catalog-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .catalog-item {
            background-color: white;
            margin: 10px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 200px;
        }
        .catalog-item img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .catalog-item p {
            margin: 10px 0 0;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact-info {
            margin: 20px 0;
            text-align: center;
        }
        .whatsapp-link {
            background-color: #25d366;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

<header>
    <h1>HatiPaints</h1>
    <p>Your Custom Paint Experts</p>
    <p>Address: Village Makura, Near XYZ Market, Tier-3 City, India</p>
    <p>Phone: +91-XXXXXXXXXX | Email: info@hatipaints.com</p>
</header>

<div class="container">
    <h2>Paint Catalog</h2>
    <div class="catalog-section">
        <!-- Example of one paint -->
        <div class="catalog-item">
            <img src="https://via.placeholder.com/200" alt="Color Sample">
            <p><strong>Color Name:</strong> Sunset Orange</p>
            <p><strong>Color Code:</strong> #FF4500</p>
        </div>
        <!-- More paint items can be added similarly -->
    </div>
</div>

<div class="contact-info">
    <p>For more details or to place an order, contact us directly via WhatsApp!</p>
    <a href="https://wa.me/91XXXXXXXXXX" class="whatsapp-link">Message Us on WhatsApp</a>
</div>

<footer>
    <p>&copy; 2024 HatiPaints | All Rights Reserved | <a href="#">Tracking Link</a></p>
</footer>

</body>
</html> Hati-paints-
