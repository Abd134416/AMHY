<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Woodworking Live Stream</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            background-color: #f4f4f4; 
            margin: 0; 
            padding: 0; 
        }
        header { 
            background-color: #333; 
            color: white; 
            padding: 10px; 
            text-align: center; 
        }
        .container { 
            padding: 20px; 
        }
        .btn { 
            padding: 10px 20px; 
            background-color: #28a745; 
            color: white; 
            border: none; 
            cursor: pointer; 
        }
        .btn:hover { 
            background-color: #218838; 
        }
        .consent-form { 
            background-color: white; 
            padding: 20px; 
            border-radius: 5px; 
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); 
            width: 300px; 
            margin: 0 auto; 
        }
        .gallery img { 
            width: 100%; 
            height: auto; 
            border-radius: 8px; 
            margin-bottom: 15px; 
        }
        .gallery { 
            display: grid; 
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr)); 
            gap: 15px; 
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Woodworking Business</h1>
</header>

<div class="container">
    <h2>Watch Me Work Live!</h2>
    <p>Experience the art of woodworking in real-time by joining my live stream. Click the button below to agree to the terms and watch the stream.</p>
    
    <!-- Consent Form -->
    <div class="consent-form">
        <h3>Consent to View Live Stream</h3>
        <p>By clicking "Agree", you consent to view the live stream of my woodworking process. Please do not record or distribute the stream.</p>
        <button class="btn" onclick="window.location.href='https://zoom.us/j/your_zoom_link'">Agree and View Stream</button>
    </div>

    <!-- Gallery Section -->
    <h2>Our Work</h2>
    <div class="gallery">
        <div><img src="wood1.jpg" alt="Woodworking project 1"></div>
        <div><img src="wood2.jpg" alt="Woodworking project 2"></div>
        <div><img src="wood3.jpg" alt="Woodworking project 3"></div>
        <div><img src="wood4.jpg" alt="Woodworking project 4"></div>
    </div>

    <!-- Contact Section -->
    <h2>Contact Us</h2>
    <p>If you're interested in custom woodworking or have any questions, please reach out:</p>
    <form action="/submit" method="post">
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <label for="message">Message:</label><br>
        <textarea id="message" name="message" required></textarea><br><br>
        <button class="btn" type="submit">Send Message</button>
    </form>
</div>

</body>
</html>
