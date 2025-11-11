 <!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Romantic Universe 💘</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap');

    :root {
      --accent: #ff4081;
      --bg1: #fff0f7;
      --bg2: #f8bbd0;
      --text: #4a1c2b;
      --shadow: 0 8px 22px rgba(236,64,122,0.25);
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, var(--bg1), var(--bg2));
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      overflow-x: hidden;
    }

    .container {
      width: 95%;
      max-width: 1150px;
      text-align: center;
      padding-bottom: 50px;
    }

    h1 {
      color: var(--accent);
      font-size: 2rem;
      margin-bottom: 8px;
    }

    p {
      color: var(--text);
      opacity: 0.8;
      margin-bottom: 40px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      width: 160px;
      height: 200px;
      background: white;
      border-radius: 20px;
      box-shadow: var(--shadow);
      cursor: pointer;
      transition: all 0.3s ease;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      user-select: none;
      position: relative;
      overflow: hidden;
    }

    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 12px 30px rgba(236,64,122,0.35);
    }

    .icon {
      font-size: 2.5rem;
      margin-bottom: 12px;
    }

    .title {
      font-weight: 600;
      color: var(--accent);
      font-size: 1.1rem;
    }

    .subtitle {
      font-size: 0.8rem;
      opacity: 0.7;
      color: var(--text);
      padding: 0 10px;
    }

    .options {
      position: absolute;
      inset: 0;
      background: rgba(255,255,255,0.96);
      display: none;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 10px;
      border-radius: 20px;
      z-index: 5;
    }

    .option {
      background: var(--bg1);
      border-radius: 12px;
      padding: 10px 15px;
      width: 130px;
      text-align: center;
      cursor: pointer;
      transition: 0.25s;
      box-shadow: var(--shadow);
    }

    .option:hover {
      background: var(--accent);
      color: white;
      transform: scale(1.05);
    }

    .back {
      position: absolute;
      bottom: 10px;
      font-size: 0.8rem;
      color: var(--accent);
      cursor: pointer;
      text-decoration: underline;
    }

    .heart {
      position: fixed;
      font-size: 1.8rem;
      color: #ff80ab;
      opacity: 0.5;
      animation: float 8s infinite ease-in-out;
    }

    @keyframes float {
      0% { transform: translateY(0); opacity: 0.5; }
      50% { transform: translateY(-50px); opacity: 0.9; }
      100% { transform: translateY(0); opacity: 0.5; }
    }
  </style>
</head>
<body>

