<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <title>Tu Nombre — Portafolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #0d1117;
      color: #e6edf3;
      line-height: 1.6;
    }
    header {
      text-align: center;
      padding: 50px 20px 20px;
    }
    header h1 {
      font-size: 2.5em;
      margin: 0;
    }
    header p {
      margin: 10px 0;
      color: #8b949e;
      font-weight: bold;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
    }
    h2 {
      color: #58a6ff;
      border-bottom: 2px solid #30363d;
      padding-bottom: 5px;
    }
    .skills, .contact, .projects, .languages {
      display: grid;
      gap: 15px;
    }
    .skills div, .languages span, .projects div, .contact div {
      background: #161b22;
      padding: 15px;
      border-radius: 8px;
    }
    .languages {
      grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    }
    .languages span {
      text-align: center;
      font-weight: bold;
      border: 1px solid #30363d;
    }
    .projects h3 {
      margin: 0 0 5px;
    }
    a {
      color: #58a6ff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #8b949e;
      border-top: 1px solid #30363d;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tu Nombre</h1>
    <p>Desarrollador • Frontend • Backend • Estudiante de Gestión Financiera</p>
  </header>

  <section id="lenguajes">
    <h2>Lenguajes</h2>
    <div class="languages">
      <span>HTML</span>
      <span>CSS</span>
      <span>JavaScript</span>
      <span>VB.NET</span>
      <span>SQL Server</span>
      <!-- Agrega más lenguajes aquí -->
    </div>
  </section>

  <section id="sobre-mi">
    <h2>Sobre mí</h2>
    <div class="skills">
      <div>
        Soy un desarrollador apasionado por crear soluciones limpias y escalables, con experiencia en sistemas de escritorio (VB.NET + SQL Server) y desarrollo web (HTML, CSS, JS). Además, estoy cursando estudios en Gestión Financiera, lo que me permite integrar la tecnología con el mundo de los negocios.
      </div>
    </div>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <div class="contact">
      <div>📧 Email: <a href="mailto:tu-email@ejemplo.com">tu-email@ejemplo.com</a></div>
      <div>💼 LinkedIn: <a href="https://www.linkedin.com/in/tu-usuario/" target="_blank">linkedin.com/in/tu-usuario</a></div>
      <div>🐙 GitHub: <a href="https://github.com/tu-usuario" target="_blank">github.com/tu-usuario</a></div>
    </div>
  </section>

  <section id="proyectos">
    <h2>Proyectos</h2>
    <div class="projects">
      <div>
        <h3><a href="https://github.com/tu-usuario/proyecto1" target="_blank">Proyecto 1</a></h3>
        <p>Sistema de ventas con roles y permisos (VB.NET + SQL Server).</p>
      </div>
      <div>
        <h3><a href="https://github.com/tu-usuario/proyecto2" target="_blank">Proyecto 2</a></h3>
        <p>Portafolio personal con HTML y CSS desplegado en GitHub Pages.</p>
      </div>
      <div>
        <h3><a href="https://github.com/tu-usuario/proyecto3" target="_blank">Proyecto 3</a></h3>
        <p>Dashboard de reportes conectado a base de datos SQL Server.</p>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> Tu Nombre — Portafolio Profesional
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
