<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>MyStick | Portfolio</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <link rel="stylesheet" href="style.css">
  
</head>
<body>
  <header>
  <img src="mystick.jpg" alt="MyStick's Photo" class="profile-pic">
    <h1 class="fade-slide">Welcome to Fagbamila Glory's World</h1>
    <p class="fade-slide delay">Upciming Afrobeat & Rap Artist | Student | Front End Developer</p>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hey there! I'm MyStick, a rising Afrobeat & rap artist, student, and digital creator. I make music, create content, and build brands with confidence.</p>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <ul>
      <li>🎵 Released Single: "Vibes Only"</li>
      <li>🎮 TikTok Growth Series</li>
      <li>👟 Bata – Custom Leather Slippers</li>
    </ul>
  </section>

  <section id="socials">
    <h2>Follow Me</h2>
   <a href="https://tiktok.com/@blue_jacketguy" class="social-link" target="_blank"><i class="fab fa-tiktok"></i> TikTok</a>
    <a href="https://istagram.com/@simply_oluremi" class="social-link" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>|
    <a href="mailto:gloryfagbamila@gmail.com" class="social-link" target="_blank"><i class="fab fa-mail"></i> Email</a>|
  </section>

  <section id="contact">
    <h2>Contact Form</h2>
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message"></textarea><br><br>

      <button type="submit">Send</button>

  <section id="music-player">
  <h3>🎶 Now Playing: <span id="trackTitle">Samad_-_Lammeda.mp3</span></h3>
  <audio id="bgMusic" src="SAMAD_-_Lameda.mp3" type="audio/mpeg"></audio>
  
  <div id="controls">
    <button id="playBtn">▶ Play</button>
    <button id="pauseBtn">⏸ Pause</button>
  </div>

  <div id="progressContainer">
    <div id="progressBar"></div>
  </div>
</section>
    </form>
  </section>

  <footer>
    <p>© 2025 MyStick. All rights reserved.</p>
  </footer>
<!-- Music Player -->
<div class="music-player">
  <button id="playPauseBtn">▶ Play Music</button>
  <input type="range" id="progressBar" value="0" min="0" step="1">
  <audio id="bgMusic" src="SAMAD_-_Lameda.mp3" preload="auto"></audio>
</div>
<script src="script.js" defer></script>
</body>
</html>
