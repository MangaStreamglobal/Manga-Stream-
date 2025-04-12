# Manga-Stream-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MangaStream — Anime Anytime, Anywhere</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #111;
      color: #fff;
    }

    header {
      background-color: #ff7f00;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      font-size: 28px;
      color: white;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 25px;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #222;
    }

    .hero {
      background: url('https://wallpapercave.com/wp/wp8262871.jpg') center/cover no-repeat;
      height: 70vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-left: 60px;
      background-blend-mode: multiply;
      background-color: rgba(0, 0, 0, 0.6);
    }

    .hero h2 {
      font-size: 48px;
      color: #fff;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      color: #ddd;
      max-width: 600px;
    }

    .section-title {
      font-size: 26px;
      padding: 30px 40px 10px;
      color: #ff7f00;
    }

    .anime-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
      gap: 20px;
      padding: 20px 40px;
    }

    .anime-card {
      background-color: #1c1c1c;
      border-radius: 8px;
      overflow: hidden;
      transition: transform 0.3s;
      cursor: pointer;
    }

    .anime-card:hover {
      transform: scale(1.05);
    }

    .anime-card img {
      width: 100%;
      height: 260px;
      object-fit: cover;
    }

    .anime-card h4 {
      padding: 10px;
      text-align: center;
      font-size: 16px;
      color: #fff;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #222;
      color: #aaa;
      margin-top: 30px;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 32px;
      }
      .hero {
        padding-left: 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>MangaStream</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Anime</a>
      <a href="#">Manga</a>
      <a href="#">Login</a>
      <a href="#">Pricing</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Watch the Latest Anime Episodes in HD</h2>
    <p>Stream your favorite anime anytime, anywhere. No ads, no lag — just pure entertainment.</p>
  </section>

  <h3 class="section-title">Trending Anime</h3>
  <section class="anime-grid">
    <div class="anime-card">
      <img src="https://cdn.myanimelist.net/images/anime/10/47347.jpg" alt="Naruto">
      <h4>Naruto: Shippuden</h4>
    </div>
    <div class="anime-card">
      <img src="https://cdn.myanimelist.net/images/anime/1910/135431.jpg" alt="Demon Slayer">
      <h4>Demon Slayer</h4>
    </div>
    <div class="anime-card">
      <img src="https://cdn.myanimelist.net/images/anime/1208/94745.jpg" alt="Attack on Titan">
      <h4>Attack on Titan</h4>
    </div>
    <div class="anime-card">
      <img src="https://cdn.myanimelist.net/images/anime/1988/121835.jpg" alt="Jujutsu Kaisen">
      <h4>Jujutsu Kaisen</h4>
    </div>
  </section>

  <footer>
    © 2025 MangaStream. Designed with love for anime fans.
  </footer>

</body>
</html>
