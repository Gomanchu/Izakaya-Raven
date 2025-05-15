<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Izakaya Raven</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+JP&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #1c1c1c;
      color: #ffffff;
      line-height: 1.6;
    }
    header, section {
      padding: 60px 20px;
      text-align: center;
    }
    h1, h2, h3 {
      font-family: 'Noto Serif JP', serif;
    }
    .hero {
      background: url('https://source.unsplash.com/1600x900/?sake,bar') no-repeat center center/cover;
      color: white;
      padding: 120px 20px;
    }
    .btn, .btn-outline {
      margin: 10px;
      padding: 12px 24px;
      border: none;
      cursor: pointer;
      font-weight: bold;
      text-decoration: none;
    }
    .btn {
      background-color: #cda34f;
      color: #1c1c1c;
    }
    .btn-outline {
      border: 2px solid #cda34f;
      color: #cda34f;
      background: transparent;
    }
    ul {
      list-style: none;
      padding: 0;
    }
    li {
      margin: 10px 0;
    }
    .image-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }
    .image-grid img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    form {
      max-width: 400px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    input, textarea, button {
      margin: 10px 0;
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-family: inherit;
    }
    button {
      background-color: #cda34f;
      color: #1c1c1c;
      cursor: pointer;
    }
    footer {
      background-color: #111;
      padding: 20px;
      text-align: center;
    }
    footer a {
      color: #cda34f;
      margin: 0 10px;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <section class="hero">
    <h1>Izakaya Raven</h1>
    <p>Crafted for Sake Enthusiasts</p>
    <a href="#menu" class="btn">View Menu</a>
    <a href="#reservation" class="btn-outline">Make a Reservation</a>
  </section>

  <section id="about">
    <h2>Our Passion for Sake</h2>
    <p>At Izakaya Raven, we celebrate Japan’s finest sake—from rare regional brews to bold modern styles. Every bottle tells a story.</p>
    <img src="https://source.unsplash.com/600x400/?pouring,sake" alt="Pouring sake" style="width:100%;max-width:600px;border-radius:10px;">
  </section>

  <section id="menu">
    <h2>Our Selection</h2>
    <h3>Sake</h3>
    <ul>
      <li>Dassai 23 – Clean, elegant, fruity aroma</li>
      <li>Hakkaisan – Crisp, dry, Niigata-style</li>
      <li>Juyondai – Rich and full-bodied (limited)</li>
    </ul>

   <section id="menu">
  <h2>Our Selection</h2>
  <div class="menu-section">
    <h3>Shochu</h3>
    <ul>
      <li>Kuro Kirishima (Sweet Potato)</li>
      <li>Iichiko (Barley)</li>
    </ul>
  </div>

  <div class="menu-section">
    <h3>Pairing Bites</h3>
    <ul>
      <li>Grilled Squid with Yuzu Kosho</li>
      <li>Sashimi Sampler</li>
      <li>Homemade Pickles</li>
    </ul>
  </div>
</section>
  </section>

  <section id="gallery">
    <h2>Inside Izakaya Raven</h2>
    <div class="image-grid">
      <img src="https://source.unsplash.com/400x300/?izakaya" alt="Interior">
      <img src="https://source.unsplash.com/400x300/?sake" alt="Sake Bottles">
      <img src="https://source.unsplash.com/400x300/?japanese,food" alt="Japanese Food">
    </div>
  </section>

  <section id="location">
    <h2>Visit Us</h2>
    <p>102 Prescott Street, Demarest, United States</p>
    <p>Open: Mon–Sat, 5:00 PM – Midnight</p>
    <p>Closed: Sunday</p>
    <iframe
      src="https://www.google.com/maps/embed?pb=!1m18..."
      width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
  </section>

  <section id="reservation">
    <h2>Reserve a Table</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="Phone Number" placeholder="Phone Number" required>
      <input type="datetime-local" required>
      <textarea placeholder="Special requests"></textarea>
      <button type="submit">Submit</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Izakaya Raven</p>
    <nav>
      <a href="#">Instagram</a>
      <a href="#">Facebook</a>
    </nav>
  </footer>
