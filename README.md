<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Makeup Wonderland</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        h2 {
            color: #4CAF50;
        }
        .monstera {
            display: block;
            margin: 0 auto 20px auto;
            max-width: 100%;
        }
        .about-me, .products, .benefits, .contact {
            margin-bottom: 40px;
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0 10px 0;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }
        .contact-form button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Your Makeup Wonderland</h1>
        <p>Embrace Your Natural Beauty</p>
    </header>

    <div class="container">
        <section class="about-me">
            <h2>About Me</h2>
            <p>Hello! I'm [Your Name], a passionate makeup enthusiast dedicated to helping beautiful Black women enhance their natural beauty with the best products. Join me on this journey to discover makeup that celebrates our unique features and skin tones.</p>
        </section>

        <section class="products">
            <h2>Our Products</h2>
            <img src="https://via.placeholder.com/600x400" alt="Monstera" class="monstera">
            <p>Our makeup products are specially formulated to cater to the diverse skin tones of Black women. From foundations to lipsticks, each product is designed to highlight your natural beauty and make you feel confident and radiant.</p>
        </section>

        <section class="benefits">
            <h2>Benefits</h2>
            <ul>
                <li>Long-lasting wear for all-day confidence</li>
                <li>Enriched with nourishing ingredients for healthy skin</li>
                <li>Wide range of shades to match every skin tone</li>
                <li>Cruelty-free and environmentally friendly</li>
            </ul>
        </section>

        <section class="contact">
            <h2>Contact</h2>
            <p>I'd love to hear from you! Whether you have questions about our products or want to share your makeup journey, feel free to reach out.</p>
            <form class="contact-form">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="5" required></textarea>
                <button type="submit">Send</button>
            </form>
        </section>
    </div>
</body>
</html>
