# Flipkartt
Shopping 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Flipcart - Fashion Shopping</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #0073e6;
      color: white;
      padding: 20px;
      text-align: center;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
      display: inline-block;
    }

    section {
      padding: 30px 20px;
    }

    h2 {
      color: #0073e6;
      margin-bottom: 20px;
    }

    .services {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }

    .box {
      background: #f2f2f2;
      padding: 20px;
      flex: 1 1 250px;
      max-width: 300px;
      border-radius: 10px;
      text-align: center;
    }

    footer {
      background-color: #111;
      color: #ccc;
      text-align: center;
      padding: 15px;
    }

    @media (max-width: 600px) {
      nav a {
        display: block;
        margin: 10px 0;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Flipcart</h1>
  <p>Your One-Stop Fashion Shopping Destination</p>
  <nav>
    <a href="#about">About</a>
    <a href="#services">Fashion</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Us</h2>
  <p>Flipcart is your go-to online shopping platform, specializing in the latest trends in fashion. We offer a wide variety of clothing, accessories, and more — all delivered to your doorstep.</p>
</section>

<section id="services">
  <h2>Our Fashion Categories</h2>
  <div class="services">
    <div class="box">
      <h3>Men's Wear</h3>
      <p>Trendy shirts, jeans, jackets, and more for men.</p>
    </div>
    <div class="box">
      <h3>Women's Fashion</h3>
      <p>Explore stylish dresses, sarees, tops & accessories.</p>
    </div>
    <div class="box">
      <h3>Footwear</h3>
      <p>Shoes, sneakers, sandals, heels – fashion from the ground up.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p><strong>Phone:</strong> 6299616824</p>
  <p><strong>Email:</strong> flipkart@876gmail.com</p>
</section>

<footer>
  <p>© 2025 Flipcart. All rights reserved.</p>
</footer>

</body>
</html>
