<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gantabya Raj Football Shop</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Header Section -->
  <header>
    <div class="container">
      <h1><a href="#">Gantabya Raj Football Shop</a></h1>
      <nav>
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Shop</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Blog</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h2>Your Ultimate Destination for Premium Football Gear</h2>
      <button><a href="#">Shop Now</a></button>
      <button><a href="#">Learn More</a></button>
    </div>
  </section>

  <!-- Featured Products Section -->
  <section class="featured-products">
    <div class="container">
      <h2>Featured Products</h2>
      <div class="product-list">
        <div class="product">
          <img src="product1.jpg" alt="Product 1">
          <h3>Adidas Predator Football Boots</h3>
          <p>$99.99</p>
          <button><a href="#">Shop Now</a></button>
        </div>
        <div class="product">
          <img src="product2.jpg" alt="Product 2">
          <h3>Nike Vapor Match Ball</h3>
          <p>$49.99</p>
          <button><a href="#">Shop Now</a></button>
        </div>
        <div class="product">
          <img src="product3.jpg" alt="Product 3">
          <h3>Puma King Jersey</h3>
          <p>$29.99</p>
          <button><a href="#">Shop Now</a></button>
        </div>
        <div class="product">
          <img src="product4.jpg" alt="Product 4">
          <h3>Reusch Goalkeeper Gloves</h3>
          <p>$69.99</p>
          <button><a href="#">Shop Now</a></button>
        </div>
      </div>
    </div>
  </section>

  <!-- About Us Section -->
  <section class="about-us">
    <div class="container">
      <h2>About Gantabya Raj</h2>
      <p>Gantabya Raj is a football lover's dream, offering high-quality football gear from the best brands in the game. Whether you're a professional athlete, an amateur enthusiast, or a passionate fan, we provide top-notch products to help you perform at your best. Join us in the game and let’s play better, together.</p>
      <button><a href="#">Learn More</a></button>
    </div>
  </section>

  <!-- Customer Reviews Section -->
  <section class="reviews">
    <div class="container">
      <h2>What Our Customers Are Saying</h2>
      <div class="review">
        <p>"Gantabya Raj has everything I need! The Nike boots I bought have made a huge difference on the field." - Amit R.</p>
      </div>
      <div class="review">
        <p>"Amazing customer service and fast delivery. The Puma ball I purchased is perfect for training." - Priya K.</p>
      </div>
      <div class="review">
        <p>"Great quality and selection. I'll be coming back for all my football gear!" - Ravi D.</p>
      </div>
    </div>
  </section>

  <!-- Footer Section -->
  <footer>
    <div class="container">
      <div class="footer-links">
        <ul>
          <li><a href="#">Shop</a></li>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact</a></li>
          <li><a href="#">Blog</a></li>
        </ul>
      </div>
      <div class="social-media">
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
        <a href="#">Twitter</a>
        <a href="#">YouTube</a>
      </div>
      <p>&copy; 2024 Gantabya Raj Football Shop. All rights reserved.</p>
    </div>
  </footer>

</body>
</html>
/* Basic Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* Body and Typography */
body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f4;
  color: #333;
}

a {
  text-decoration: none;
  color: inherit;
}

h1, h2, h3 {
  color: #333;
}

h2 {
  font-size: 24px;
  margin-bottom: 20px;
}

/* Header Styles */
header {
  background-color: #333;
  color: white;
  padding: 20px 0;
}

header .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

header h1 a {
  color: white;
  font-size: 28px;
  font-weight: bold;
}

header nav ul {
  list-style: none;
}

header nav ul li {
  display: inline;
  margin-left: 20px;
}

header nav ul li a {
  color: white;
  font-size: 16px;
}

/* Hero Section */
.hero {
  background-image: url('hero-bg.jpg');
  background-size: cover;
  background-position: center;
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 36px;
  margin-bottom: 20px;
  color: white;
}

.hero button {
  background-color: #ff6f61;
  padding: 10px 20px;
  border: none;
  color: white;
  font-size: 16px;
  cursor: pointer;
  margin: 10px;
}

.hero button a {
  color: white;
}

/* Featured Products Section */
.featured-products {
  padding: 40px 20px;
  background-color: #fff;
}

.featured-products .product-list {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}

.featured-products .product {
  width: 22%;
  background-color: #f9f9f9;
  padding: 20px;
  border-radius: 5px;
  text-align: center;
}

.featured-products .product img {
  max-width: 100%;
  border-radius: 5px;
}

.featured-products .product button {
  background-color: #333;
  padding: 10px 20px;
  border: none;
  color: white;
  cursor: pointer;
}

/* About Us Section */
.about-us {
  background-color: #f9f9f9;
  padding: 40px 20px;
  text-align: center;
}

.about-us button {
  background-color: #ff6f61;
  padding: 10px 20px;
  border: none;
  color: white;
  font-size: 16px;
  cursor: pointer;
  margin-top: 20px;
}

/* Customer Reviews Section */
.reviews {
  padding: 40px 20px;
  background-color: #fff;
}

.reviews .review {
  margin-bottom: 20px;
  font-style: italic;
}

/* Footer Section */
footer {
  background-color: #333;
  color: white;
  padding: 20px 0;
  text-align: center;
}

footer .footer-links ul {
  list-style: none;
  margin-bottom: 20px;
}

footer .footer-links ul li {
  display: inline;
  margin-right: 15px;
}

footer .social-media a {
  color: white;
  margin-right: 15px;
}

footer p {
  margin-top: 20px;
}


<!---
gantabya123/gantabya123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
