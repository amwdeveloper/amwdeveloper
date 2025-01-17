<!DOCTYPE html>
<html lang="pt-br">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio GitHub - André Junior de Souza</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #141e30, #243b55);
      color: #fff;
      text-align: center;
    }

    .header-image {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-bottom: 20px;
    }

    .btn-custom {
      margin: 5px;
    }

    .technologies {
      display: flex;
      justify-content: center;
      gap: 10px;
      flex-wrap: wrap;
      margin-top: 20px;
    }

    .technologies img {
      width: 60px;
      height: 60px;
      border-radius: 5px;
    }

    .stats {
      margin-top: 40px;
    }

    .footer {
      margin-top: 40px;
      padding: 20px 0;
      background: #101d2c;
    }
  </style>
</head>

<body>
  <header>
    <img src="https://64.media.tumblr.com/75ee871c3c70501014511f527b342213/74bb6bc1ad2987d5-a1/s1280x1920/ae89e529ec10b97daff14c6aa3db56e663fbe416.gif" alt="Header" class="header-image">
    <h1>Olá! 👋 Eu sou o André Junior de Souza 🖐️</h1>
    <p>Desenvolvedor apaixonado por tecnologia, sempre buscando criar soluções criativas e eficientes.</p>

    <div>
      <a href="https://amwdeveloper.com.br" target="_blank" class="btn btn-primary btn-custom">🌐 Meu Blog</a>
      <a href="https://youtube.com/c/amwdeveloper" target="_blank" class="btn btn-danger btn-custom">🎥 YouTube</a>
      <a href="https://instagram.com/amwdeveloper" target="_blank" class="btn btn-warning btn-custom">📸 Instagram</a>
    </div>
  </header>

  <main>
    <section class="technologies">
      <h2>Tecnologias que uso</h2>
      <div>
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
        <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white" alt="Vue.js">
        <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white" alt="jQuery">
        <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
      </div>
    </section>

    <section class="stats">
      <h2>Estatísticas do GitHub</h2>
      <div class="row">
        <div class="col-md-6">
          <img src="https://github-readme-stats.vercel.app/api?username=amwdeveloper&show_icons=true&locale=pt-br&theme=tokyonight" alt="Estatísticas de GitHub">
        </div>
        <div class="col-md-6">
          <img src="https://github-readme-stats.vercel.app/api/top-langs?username=amwdeveloper&show_icons=true&locale=pt-br&layout=compact&theme=tokyonight" alt="Linguagens Mais Usadas">
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <p>Feito com ❤️ por André Junior de Souza</p>
    <p>📫 <a href="mailto:contato@amwdeveloper.com.br" style="color: #fff;">contato@amwdeveloper.com.br</a></p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>

</html>
