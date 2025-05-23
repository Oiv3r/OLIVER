<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Vida y Logros de Lamine Yamal y Natanael Cano</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #1d1d1d;
      color: white;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      font-size: 1.8em;
      margin: 0;
    }

    nav {
      background-color: #333;
      overflow: hidden;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
    }

    nav a {
      color: white;
      padding: 10px;
      text-decoration: none;
      font-size: 1em;
    }

    nav a:hover {
      background-color: #575757;
    }

    .menu-icon {
      display: none;
      font-size: 24px;
      color: white;
      cursor: pointer;
    }

    .menu-links {
      display: flex;
      gap: 15px;
    }

    .menu-links.mobile {
      display: none;
      flex-direction: column;
      padding-top: 10px;
    }

    section {
      background: white;
      margin: 20px auto;
      max-width: 800px;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0, 0, 0, 0.1);
    }

    h2 {
      border-bottom: 2px solid #222;
      padding-bottom: 5px;
    }

    p {
      line-height: 1.6;
      font-size: 1em;
    }

    .photo {
      max-width: 100%;
      border-radius: 8px;
      margin-top: 10px;
    }

    .highlight {
      font-weight: bold;
      color: #0056b3;
    }

    blockquote {
      font-style: italic;
      color: #555;
      margin: 15px 0;
      padding-left: 15px;
      border-left: 4px solid #aaa;
    }

    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      margin-top: 15px;
    }

    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }

    .social-links {
      margin-top: 15px;
    }

    .social-links a {
      display: inline-block;
      margin-right: 10px;
      color: #333;
      text-decoration: none;
      font-size: 1.2em;
    }

    .social-links a:hover {
      color: #0077cc;
    }

    footer {
      text-align: center;
      padding: 15px 0;
      font-size: 0.9em;
      color: #666;
      background-color: #eaeaea;
    }

    @media (max-width: 768px) {
      .menu-links {
        display: none;
      }

      .menu-icon {
        display: block;
      }

      .menu-links.mobile.active {
        display: flex;
      }

      header h1 {
        font-size: 1.4em;
      }

      nav {
        flex-direction: column;
        align-items: flex-start;
      }

      section {
        margin: 10px;
        padding: 15px;
      }

      p {
        font-size: 0.95em;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Vida y Logros de Lamine Yamal y Natanael Cano</h1>
  </header>

  <nav>
    <div class="menu-icon" onclick="toggleMenu()">☰</div>
    <div class="menu-links" id="menuDesktop">
      <a href="#lamine-yamal">Lamine Yamal</a>
      <a href="#natanael-cano">Natanael Cano</a>
    </div>
    <div class="menu-links mobile" id="menuMobile">
      <a href="#lamine-yamal">Lamine Yamal</a>
      <a href="#natanael-cano">Natanael Cano</a>
    </div>
  </nav>

  <section id="lamine-yamal">
    <h2>Lamine Yamal</h2>
    <p>Lamine Yamal es un joven futbolista español, considerado una de las promesas más brillantes del fútbol mundial. Nacido en 2007, comenzó su carrera en las categorías juveniles del FC Barcelona y ha destacado por su técnica, velocidad y habilidad para crear oportunidades en el campo.</p>
    <p>Entre sus logros más destacados se encuentra su debut en el primer equipo del FC Barcelona a una edad muy temprana, convirtiéndose en uno de los jugadores más jóvenes en lograrlo.</p>
    <p class="highlight">Canción icónica: "¿Y Qué Fue?"</p>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/16nZ6K7sim4" title="Y QUE FUE? - Don Miguelo" frameborder="0" allowfullscreen></iframe>
    </div>
    <img src="https://th.bing.com/th/id/OIP.3QlstcREQg0DCEYylCtytQHaD_?w=319&h=180&c=7&r=0&o=5&pid=1.7" alt="Lamine Yamal" class="photo" />
    <div class="social-links">
      <a href="https://instagram.com/lamineyamal" target="_blank">📷 Instagram</a>
      <a href="https://twitter.com/lamineyamal" target="_blank">🐦 Twitter</a>
    </div>
  </section>

  <section id="natanael-cano">
    <h2>Natanael Cano</h2>
    <p>Natanael Cano es un cantante y compositor mexicano, pionero del género conocido como "corridos tumbados". Nacido en 2001, Cano fusiona la música tradicional mexicana con influencias urbanas como el trap y el hip-hop.</p>
    <p>Ha ganado popularidad internacional gracias a sus éxitos y colaboraciones con artistas reconocidos, y es conocido por revolucionar la música regional mexicana, conectando con nuevas generaciones.</p>
    <p class="highlight">Canción icónica: "Amor Tumbado"</p>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/ehIm7sCUAVg" title="Natanael Cano - Amor Tumbado" frameborder="0" allowfullscreen></iframe>
    </div>
    <blockquote>
      Que nos fuimos de casa persiguiendo un sueño<br>
      cuando nadie nos miraba tan arriba,<br>
      tenemos los sueños y metas<br>
      que nadie en el mundo vería.
    </blockquote>
    <img src="https://th.bing.com/th/id/OIP.zFtQRiWo6PPV4J0q6-g5fQHaEK?w=333&h=187&c=7&r=0&o=5&pid=1.7" alt="Natanael Cano" class="photo" />
    <div class="social-links">
      <a href="https://instagram.com/natanael_cano" target="_blank">📷 Instagram</a>
      <a href="https://twitter.com/natanaelc" target="_blank">🐦 Twitter</a>
      <a href="https://youtube.com/@NatanaelCano" target="_blank">▶️ YouTube</a>
    </div>
  </section>

  <footer>
    &copy; OLIVER   IG: oliverperez_sm
  </footer>

  <script>
    function toggleMenu() {
      const mobileMenu = document.getElementById("menuMobile");
      mobileMenu.classList.toggle("active");
    }
  </script>

</body>
</html>
