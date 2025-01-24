<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Professional Electric Generator Rental Services">
    <title>SHAIK KALESHA GENERATORS RENTAL SERVICE</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            color: #34495e;
            background-color: #f7f9fc;
        }

        .bismillah-container {
            text-align: center;
            margin-top: 20px;
            padding: 20px;
            background: linear-gradient(to right, #1abc9c, #16a085);
        }

        .bismillah-container img {
            max-width: 100px;
            height: auto;
        }

        header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background: linear-gradient(to right, #2c3e50, #1abc9c);
            color: white;
            padding: 20px;
        }

        header img {
            max-width: 100px;
            height: auto;
            border-radius: 50%;
        }

        header div {
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background: #2c3e50;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 500;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .container {
            padding: 20px;
        }

        .services,
        .products,
        .about,
        .contact {
            margin-bottom: 20px;
        }

        .services h2,
        .products h2,
        .about h2,
        .contact h2 {
            color: #f39c12;
        }

        .product-item {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
            margin-bottom: 20px;
            text-align: center;
            background: #fff;
            position: relative;
            transition: transform 0.3s ease;
        }

        .product-item img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            transition: transform 0.3s ease;
        }

        .product-item:hover {
            transform: scale(1.05);
        }

        .product-item:hover img {
            transform: scale(1.1);
        }

        button {
            background-color: #1abc9c;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
            margin-top: 10px;
        }

        button:hover {
            background-color: #16a085;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        /* Product details frames */
        .product-frame {
            background: #fff;
            border: 2px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .product-frame img {
            max-width: 200px;
            height: auto;
            margin-right: 20px;
        }

        .product-frame button {
            background-color: #f39c12;
        }

        .order-popup {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            justify-content: center;
            align-items: center;
            z-index: 1000;
        }

        .order-popup .content {
            background: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            max-width: 400px;
            width: 100%;
        }

        .order-popup button {
            background-color: #e74c3c;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            font-size: 1em;
            border-radius: 5px;
        }

        .order-popup button:hover {
            background-color: #c0392b;
        }
    </style>
</head>

<body>
    <div class="bismillah-container">
        <img src="bishmillah.jpg.webp" alt="Bismillah with Crescent Moon">
    </div>
    <header>
        <img src="nayee.jpg" alt="Pawan Kalyan">
        <div>
            <h1 style="margin: 0;">SHAIK KALESHA GENERATORS RENTAL SERVICE</h1>
            <p style="margin: 0; font-size: 1.2em;">Generators for Every Need</p>
        </div>
        <img src="30kv.jpeg" alt="Generator">
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#services">Services</a>
        <a href="#products">Products</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="services" class="services">
            <h2>Our Services</h2>
            <ul>
                <li>
                    <p>20 kV Generator</p>
                    <img src="30kv.jpeg" alt="20 kV Generator">
                    <button onclick="orderNow('20 kV Generator')">Order</button>
                </li>
                <li>
                    <p>30 kV Generator</p>
                    <img src="80kv.jpeg" alt="30 kV Generator">
                    <button onclick="orderNow('30 kV Generator')">Order</button>
                </li>
                <li>
                    <p>40 kV Generator</p>
                    <img src="40kv.jpeg" alt="40 kV Generator">
                    <button onclick="orderNow('40 kV Generator')">Order</button>
                </li>
                <li>
                    <p>50 kV Generator</p>
                    <img src="50kv.jpeg" alt="50 kV Generator">
                    <button onclick="orderNow('50 kV Generator')">Order</button>
                </li>
                <li>
                    <p>60 kV Generator</p>
                    <img src="60kv.jpeg" alt="60 kV Generator">
                    <button onclick="orderNow('60 kV Generator')">Order</button>
                </li>
                <li>
                    <p>80 kV Generator</p>
                    <img src="80kv.jpeg" alt="80 kV Generator">
                    <button onclick="orderNow('80 kV Generator')">Order</button>
                </li>
            </ul>
        </section>
        <section id="products" class="products">
            <h2>Our Products</h2>
            <div class="product-item" onclick="showProductDetails('20 kV Generator', '30kv.jpeg', '20 kV Generator details')">
                <img src="30kv.jpeg" alt="20 kV Generator">
                <p>20 kV Generator</p>
            </div>
            <div class="product-item" onclick="showProductDetails('30 kV Generator', '40kv.jpeg', '30 kV Generator details')">
                <img src="40kv.jpeg" alt="30 kV Generator">
                <p>30 kV Generator</p>
            </div>
        </section>
        <section id="about" class="about">
            <h2>About Us</h2>
            <p>We provide high-quality, reliable electric generators for all your power needs. Our services are customer-focused and affordable.</p>
        </section>
    </div>
    <footer>
        <p>Contact us at: <a href="tel:+919100569047" style="color: #f39c12;">+91 9100569047</a></p>
    </footer>

    <!-- Product Details Popup -->
    <div class="order-popup" id="orderPopup">
        <div class="content">
            <h3>Order Details</h3>
            <p id="productDetails">Product details will be displayed here.</p>
            <button onclick="closeOrderPopup()">Close</button>
        </div>
    </div>

    <script>
        function showProductDetails(name, imgSrc, details) {
            const popup = document.getElementById('orderPopup');
            const productDetails = document.getElementById('productDetails');
            productDetails.innerHTML = `
                <div class="product-frame">
                    <img src="${imgSrc}" alt="${name}">
                    <div>
                        <h3>${name}</h3>
                        <p>${details}</p>
                        <button onclick="orderNow('${name}')">Order Now</button>
                    </div>
                </div>
            `;
            popup.style.display = 'flex';
        }

        function orderNow(product) {
            const contactInfo = `
                Product: ${product}
                Name: Sk Nayeem
                Phone: +91 9100569047
                Email: sknayeemrecersk@gmail.com
                Address: Auto Nagar, Nellore 4
            `;
            if (confirm(`Do you want to call for this product?\n\nContact Info:\n${contactInfo}`)) {
                window.location.href = "tel:+919100569047";
            }
        }

        function closeOrderPopup() {
            document.getElementById('orderPopup').style.display = 'none';
        }
    </script>
</body>

</html>
