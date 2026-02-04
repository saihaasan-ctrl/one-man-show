<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>One Man Show</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #fff;
      color: #111;
    }
    header {
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid #eee;
    }
    h1 {
      font-size: 22px;
      letter-spacing: 2px;
    }
    .hero {
      text-align: center;
      padding: 80px 20px;
    }
    .hero h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 30px;
      padding: 40px;
    }
    .card {
      border: 1px solid #eee;
      padding: 15px;
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 280px;
      object-fit: cover;
      background: #f5f5f5;
    }
    .card button {
      margin-top: 10px;
      padding: 10px 20px;
      background: black;
      color: white;
      border: none;
      cursor: pointer;
    }
    footer {
      text-align: center;
      padding: 20px;
      border-top: 1px solid #eee;
      font-size: 14px;
    }
  </style>
</head>
<body>

<header>
  <h1>ONE MAN SHOW</h1>
</header>

<section class="hero">
  <h2>Minimal. Bold. Timeless.</h2>
  <p>Premium men’s wear designed for confidence.</p>
</section>

<section class="products">
  <div class="card">
    <img src="" alt="Product">
    <h3>Classic Black Tee</h3>
    <p>$29</p>
    <button>Buy Now</button>
  </div>
  <!-- Duplicate this card for 15 products -->
</section>

<footer>
  © 2026 One Man Show
</footer>

</body>
</html>