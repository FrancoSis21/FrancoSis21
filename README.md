<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Franco Rojas Luque</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Fira+Code&family=Montserrat:wght@400;700&display=swap"
      rel="stylesheet"
    />
    <style>
      /* Aquí va TODO tu CSS tal como lo pusiste antes */
      body {
        background-color: #000;
        font-family: "Montserrat", sans-serif;
        color: #fff;
        padding: 20px;
      }

      .container {
        max-width: 1000px;
        margin: auto;
        background: rgba(255, 255, 255, 0.03);
        border-radius: 20px;
        padding: 30px;
        box-shadow: 0 0 25px rgba(255, 255, 255, 0.07);
        backdrop-filter: blur(6px);
        position: relative;
        overflow: hidden;
      }

      h2 {
        font-weight: 700;
        text-transform: uppercase;
        letter-spacing: 2px;
        margin-top: 30px;
        border-bottom: 1px solid #ffffff20;
        padding-bottom: 5px;
      }

      h4 {
        margin-top: 20px;
        color: #aad8ff;
        font-family: "Fira Code", monospace;
      }

      ul {
        text-align: left;
        list-style: none;
        padding-left: 0;
      }

      ul li {
        margin: 8px 0;
      }

      .icons img {
        margin: 5px 8px;
        transition: transform 0.3s ease;
      }

      .icons img:hover {
        transform: scale(1.15);
      }

      .top-img {
        text-align: center;
        margin-bottom: 30px;
      }

      .shimarin {
        float: right;
        border-radius: 20px;
        box-shadow: 0 4px 10px rgba(255, 255, 255, 0.1);
        margin-left: 20px;
      }

      .corner-img {
        width: 162px;
        position: absolute;
        right: 25px;
        top: 430px;
        border-radius: 20px;
        box-shadow: 0 4px 15px rgba(255, 255, 255, 0.06);
        opacity: 0;
        animation: fadeInUp 1.2s ease forwards;
      }

      @keyframes fadeInUp {
        0% {
          transform: translateY(40px);
          opacity: 0;
        }
        100% {
          transform: translateY(0px);
          opacity: 1;
        }
      }

      .social {
        text-align: center;
        margin-top: 50px;
      }

      .social a {
        margin: 0 10px;
        display: inline-block;
        transition: transform 0.3s ease, opacity 0.3s ease;
        opacity: 0.8;
      }

      .social a:hover {
        transform: scale(1.2);
        opacity: 1;
      }

      .social img {
        width: 32px;
        height: 32px;
        filter: brightness(0) invert(1);
      }

      .author {
        text-align: center;
        margin-top: 15px;
        font-size: 14px;
        color: #ccc;
      }

      @media (max-width: 768px) {
        .shimarin {
          float: none;
          display: block;
          margin: 0 auto 20px;
        }

        .corner-img {
          position: static;
          display: block;
          margin: 30px auto 0;
        }
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="top-img">
        <img src="https://i.imgur.com/x6qU1kR.png" width="180" alt="Logo" />
      </div>

      <img
        src="https://i.imgur.com/aNBi8Jf.png"
        width="160"
        class="shimarin"
        alt="Shimarin"
      />

      <h2>/ sobre mí /</h2>
      <ul>
        <li>⭐ Actualmente trabajando en <strong>Desarrollo Web</strong></li>
        <li>💀 En su mayoría en <strong>Repositorios Privados</strong></li>
        <li>
          👾 <strong>Estudiante</strong> aprendiendo y explorando nuevas tecnologías
        </li>
      </ul>

      <h2>/ habilidades /</h2>

      <h4>Lenguajes</h4>
      <p class="icons">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" width="40" title="C" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" width="40" title="C++" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" title="Python" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" title="JavaScript" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" width="40" title="PHP" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40" title="Java" />
      </p>

      <h4>Backend</h4>
      <p class="icons">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" width="40" title="Node.js" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/codeigniter/codeigniter-plain.svg" width="40" title="CodeIgniter" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" width="40" title="Express" />
      </p>

      <h4>Frontend</h4>
      <p class="icons">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" title="HTML5" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" title="CSS3" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="40" title="Bootstrap" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" title="React" />
      </p>

      <h4>Bases de Datos</h4>
      <p class="icons">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" width="40" title="MySQL" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" width="40" title="SQLite" />
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" width="40" title="Firebase" />
      </p>

      <img
        class="corner-img"
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT60qJqNgG3Mv0p4gnm1TuRPgO867Y_xgc2iQ&s"
        alt="Decorativo"
      />

      <div class="social">
        <a href="https://facebook.com" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/facebook.svg" alt="Facebook" /></a>
        <a href="https://instagram.com" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/instagram.svg" alt="Instagram" /></a>
        <a href="https://x.com" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/x.svg" alt="X" /></a>
        <a href="https://github.com" target="_blank"><img src="https://cdn.jsdelivr.net/gh/simple-icons/simple-icons/icons/github.svg" alt="GitHub" /></a>
      </div>

      <div class="author">
        Creado por <strong>Franco Rojas Luque</strong> © 2025
      </div>
    </div>
  </body>
</html>
