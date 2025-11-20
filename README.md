# Cassava-cat-litter
Cassava cat litter
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Starch Cat Litter</title>
  <style>
    /* Colors: Brown #8B4513, Yellow #FFD700, Light Brown #F5DEB3 */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #F5DEB3;
      color: #333;
    }

    header {
      background-color: #8B4513;
      color: #FFD700;
      padding: 20px;
      text-align: center;
    }

    nav {
      background-color: #DEB887;
      display: flex;
      justify-content: center;
      padding: 10px 0;
    }

    nav a {
      color: #8B4513;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      color: #FFD700;
    }

    main {
      padding: 20px;
      max-width: 1200px;
      margin: auto;
    }

    section {
      margin-bottom: 40px;
    }

    h1, h2 {
      color: #8B4513;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .product {
      background-color: #FFF8DC;
      border: 2px solid #DEB887;
      border-radius: 10px;
      padding: 15px;
      flex: 1 1 calc(25% - 20px);
      box-sizing: border-box;
      text-align: center;
    }

    .product img {
      max-width: 100%;
      border-radius: 10px;
    }

    .product button {
      background-color: #8B4513;
      color: #FFD700;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }

    .product button:hover {
      background-color: #A0522D;
    }

    footer {
      background-color: #8B4513;
      color: #FFD700;
      text-align: center;
      padding: 20px;
    }

    /* Contact form */
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #DEB887;
      border-radius: 5px;
      box-sizing: border-box;
    }

    .contact-form button {
      background-color: #8B4513;
      color: #FFD700;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    .contact-form button:hover {
      background-color: #A0522D;
    }

    @media (max-width: 768px) {
      .products {
        flex-direction: column;
      }

      .product {
        flex: 1 1 100%;
      }
    }

  </style>
</head>
<body>

<header>
  <h1>Starch Cat Litter</h1>
  <p>Eco-friendly, Dust-free, Safe for Cats</p>
</header>

<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#shop">Shop</a>
  <a href="#contact">Contact</a>
</nav>

<main>
  <section id="home">
    <h2>Welcome to Starch Cat Litter</h2>
    <p>Our premium starch-based cat litter is biodegradable, low-dust, and safe for your feline friends. Perfect for homes that care about the environment and your cat's health.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>We are dedicated to providing the highest quality cat litter made from natural starch. Our products are designed to be eco-friendly, clump easily, and reduce odors, making cat care simple and safe.</p>
  </section>

  <section id="shop">
    <h2>Shop Our Products</h2>
    <div class="products">
      <div class="product">
        <img src="https://via.placeholder.com/150" alt="Starch Cat Litter 4L">
        <h3>Starch Cat Litter 4L</h3>
        <p>$6.50 per bag</p>
        <button>Add to Cart</button>
      </div>
      <div class="product">
        <img src="https://via.placeholder.com/150" alt="Starch Cat Litter 8L">
        <h3>Starch Cat Litter 8L</h3>
        <p>$12.00 per bag</p>
        <button>Add to Cart</button>
      </div>
      <!-- Add more products here -->
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>
</main>

<footer>
  <p>&copy; 2025 Starch Cat Litter. All Rights Reserved.</p>
</footer>

<script>
  // Simple Contact Form Alert
  const form = document.querySelector('.contact-form');
  form.addEventListener('submit', function(e) {
    e.preventDefault();
    alert('Thank you for contacting us! We will get back to you soon.');
    form.reset();
  });
</script>

</body>
</html>
