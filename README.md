# svak

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bella Accessories | Stylish Jewelry & More</title>
    <style>
        /* Modern, clean styling */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #f9f3f0;
            color: #333;
        }
        header {
            background: #fff;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            padding: 15px 0;
            text-align: center;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #d4a373;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1599643478518-a784e5dc4c8f?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80') no-repeat center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
        }
        .hero h1 {
            font-size: 48px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 30px;
        }
        .product-card {
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            margin: 15px;
            width: 250px;
            overflow: hidden;
            transition: transform 0.3s;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-img {
            height: 200px;
            background: #eee;
            background-size: cover;
            background-position: center;
        }
        .product-info {
            padding: 15px;
        }
        .price {
            font-weight: bold;
            color: #d4a373;
            font-size: 18px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: #333;
            color: white;
        }
        @media (max-width: 768px) {
            .hero h1 { font-size: 32px; }
            .product-card { width: 100%; }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Bella Accessories</div>
        <nav>
            <a href="#shop">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h1>Handcrafted Jewelry & Accessories</h1>
    </section>

    <section id="shop" class="products">
        <!-- Product 1 -->
        <div class="product-card">
            <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1605100804763-247f67b3557e?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80');"></div>
            <div class="product-info">
                <h3>Gold Pearl Necklace</h3>
                <p>Elegant and timeless.</p>
                <p class="price">$29.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
        <!-- Product 2 -->
        <div class="product-card">
            <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1599643478518-a784e5dc4c8f?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80');"></div>
            <div class="product-info">
                <h3>Silver Hoop Earrings</h3>
                <p>Minimalist and chic.</p>
                <p class="price">$19.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
        <!-- Product 3 -->
        <div class="product-card">
            <div class="product-img" style="background-image: url('https://images.unsplash.com/photo-1535632066927-ab7c9ab60908?ixlib=rb-1.2.1&auto=format&fit=crop&w=634&q=80');"></div>
            <div class="product-info">
                <h3>Leather Crossbody Bag</h3>
                <p>Stylish and practical.</p>
                <p class="price">$49.99</p>
                <button>Add to Cart</button>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Bella Accessories. All rights reserved.</p>
    </footer>
</body>
</html>
