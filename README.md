<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>SVAK | Accessories</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #fff;
      color: #333;
    }

    header {
      background-color: #fff;
      text-align: center;
      padding: 2rem 0;
      border-bottom: 1px solid #ddd;
    }

    header h1 {
      font-size: 2.5rem;
      letter-spacing: 2px;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
      background-color: #f8f8f8;
    }

    nav a {
      text-decoration: none;
      color: #333;
      font-weight: bold;
      letter-spacing: 1px;
    }

    nav a:hover {
      color: #b00020;
    }

    .section {
      padding: 3rem 2rem;
      text-align: center;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 2rem;
      text-transform: uppercase;
      letter-spacing: 1px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 2rem;
    }

    .product {
      border: 1px solid #ddd;
      padding: 1rem;
    }

    .product img {
      width: 100%;
      height: auto;
    }

    .product h3 {
      font-size: 1.1rem;
      margin: 0.5rem 0 0.2rem;
    }

    .product p {
      font-size: 0.9rem;
      color: #555;
    }

    footer {
      background-color: #f1f1f1;
      padding: 2rem;
      text-align: center;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>SVAK</h1>
    <p> Accessories from Mauritius</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <!-- Necklaces -->
  <section class="section">
    <h2>Necklaces</h2>
    <div class="products">
      <div class="product">
        <img src="necklace2.jpg" alt="Model 1" />
        <h3>BULKY FLOWER SET</h3>
        <p>Rs 700</p>
      </div>
      <div class="product">
        <img src="necklace3.jpg" alt="Model 2" />
        <h3>DIAMOND SUNFLOWER</h3>
        <p>Rs 450</p>
      </div>
      <div class="product">
        <img src="necklace4.jpg" alt="Model 3" />
        <h3>GOLD HEART & DIAMOND  </h3>
        <p>Rs 900</p>
      </div>
      <div class="product">
        <img src="necklace5.jpg" alt="Model 4" />
        <h3>GOLD BUTTERFLIES</h3>
        <p>Rs 900</p>
      </div>
    </div>
  </section>

  <!-- Keychains -->
  <section class="section">
    <h2>Keychains</h2>
    <div class="products">
      <div class="product">
        <img src="keychain1.jpg" alt="Model 1" />
        <h3>BUTTERFLY & FLOWER</h3>
        <p>Rs 250</p>
      </div>
      <div class="product">
        <img src="keychain2.jpg" alt="Model 2" />
        <h3>SILVER & FLOWER</h3>
        <p>Rs 180</p>
      </div>
      <div class="product">
        <img src="keychain3.jpg" alt="Model 3" />
        <h3>SILVER HEART</h3>
        <p>Rs 140</p>
      </div>
      <div class="product">
        <img src="keychain4.jpg" alt="Model 4" />
        <h3>SILVER ROUND</h3>
        <p>Rs 140</p>
      </div>
    </div>
  </section>

  <!-- Bags -->
  <section class="section">
    <h2>Bags</h2>
    <div class="products">
      <div class="product">
        <img src="bag1.jpg" alt="Model 1" />
        <h3>BEACH TOTE</h3>
        <p>Rs 550</p>
      </div>
      <div class="product">
        <img src="bag2.jpg" alt="Model 2" />
        <h3>FLORAL GRANDMA</h3>
        <p>Rs 725</p>
      </div>
    </div>
  </section>

  <!-- Teddy Bear -->
  <section class="section">
    <h2>Teddy Bear</h2>
    <div class="products">
      <div class="product">
        <img src="teddy.jpg" alt="Teddy Bear" />
        <h3>SUPPORT TEDDY</h3>
        <p>Rs 300</p>
      </div>
    </div>
  </section>

  <!-- Mirror -->
  <section class="section">
    <h2>Mirror</h2>
    <div class="products">
      <div class="product">
        <img src="pocketmirror.jpg" alt="Mirror" />
        <h3>POCKET MIRROR</h3>
        <p>Rs 750</p>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 SVAK Mauritius. All rights reserved.
  </footer>

</body>
</html>



