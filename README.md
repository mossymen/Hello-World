<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Burna Boy Fan Page</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #111;
      color: #fff;
    }
    header {
      background: #e50914;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .hero {
      background: url('https://upload.wikimedia.org/wikipedia/commons/d/d0/Burna_Boy_2021.jpg') no-repeat center/cover;
      height: 400px;
      position: relative;
    }
    .hero::after {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0,0,0,0.6);
    }
    .hero-text {
      position: absolute;
      bottom: 20px;
      left: 20px;
      z-index: 1;
    }
    .hero-text h2 {
      font-size: 2rem;
      margin: 0;
    }
    .content {
      padding: 20px;
    }
    .section {
      margin-bottom: 40px;
    }
    .section h3 {
      color: #e50914;
    }
    .gallery img {
      width: 100%;
      max-width: 300px;
      border-radius: 8px;
      margin: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      font-size: 0.9rem;
    }
    @media (min-width: 768px) {
      .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
    }
    .payment-box {
      background: #222;
      border-radius: 10px;
      padding: 20px;
      max-width: 500px;
      margin: 0 auto;
      text-align: center;
    }
    .payment-box p {
      font-size: 1.1rem;
      margin-bottom: 10px;
    }
    .cash-tag {
      font-size: 1.5rem;
      font-weight: bold;
      color: #0f0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Burna Boy Fan Page</h1>
  </header>
  <div class="hero">
    <div class="hero-text">
      <h2>The African Giant</h2>
    </div>
  </div>
  <div class="content">
    <div class="section">
      <h3>About Burna Boy</h3>
      <p>Burna Boy, born Damini Ebunoluwa Ogulu, is a Grammy Award-winning Nigerian singer, songwriter, and performer known for hits like "Last Last," "Ye," and "Gbona." His Afro-fusion style blends Afrobeat, dancehall, reggae, and pop.</p>
    </div>
    <div class="section gallery">
      <h3>Gallery</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/66/Burna_Boy_-_Global_Citizen_Festival_South_Africa_2018_%2845743064112%29.jpg" alt="Burna Boy on stage" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/Burna_Boy_Interview_2019.png" alt="Burna Boy interview" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Burna_Boy_-_Ziggo_Dome_-_2023.jpg" alt="Live concert" />
    </div>
    <div class="section">
      <h3>Top Songs</h3>
      <ul>
        <li>Last Last</li>
        <li>Ye</li>
        <li>Anybody</li>
        <li>On the Low</li>
        <li>City Boys</li>
      </ul>
    </div>
    <div class="section">
      <h3>Follow on Social Media</h3>
      <p>
        <a href="https://instagram.com/burnaboygram" target="_blank" style="color: #e50914;">Instagram</a> | 
        <a href="https://twitter.com/burnaboy" target="_blank" style="color: #e50914;">Twitter</a> | 
        <a href="https://youtube.com/user/BurnaBoyVEVO" target="_blank" style="color: #e50914;">YouTube</a>
      </p>
    </div>
    <div class="section">
      <h3>Support the Fan Page</h3>
      <div class="payment-box">
        <p>If you love Burna Boy and this fan page, support us with a tip via Cash App!</p>
        <p class="cash-tag">$BurnaSupport</p>
        <p>Thank you for your generosity! ❤️</p>
      </div>
    </div>
  </div>
  <footer>
    <p>Made with ❤️ by Gerard Butler.</p>
  </footer>
</body>
</html>
