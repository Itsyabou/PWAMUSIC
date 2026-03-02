


<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PWA MUSIC</title>

<style>
@keyframes glitch {
  0% { text-shadow: 2px 2px red; }
  20% { text-shadow: -2px -2px blue; }
  40% { text-shadow: 2px -2px purple; }
  60% { text-shadow: -2px 2px crimson; }
  80% { text-shadow: 2px 2px red; }
  100% { text-shadow: none; }
}

@keyframes flicker {
  0% { opacity: 1; }
  5% { opacity: 0.4; }
  10% { opacity: 1; }
  15% { opacity: 0.3; }
  20% { opacity: 1; }
  100% { opacity: 1; }
}

body {
  margin: 0;
  background: black;
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  overflow-x: hidden;
}

header {
  position: fixed;
  width: 100%;
  padding: 25px 50px;
  background: rgba(0,0,0,0.95);
  display: flex;
  justify-content: space-between;
  align-items: center;
  z-index: 999;
  border-bottom: 1px solid #111;
}

header h1 {
  letter-spacing: 6px;
  font-size: 22px;
  animation: glitch 1.5s infinite;
}

nav a {
  color: white;
  text-decoration: none;
  margin-left: 30px;
  font-size: 14px;
  letter-spacing: 3px;
  transition: 0.3s;
}

nav a:hover {
  color: crimson;
}

.hero {
  height: 100vh;
  background: url('https://i.pinimg.com/736x/7f/2b/7e/7f2b7edb83b78dfd52b70e89c4c6b8a6.jpg') center/cover no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero h2 {
  font-size: 110px;
  letter-spacing: 10px;
  animation: glitch 1.2s infinite;
}

.hero p {
  font-size: 16px;
  letter-spacing: 4px;
  animation: flicker 3s infinite;
}

section {
  padding: 120px 60px;
  text-align: center;
  border-top: 1px solid #111;
}

img {
  width: 85%;
  max-width: 900px;
  margin: 50px auto;
  display: block;
  filter: grayscale(100%) contrast(120%);
  transition: 0.5s;
}

img:hover {
  filter: grayscale(0%) contrast(140%);
  transform: scale(1.03);
}

.button {
  display: inline-block;
  margin-top: 40px;
  padding: 18px 50px;
  border: 1px solid white;
  color: white;
  text-decoration: none;
  letter-spacing: 4px;
  transition: 0.4s;
}

.button:hover {
  background: crimson;
  border-color: crimson;
  transform: scale(1.05);
}

.countdown {
  font-size: 40px;
  letter-spacing: 6px;
  margin-top: 30px;
  animation: flicker 4s infinite;
}

footer {
  padding: 50px;
  text-align: center;
  font-size: 12px;
  letter-spacing: 3px;
  border-top: 1px solid #111;
}
</style>
</head>

<body>

<header>
  <h1>PWA MUSIC</h1>
  <nav>
    <a href="#music">MUSIC</a>
    <a href="#tour">TOUR</a>
    <a href="#merch">MERCH</a>
    <a href="#contact">CONTACT</a>
  </nav>
</header>

<div class="hero">
  <h2>PWA 18 COMING SOON FUCK NIGGA</h2>
  <p>UNDERGROUND. DARK. UNSTOPPABLE.</p>
</div>

<section id="music">
  <h2>STREAM THE DARKNESS</h2>
  <img src="https://i.pinimg.com/736x/3c/75/7a/3c757a95e3a1f5dc4cfa0d89dce9e17b.jpg">
  <a class="button" href="https://soundcloud.com/pwa-318612296" target="_blank">
    ENTER SOUNDCLOUD
  </a>
</section>

<section id="tour">
  <h2>2026 WORLD TAKEOVER</h2>
  <img src="https://i.pinimg.com/736x/1a/54/aa/1a54aa0ad9d2d3c4bdbb1f0b9fd7b9f6.jpg">
  <div class="countdown">TOUR DATES DROPPING SOON</div>
  <a class="button" href="#">GET NOTIFIED</a>
</section>

<section id="merch">
  <h2>LIMITED MERCH</h2>
  <img src="https://i.pinimg.com/736x/55/21/4f/55214fbd5f45dbbdc18f98b9f96a8baf.jpg">
  <p>Distorted graphics. Heavyweight fabric. No restocks.</p>
  <a class="button" href="#">COMING SOON</a>
</section>

<section id="contact">
  <h2>BOOKINGS / FEATURES</h2>
  <p>pwabusiness@protonmail.com</p>
</section>

<footer>
  © 2026 PWA MUSIC — BUILT FOR THE UNDERGROUND
</footer>

</body>
</html>
