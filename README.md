<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Masaalaaa - House of Spice</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap'); /* Custom font for the header */
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
        }

        header {
            background-color: #d4af37;
            color: #fff;
            padding: 10px 0; /* Reduced padding to make header less bulky */
            text-align: center;
        }

        header h1 {
            font-family: 'Great Vibes', cursive; /* Applying the custom font */
            font-size: 3rem;
            margin-bottom: 0; /* Removed bottom margin to bring "House of Spice" closer */
        }

        header p {
            margin-top: 0; /* Removed top margin to bring "House of Spice" closer */
            font-size: 1.2rem; /* Adjusted font size if needed */
        }

        nav {
            background-color: #fff;
            padding: 10px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        nav a {
            color: #d4af37;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            font-weight: bold;
        }

        .container {
            padding: 20px;
        }

        .section {
            margin: 20px 0;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .hero-text {
            color: #333; /* Darker color for better visibility */
            font-size: 24px;
            margin-bottom: 20px;
        }

        footer {
            background-color: #d4af37;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        .product-list {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
        }

        .product {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            flex: 1;
            min-width: 200px;
            max-width: 250px;
        }

        .product h3 {
            color: #d4af37;
        }

        .product p {
            font-size: 14px;
            color: #555;
        }

        .order-button {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 15px;
            background-color: #d4af37;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 16px;
            transition: background-color 0.3s ease;
        }

        .order-button:hover {
            background-color: #b4942e;
        }
    </style>
</head>
<body>
    <header>
        <h1>Masaalaaa</h1>
        <p>House of Spice</p>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container" id="home">
        <div class="section">
            <h2>Welcome to Masaalaaa</h2>
            <p class="hero-text">Your source for the finest spices directly from House of Spice.</p>
        </div>
        <div class="section" id="about">
            <h2>About Us</h2>
            <p>Welcome to Masaalaaa, your number one source for authentic spices and masala. We are based in Malad, Mumbai, India, with our farms located in Hubli, Karnataka, where we manufacture our spices. We are dedicated to giving you the very best of our products, with a focus on quality, freshness, and customer service.</p>
            <p>Founded in Malad, Mumbai, Masaalaaa has come a long way from its beginnings. We are the manufacturers, directly buying from the farm and distributing all over India. Our passion for providing the finest spices drove us to do intense research and gave us the impetus to turn hard work and inspiration into a booming online store.</p>
        </div>
        <div class="section" id="products">
            <h2>Our Products</h2>
            <div class="product-list">
                <div class="product">
                    <h3>Bedgi Chilli</h3>
                    <p>Known for its vibrant color and moderate heat, Bedgi chilli is a popular choice for Indian cuisine.</p>
                    <a href="https://wa.me/918169751309?text=I'm%20interested%20in%20Bedgi%20Chilli" class="order-button">Place Order</a>
                </div>
                <div class="product">
                    <h3>Kashmiri Chilli</h3>
                    <p>With its deep red color and mild flavor, Kashmiri chilli is perfect for adding color to dishes without overwhelming heat.</p>
                    <a href="https://wa.me/918169751309?text=I'm%20interested%20in%20Kashmiri%20Chilli" class="order-button">Place Order</a>
                </div>
                <div class="product">
                    <h3>Turmeric Powder</h3>
                    <p>Our turmeric powder is rich in color and flavor, sourced directly from the farms of Hubli.</p>
                    <a href="https://wa.me/918169751309?text=I'm%20interested%20in%20Turmeric%20Powder" class="order-button">Place Order</a>
                </div>
                <!-- Add more products here -->
            </div>
        </div>
    </div>
    <footer>
        <p>Contact Us:</p>
        <p>Email: masaalaaa.in@gmail.com</p>
        <p>Phone: +91 82170 95238, +91 81697 51309</p>
        &copy; 2024 Masaalaaa. All rights reserved. Based in Malad, Mumbai.
    </footer>
    <script>
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>

