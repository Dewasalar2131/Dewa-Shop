# Dewa-Shop 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dewa Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }

        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }

        nav a {
            color: white;
            padding: 1rem;
            text-decoration: none;
            text-transform: uppercase;
        }

        nav a:hover {
            background-color: #575757;
        }

        .hero {
            text-align: center;
            padding: 2rem;
            background-color: #e8f5e9;
        }

        .hero h1 {
            margin: 0;
            color: #333;
        }

        .hero p {
            color: #666;
            font-size: 1.2rem;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            padding: 2rem;
        }

        .product {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .product img {
            max-width: 100%;
            border-radius: 8px;
        }

        .product h3 {
            color: #333;
        }

        .product p {
            color: #555;
        }

        .product button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 4px;
        }

        .product button:hover {
            background-color: #45a049;
        }

        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Dewa Shop</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
        <a href="#about">About</a>
    </nav>

    <section class="hero" id="home">
        <h1>Find the Best Deals Here</h1>
        <p>Your one-stop shop for everything you need!</p>
    </section>

    <section class="products" id="products">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 1">
            <h3>Product 1</h3>
            <p>$10.00</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 2">
            <h3>Product 2</h3>
            <p>$20.00</p>
            <button>Buy Now</button>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Product 3">
            <h3>Product 3</h3>
            <p>$15.00</p>
            <button>Buy Now</button>
        </div>
    </section>

    <footer id="contact">
        <p>Contact us at <a href="mailto:info@dewashop.com">info@dewashop.com</a></p>
        <p>&copy; 2025 Dewa Shop. All rights reserved.</p>
    </footer>
</body>
</html>
