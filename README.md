# trendora.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Trendora - Anime Merch Store</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap');
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      padding: 0;
      background: #121212;
      color: #d1c4e9;
      scroll-behavior: smooth;
      text-shadow: 0 0 5px #ba68c8;
    }
    header {
      background: url('https://wallpapercave.com/wp/wp11943801.jpg') center/cover no-repeat;
      color: #d1c4e9;
      padding: 80px 20px;
      text-align: center;
      position: relative;
      overflow: hidden;
      text-shadow: 0 0 10px #ba68c8;
    }
    header::after {
      content: '';
      background: rgba(0,0,0,0.6);
      top: 0;
      left: 0;
      bottom: 0;
      right: 0;
      position: absolute;
      z-index: 0;
    }
    header h1, header p { position: relative; z-index: 1; }
    header h1 {
      margin: 0;
      font-size: 3.5rem;
      font-weight: 700;
      letter-spacing: 3px;
      color: #d1c4e9;
      text-shadow: 0 0 15px #ba68c8;
    }
    header p {
      margin: 10px 0 0;
      font-size: 1.5rem;
      color: #d1c4e9;
      text-shadow: 0 0 10px #ba68c8;
    }
    nav {
      display: flex;
      justify-content: center;
      background: #1a1a1a;
      position: sticky;
      top: 0;
      z-index: 10;
    }
    nav a {
      color: #d1c4e9;
      padding: 16px 25px;
      text-decoration: none;
      display: block;
      font-weight: 600;
      transition: 0.3s;
      text-shadow: 0 0 5px #ba68c8;
    }
    nav a:hover {
      background: #333;
      color: #ba68c8;
      text-shadow: 0 0 10px #ba68c8;
    }
    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 50px;
      font-size: 2.5rem;
      color: #ba68c8;
      text-shadow: 0 0 8px #d1c4e9;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 35px;
    }
    .card {
      background: #1e1e1e;
      padding: 25px;
      border-radius: 15px;
      text-align: center;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      box-shadow: 0 6px 18px rgba(186, 104, 200, 0.2);
      overflow: hidden;
      color: #d1c4e9;
      text-shadow: 0 0 5px #ba68c8;
    }
    .card img {
      width: 100%;
      max-height: 280px;
      object-fit: cover;
      border-radius: 12px;
      margin-bottom: 15px;
      transition: transform 0.3s ease;
    }
    .card:hover img {
      transform: scale(1.1);
    }
    .card h3 {
      margin: 12px 0;
      font-size: 1.4rem;
      font-weight: 700;
      color: #ba68c8;
      text-shadow: 0 0 8px #d1c4e9;
    }
    .price {
      font-weight: bold;
      color: #ffffff; /* changed Taka text to white */
      font-size: 1.2rem;
      margin: 10px 0;
      text-shadow: 0 0 5px #ffffff;
    }
    footer {
      background: #1a1a1a;
      color: #d1c4e9;
      text-align: center;
      padding: 30px;
      font-size: 0.95rem;
      text-shadow: 0 0 5px #ba68c8;
    }
    footer a {
      color: #ba68c8;
      text-decoration: none;
      margin: 0 12px;
      text-shadow: 0 0 5px #d1c4e9;
    }
    footer a:hover {
      text-decoration: underline;
    }
    .btn {
      display: inline-block;
      background: #ba68c8;
      color: #fff;
      padding: 10px 25px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: 600;
      margin-top: 10px;
      transition: 0.3s;
      text-shadow: 0 0 5px #d1c4e9;
    }
    .btn:hover {
      background: #9c27b0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Trendora</h1>
    <p>Breathtaking Anime Merchandise for Every Otaku</p>
  </header>

  <nav>
    <a href="#tees-merch">Tees & Merch</a>
    <a href="#keychains-goods">Keychains & Goods</a>
    <a href="#kimono">Kimonos</a>
    <a href="#outfits">Anime Outfits</a>
    <a href="#figures">Figures</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="tees-merch">
    <h2>Tees & Anime Merchandise</h2>
    <div class="grid">
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.amiami.com/eng/detail/?gcode=FIGURE-035132&ref=home&ictx=1&source=images&cd=&ved=2ahUKEwjYy4-e4Lr_AhUF7GoFHdRjCvYQjRx6BAgAEAU&psig=AOvVaw1IjRl1u7xeMOPtSnFts_KN&ust=1692889410423000" alt="Anime Graphic Tee">
        <h3>Naruto Graphic Tee</h3>
        <p class="price">500 TK</p>
      </div>
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.amazon.com/dp/B093T3B5Z8&psig=AOvVaw2nXxvVj8g9RvOTnMlF5ggJ&ust=1692889483641000" alt="Custom Diary">
        <h3>Custom Anime Diary</h3>
        <p class="price">600 TK</p>
      </div>
      <!-- Add more items as needed -->
    </div>
  </section>

  <section id="keychains-goods">
    <h2>Keychains & Goods</h2>
    <div class="grid">
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.amiami.com/eng/detail/?gcode=CH_KEYCHAIN&ref=home" alt="Anime Keychain">
        <h3>Attack on Titan Keychain</h3>
        <p class="price">150 TK</p>
      </div>
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.narutoshop.com/kunai-replica" alt="Kunai Replica">
        <h3>Naruto Kunai</h3>
        <p class="price">800 TK</p>
      </div>
      <!-- Add more items as needed -->
    </div>
  </section>

  <section id="kimono">
    <h2>Kimonos</h2>
    <div class="grid">
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.narutoshop.com/nezuko-kimono" alt="Demon Slayer Kimono">
        <h3>Nezuko Kimono</h3>
        <p class="price">1200 TK</p>
      </div>
      <!-- Add more kimonos -->
    </div>
  </section>

  <section id="outfits">
    <h2>Anime Character Outfits</h2>
    <div class="grid">
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.jujutsukaisenmerch.com/gojo-outfit" alt="Jujutsu Kaisen Outfit">
        <h3>Gojo Outfit</h3>
        <p class="price">1500 TK</p>
      </div>
      <!-- Add more outfits -->
    </div>
  </section>

  <section id="figures">
    <h2>Anime Figures</h2>
    <div class="grid">
      <div class="card">
        <img src="https://www.google.com/url?sa=i&url=https://www.amiami.com/eng/detail/?gcode=FIGURE-035132" alt="Naruto Figure">
        <h3>Naruto Figure</h3>
        <p class="price">1200 TK</p>
      </div>
      <!-- Add more figures -->
    </div>
  </section>

  <section id="offers">
    <h2>Special Offers</h2>
    <div class="grid">
      <div class="card">🚚 Free Shipping on orders above 2000 TK</div>
      <div class="card">🎉 10% Off on First Purchase (Code: OTAKU10)</div>
      <div class="card">💳 Secure Payments – Bkash / Nagad / Card</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>📞 Phone: 01781855999</p>
    <p>✉ Email: suptrendora@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Trendora. All Rights Reserved.</p>
  </footer>
</body>
</html>
