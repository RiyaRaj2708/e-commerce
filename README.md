# e-commerce
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TrendiiHut</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    body {
      background-color: #fffefc;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: url('image.png') no-repeat center center;
      background-size: cover;
      padding: 4rem 2rem;
      text-align: center;
      color: #fff;
    }
    header h1 {
      font-size: 3rem;
      letter-spacing: 2px;
      background-color: rgba(0,0,0,0.5);
      display: inline-block;
      padding: 0.5rem 1rem;
      border-radius: 10px;
    }
    nav {
      background-color: #fff0f6;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      position: sticky;
      top: 0;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
    }
    nav a {
      color: #d63384;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #a61e4d;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1607082349566-1873429a1f99') no-repeat center center/cover;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      position: relative;
    }
    .hero::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.4);
    }
    .hero h2 {
      position: relative;
      font-size: 3rem;
      padding: 0 1rem;
    }
    .features {
      padding: 4rem 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      background-color: #fff7fb;
    }
    .feature {
      background-color: #fff;
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
      text-align: center;
      transition: transform 0.3s ease;
    }
    .feature:hover {
      transform: translateY(-5px);
    }
    .feature h3 {
      color: #b5179e;
      margin-bottom: 0.5rem;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background-color: #ffd6ec;
      color: #6a0f49;
    }
    .social-icons {
      margin-top: 1rem;
    }
    .social-icons a {
      margin: 0 10px;
      color: #d63384;
      text-decoration: none;
      font-size: 1.5rem;
      transition: color 0.3s;
    }
    .social-icons a:hover {
      color: #a61e4d;
    }
    @media (max-width: 768px) {
      .hero h2 {
        font-size: 2rem;
      }
      nav {
        flex-direction: column;
        gap: 1rem;
      }
    }
  </style>
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
  <header>
    <h1>TohfaHut</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Shop</a>
    <a href="#">Categories</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <section class="hero">
    <h2>Unbox Happiness With Every Tohfa 🎁</h2>
  </section>

  <section class="features">
    <div class="feature">
      <h3>🎁 Curated Gifts</h3>
      <p>Handpicked for every occasion, delivered with love.</p>
    </div>
    <div class="feature">
      <h3>🚚 Fast Delivery</h3>
      <p>Pan India shipping with tracking and care.</p>
    </div>
    <div class="feature">
      <h3>🛍️ General Store Vibes</h3>
      <p>From daily use to unique surprises, sab milega yahaan.</p>
    </div>
    <div class="feature">
      <h3>💬 24/7 Support</h3>
      <p>Hum hamesha hai aapke saath – kabhi bhi, kahin bhi.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 TohfaHut. All rights reserved. Designed with ❤️ for every emotion.</p>
    <div class="social-icons">
      <a href="https://instagram.com/tohfahut" target="_blank"><i class="fab fa-instagram"></i></a>
    </div>
  </footer>
</body>
</html>
