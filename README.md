<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Aryanfifa – FC Mobile Gamer</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: #f0f0f0;
    }
    header {
      background: linear-gradient(90deg, #00ff88, #9146FF);
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 0 20px;
    }
    .about {
      text-align: center;
    }
    .about img {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 15px;
      border: 3px solid #00ff88;
    }
    .socials {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
    }
    .socials a {
      color: #f0f0f0;
      text-decoration: none;
      font-size: 1.2rem;
      background-color: #222;
      padding: 10px 20px;
      border-radius: 8px;
      transition: background-color 0.3s ease;
    }
    .socials a:hover {
      background-color: #00ff88;
      color: #000;
    }
    .videos {
      margin-top: 40px;
    }
    .videos h2 {
      text-align: center;
      margin-bottom: 20px;
    }
    .video-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .video {
      background-color: #1f1f1f;
      padding: 10px;
      border-radius: 10px;
      text-align: center;
    }
    .video img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      background-color: #1a1a1a;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Aryanfifa</h1>
  <p>FC Mobile Gamer | Livestreams & Highlights</p>
</header>

<div class="container">
  <section class="about">
    <img src="https://via.placeholder.com/150" alt="Profilbild">
    <p>Hey! Ich bin Aryanfifa – leidenschaftlicher FC Mobile Gamer.  
    Ich streame regelmäßig live auf <strong>Twitch</strong> und teile meine besten Highlights auf <strong>YouTube</strong>.</p>
  </section>

  <section class="socials">
    <a href="https://twitch.tv/DEIN_USERNAME" target="_blank">🔴 Twitch</a>
    <a href="https://youtube.com/@DEIN_KANAL" target="_blank">▶️ YouTube</a>
    <a href="mailto:deine@email.de">📧 Kontakt</a>
  </section>

  <section class="videos">
    <h2>Letzte Highlights</h2>
    <div class="video-grid">
      <div class="video">
        <img src="https://via.placeholder.com/300x170.png?text=Highlight+1" alt="Highlight 1">
        <p>⚽ Krasser Sieg in der Weekend League!</p>
      </div>
      <div class="video">
        <img src="https://via.placeholder.com/300x170.png?text=Highlight+2" alt="Highlight 2">
        <p>🔥 Pack Opening mit Mega-Luck</p>
      </div>
    </div>
  </section>
</div>

<footer>
  &copy; 2025 Aryanfifa – Alle Rechte vorbehalten.
</footer>

</body>
</html>
