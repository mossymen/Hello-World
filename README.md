<!DOCTYPE html><html lang="en">
<head>
  /gerard-butler-fanpage
├── index.html ✅
├── style.css (if any)
├── images/ (if any)
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gerard Butler Fan Page</title>
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
      background: url('https://upload.wikimedia.org/wikipedia/commons/e/e3/Gerard_Butler_2016.jpg') no-repeat center/cover;
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
    .cards {
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-width: 800px;
      margin: 0 auto;
    }
    .card {
      background: #1e1e1e;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      border: 2px solid #e50914;
    }
    .card h4 {
      margin: 0 0 10px;
      color: gold;
    }
    .card.silver h4 {
      color: silver;
    }
    .card.bronze h4 {
      color: #cd7f32;
    }
    .card a {
      display: inline-block;
      margin-top: 10px;
      background: #e50914;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>Gerard Butler Fan Page</h1>
  </header>
  <div class="hero">
    <div class="hero-text">
      <h2>The Spartan Legend</h2>
    </div>
  </div>
  <div class="content">
    <div class="section">
      <h3>About Gerard Butler</h3>
      <p>Gerard Butler is a Scottish actor and film producer known for his powerful performances in action films and dramas. He rose to global fame with his role as King Leonidas in "300" and has starred in hits like "Olympus Has Fallen," "Law Abiding Citizen," and "P.S. I Love You."</p>
    </div>
    <div class="section gallery">
      <h3>Gallery</h3>
      <img src="https://upload.wikimedia.org/wikipedia/commons/e/e3/Gerard_Butler_2016.jpg" alt="Gerard Butler" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/b/b0/Gerard_Butler_in_2019.jpg" alt="Gerard Butler 2019" />
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/7f/Gerard_Butler_2013.jpg" alt="Gerard Butler event" />
    </div>
    <div class="section">
      <h3>Top Movies</h3>
      <ul>
        <li>300</li>
        <li>Olympus Has Fallen</li>
        <li>P.S. I Love You</li>
        <li>Law Abiding Citizen</li>
        <li>London Has Fallen</li>
      </ul>
    </div>
    <div class="section">
      <h3>Follow on Social Media</h3>
      <p>
        <a href="https://www.instagram.com/gerardbutler/" target="_blank" style="color: #e50914;">Instagram</a> | 
        <a href="https://twitter.com/GerardButler" target="_blank" style="color: #e50914;">Twitter</a> | 
        <a href="https://www.youtube.com/results?search_query=gerard+butler+interview" target="_blank" style="color: #e50914;">YouTube</a>
      </p>
    </div>
    <div class="section">
      <h3>Support the Page</h3>
      <div class="payment-box">
        <p>If you love Gerard Butler and this page, support us with a tip via Cash App!</p>
        <p class="cash-tag">$GerardSupport</p>
        <p>Thank you for your generosity! ❤️</p>
      </div>
    </div>
    <div class="section">
      <h3>Meet & Greet Passes</h3>
      <div class="cards">
        <div class="card gold">
          <h4>Gold Card</h4>
          <p>VIP Meet & Greet + Signed Merchandise</p>
          <a href="https://cash.app/$GerardGold" target="_blank">Pay $200</a>
        </div>
        <div class="card silver">
          <h4>Silver Card</h4>
          <p>Standard Meet & Greet + Photo Opportunity</p>
          <a href="https://cash.app/$GerardSilver" target="_blank">Pay $150</a>
        </div>
        <div class="card bronze">
          <h4>Bronze Card</h4>
          <p>Access to Fan Q&A Session</p>
          <a href="https://cash.app/$GerardBronze" target="_blank">Pay $100</a>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <p>Made with ❤️ by Gerard Butler</p>
  </footer>
</body>
</html>
