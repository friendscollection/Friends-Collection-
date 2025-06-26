<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Friends Collection</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f8f8f8; }
    header { background: #000; color: #fff; padding: 20px; text-align: center; }
    nav { background: #333; padding: 10px; text-align: center; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; }
    .banner { background: url('https://via.placeholder.com/1200x400?text=Friends+Collection') no-repeat center/cover; height: 300px; }
    .section { padding: 40px 20px; max-width: 1200px; margin: auto; }
    .products { display: flex; flex-wrap: wrap; gap: 20px; justify-content: center; }
    .product { background: #fff; padding: 20px; width: 250px; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    .product img { width: 100%; border-radius: 8px; }
    .product h3 { margin: 10px 0 5px; }
    .product p { margin: 5px 0; }
    .product a { display: inline-block; margin-top: 10px; background: #000; color: #fff; padding: 10px; border-radius: 5px; text-decoration: none; }
    footer { background: #222; color: #aaa; text-align: center; padding: 20px; }
  </style>
</head>
<body>
  <header>
    <h1>Friends Collection</h1>
    <p>Trendy Fashion Delivered to Your Doorstep!</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#products">Shop</a>
    <a href="#faq">FAQ</a>
    <a href="#contact">Contact</a>
  </nav>
  <div class="banner"></div>
  <section class="section" id="products">
    <h2>Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/250x250?text=Fashion+Item+1" alt="T-shirt">
        <h3>White T-Shirt</h3>
        <p>Price: Rs. 799</p>
        <a href="https://wa.me/923369966056?text=I%20want%20to%20order%20White%20T-Shirt">Order on WhatsApp</a>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/250x250?text=Fashion+Item+2" alt="Abaya">
        <h3>Black Abaya</h3>
        <p>Price: Rs. 2200</p>
        <a href="https://wa.me/923369966056?text=I%20want%20to%20order%20Black%20Abaya">Order on WhatsApp</a>
      </div>
    </div>
  </section>
  <section class="section" id="faq">
    <h2>Frequently Asked Questions</h2>
    <p><strong>Q:</strong> What is Friends Collection?<br><strong>A:</strong> An online fashion store offering stylish clothing and accessories.</p>
    <p><strong>Q:</strong> Do you offer Cash on Delivery?<br><strong>A:</strong> Yes, we do within Pakistan.</p>
    <p><strong>Q:</strong> What are the delivery charges?<br><strong>A:</strong> Rs. 200 (Free above Rs. 3000)</p>
    <p><strong>Q:</strong> Can I return a product?<br><strong>A:</strong> Yes, within 7 days if unused and in original packaging.</p>
  </section>
  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>WhatsApp: +92 336 9966056</p>
    <p>Email: support@friendscollection.pk</p>
  </section>
  <footer>
    &copy; 2025 Friends Collection. All Rights Reserved.
  </footer>
</body>
</html>