<div class="container">
  <h1>💞 Choose Your Connection 💞</h1>
  <p>Every card leads to something beautiful — click and explore 💐</p>

  <div class="cards">
    <!-- WhatsApp -->
    <div class="card main" data-link="https://wa.me/9068685074?text=Hey%20there!%20💖">
      <div class="icon">💬</div>
      <div class="title">WhatsApp</div>
      <div class="subtitle">Stay close, one message away 💌</div>
      <div class="options">
        <div class="option" data-link="https://wa.me/9068685074?text=Let's%20be%20friends%20💖">Let's be friends 💖</div>
        <div class="option" data-link="https://wa.me/9068685074?text=Text%20me%20maybe%20🌷">Text me maybe 🌷</div>
        <div class="option" data-link="https://wa.me/9068685074?text=Keep%20in%20touch%20💫">Keep in touch 💫</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Instagram -->
    <div class="card main" data-link="https://instagram.com/nikhil_.bindal29">
      <div class="icon">📸</div>
      <div class="title">Instagram</div>
      <div class="subtitle">Double-tap your way to my heart 💕</div>
      <div class="options">
        <div class="option" data-link="https://instagram.com/nikhil_.bindal29">Follow my heart 💞</div>
        <div class="option" data-link="https://instagram.com/nikhil_.bindal29">Double-tap forever 💘</div>
        <div class="option" data-link="https://instagram.com/nikhil_.bindal29">Let's share smiles 📷</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Call -->
    <div class="card main" data-link="tel:+919068685074">
      <div class="icon">📞</div>
      <div class="title">Call</div>
      <div class="subtitle">Because your voice is my favorite sound 🎶</div>
      <div class="options">
        <div class="option" data-link="tel:+919068685074">Late night talks 🌙</div>
        <div class="option" data-link="tel:+919068685074">Morning wishes ☀️</div>
        <div class="option" data-link="tel:+919068685074">Surprise call 💕</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Love Note -->
    <div class="card main" data-link="https://poemuseum.org/poems/">
      <div class="icon">💌</div>
      <div class="title">Love Note</div>
      <div class="subtitle">Whispers from the heart ✨</div>
      <div class="options">
        <div class="option" data-link="https://poets.org/love-poems">You make me smile 💋</div>
        <div class="option" data-link="https://www.goodreads.com/quotes/tag/love">You're my favorite chapter 📖</div>
        <div class="option" data-link="https://poemuseum.org/poems/">Forever us 💫</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Music -->
    <div class="card main" data-link="https://open.spotify.com/track/7BKLCZ1jbUBVqRi2FVlTVw">
      <div class="icon">🎶</div>
      <div class="title">Music</div>
      <div class="subtitle">The soundtrack of our hearts 💗</div>
      <div class="options">
        <div class="option" data-link="https://open.spotify.com/track/7BKLCZ1jbUBVqRi2FVlTVw">Love on Replay 💕</div>
        <div class="option" data-link="https://open.spotify.com/track/2VxeLyX666F8uXCJ0dZF8B">Heartbeats Sync 💓</div>
        <div class="option" data-link="https://open.spotify.com/track/3YJJjQPAbDT7mGpX3WtQ9A">Melody of Us 🎧</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

        <!-- Coffee -->
    <div class="card main" data-link="https://www.starbucks.com">
      <div class="icon">☕</div>
      <div class="title">Coffee Date</div>
      <div class="subtitle">Two cups. One vibe. Endless talks 🥰</div>
      <div class="options">
        <div class="option" data-link="https://www.coffeebean.com">Morning brew ☀️</div>
        <div class="option" data-link="https://www.starbucks.com">Evening chill 🌙</div>
        <div class="option" data-link="https://www.timhortons.ca">Café romance 💕</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Dinner -->
    <div class="card main" data-link="https://www.opentable.com/">
      <div class="icon">🍷</div>
      <div class="title">Dinner Date</div>
      <div class="subtitle">Candlelight & conversation 💞</div>
      <div class="options">
        <div class="option" data-link="https://www.opentable.com/">Candlelight dinner 💐</div>
        <div class="option" data-link="https://www.yelp.com">Romantic restaurant 💖</div>
        <div class="option" data-link="https://www.foodnetwork.com">Cooking together 🍽️</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Stargazing -->
    <div class="card main" data-link="https://www.nasa.gov/">
      <div class="icon">🌌</div>
      <div class="title">Stargazing</div>
      <div class="subtitle">Under the same sky, always 🌠</div>
      <div class="options">
        <div class="option" data-link="https://stellarium-web.org/">Moonlit night 🌙</div>
        <div class="option" data-link="https://www.nasa.gov/">Count the stars 💫</div>
        <div class="option" data-link="https://skyandtelescope.org/">Our constellation 💖</div>
        <div class="back">↩ Back</div>
      </div>
    </div>

    <!-- Surprise Gift -->
    <div class="card main" data-link="https://www.amazon.in/gifts">
      <div class="icon">🎁</div>
      <div class="title">Surprise Gift</div>
      <div class="subtitle">Because you deserve smiles 🌷</div>
      <div class="options">
        <div class="option" data-link="https://www.amazon.in/gifts">Tiny surprise 🎀</div>
        <div class="option" data-link="https://www.flowers.com/">Bouquet of love 💐</div>
        <div class="option" data-link="https://www.cadburygiftsdirect.co.uk/">Sweet treat 🍫</div>
        <div class="back">↩ Back</div>
      </div>
    </div>
  </div>
</div>

<!-- Floating hearts -->
<div class="heart" style="top:30px;left:20px;">💖</div>
<div class="heart" style="top:150px;right:60px;">💘</div>
<div class="heart" style="bottom:40px;left:120px;">❤️</div>

<script>
  const cards = document.querySelectorAll('.card.main');

  cards.forEach(card => {
    const optionsPanel = card.querySelector('.options');
    const options = card.querySelectorAll('.option');
    const back = card.querySelector('.back');

    // Step 1: Click card → show sub-options (no link open yet)
    card.addEventListener('click', e => {
      if (e.target.classList.contains('option') || e.target.classList.contains('back')) return;

      // Show options only
      optionsPanel.style.display = 'flex';
    });

    // Step 2: Click sub-option → open link
    options.forEach(option => {
      option.addEventListener('click', e => {
        e.stopPropagation();
        const link = option.dataset.link;
        if (link) window.open(link, '_blank');
        optionsPanel.style.display = 'none';
      });
    });

    // Step 3: Click "Back" → close options
    back.addEventListener('click', e => {
      e.stopPropagation();
      optionsPanel.style.display = 'none';
    });
  });
</script>

</body>
</html>

