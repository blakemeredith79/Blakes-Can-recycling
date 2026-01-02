<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blake's Can & Bottle Recycling</title>
    <!-- Favicon -->
    <link rel="icon" type="image/png" href="favicon.png">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #008080;
            color: white;
            text-align: center;
            padding: 25px 0;
        }

        header .logo {
            max-width: 140px;
            display: block;
            margin: 0 auto 15px;
        }

        /* Banner */
        .banner {
            background-color: #00bfa5; /* bright teal */
            color: white;
            text-align: center;
            font-weight: bold;
            padding: 12px 0;
            font-size: 18px;
            border-bottom: 4px solid #008080;
        }

        /* Tip box */
        .tip {
            background-color: #fff3cd; /* light yellow */
            border-left: 6px solid #ffc107; /* gold accent */
            padding: 15px 20px;
            border-radius: 6px;
            font-size: 16px;
            max-width: 850px;
            margin: 20px auto;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .tip p {
            margin: 0;
        }

        section {
            padding: 25px 20px;
            max-width: 850px;
            margin: 25px auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1);
        }

        h1, h2 {
            margin-bottom: 20px;
            color: #008080;
        }

        ul {
            list-style: none;
            padding-left: 0;
        }

        li {
            padding: 10px 0;
            font-size: 17px;
        }

        a {
            color: #008080;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .button-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 15px;
        }

        button {
            background-color: #00bfa5;
            color: white;
            border: none;
            padding: 15px 25px;
            border-radius: 8px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            flex: 1;
            min-width: 180px;
            text-align: center;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #008c7a;
        }

        .dropoff-instructions {
            background-color: #e0f7f7;
            border: 2px dashed #00bfa5;
            padding: 20px;
            border-radius: 10px;
            font-size: 16px;
            margin-top: 20px;
        }

        .dropoff-instructions p {
            margin: 10px 0;
        }

        .arrow {
            font-size: 30px;
            display: block;
            text-align: center;
            margin: 10px 0;
            color: #00bfa5;
        }

        footer {
            text-align: center;
            padding: 20px 0;
            background-color: #008080;
            color: white;
            margin-top: 25px;
        }

        @media (max-width: 600px) {
            .banner {
                font-size: 16px;
                padding: 10px 0;
            }
            .tip {
                font-size: 15px;
                padding: 12px 15px;
            }
            button {
                flex: 100%;
            }
        }
    </style>
</head>
<body>

    <header>
        <img src="logo.png" alt="Blake's Recycling Logo" class="logo">
        <h1>Blake's Can & Bottle Recycling</h1>
    </header>

    <!-- Banner -->
    <section class="banner">
        <p>📣 We now collect cans & bottles! Call or WhatsApp Blake today! ♻️</p>
    </section>

    <section class="intro">
        <h2>Welcome!</h2>
        <p>Blake's Recycling collects cans and bottles in the Narangba area. You can either drop them off at our location or request a pick-up. Let's make a difference together!</p>
    </section>

    <section class="services">
        <h2>How It Works</h2>
        <ul>
            <li>📦 <strong>Drop-Off:</strong> Bring your cans & bottles to 179 Prosperity Street, Narangba QLD 4504</li>
            <li>🚗 <strong>Pick-Up:</strong> Call, text, or use the Request Pick-Up button to arrange a collection</li>
            <li>♻️ <strong>Recycling:</strong> All cans and bottles are sorted and recycled responsibly</li>
        </ul>
    </section>

    <!-- Tip box -->
    <section class="tip">
        <p>💡 <strong>Tip:</strong> To arrange a pick-up, simply click the “Request Pick-Up” button above or send a WhatsApp to Blake. It’s quick and easy!</p>
    </section>

    <section class="contact">
        <h2>Contact Blake</h2>
        <p>Phone: <a href="tel:0423278213">0423 278 213</a></p>
        <p>Email: <a href="mailto:blake.meredith1@icloud.com">blake.meredith1@icloud.com</a></p>
        <p>Address: 179 Prosperity Street, Narangba QLD 4504</p>
        <div class="button-container">
            <button onclick="window.location='tel:0423278213'">Call Blake Now</button>
            <button onclick="window.open('https://wa.me/61423278213?text=Hello%20Blake!%20I%20would%20like%20to%20request%20a%20can%20and%20bottle%20pick-up.','_blank')">Request Pick-Up</button>
        </div>
    </section>

    <section class="dropoff-instructions">
        <h2>Drop-Off Instructions</h2>
        <p>Follow these simple steps to safely drop off your cans and bottles:</p>
        <p>1️⃣ Drive to 179 Prosperity Street, Narangba QLD 4504</p>
        <span class="arrow">⬇️</span>
        <p>2️⃣ Look for Blake’s Recycling sign and the collection bucket</p>
        <span class="arrow">⬇️</span>
        <p>3️⃣ Place your cans and bottles carefully in the bucket</p>
        <span class="arrow">⬇️</span>
        <p>4️⃣ Give Blake a call or send a WhatsApp if you need help or have questions</p>
        <p>Thank you for helping us recycle responsibly!</p>
    </section>

    <section class="map">
        <h2>Our Location</h2>
        <iframe
            src="https://www.google.com/maps?q=179+Prosperity+St,+Narangba+QLD+4504&output=embed"
            width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>

    <footer>
        <p>© 2026 Blake's Can & Bottle Recycling. All rights reserved.</p>
    </footer>

</body>
</html>