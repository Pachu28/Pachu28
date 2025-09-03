<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title><<<Tu Nombre>>> / <<<tuUsuario>>></title>
  <link rel="preconnect" href="https://cdn.jsdelivr.net" />
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.15.1/devicon.min.css">
  <style>
    :root{
      --bg:#0d1117; --text:#e6edf3; --muted:#9da2a8; --card:#0f141b; --line:#222831;
      --brand:#58a6ff; --radius:14px; --shadow:0 10px 30px rgba(0,0,0,.35);
    }
    *{box-sizing:border-box}
    body{margin:0; font-family:Inter,system-ui,Segoe UI,Roboto,Arial,sans-serif; background:var(--bg); color:var(--text)}
    .wrap{max-width:1050px; margin:0 auto; padding:28px 20px}
    .title{font-size:clamp(28px,6vw,48px); font-weight:800; margin:8px 0 4px}
    .sub{color:var(--muted); margin:0 0 16px}
    .bar{height:1px; background:var(--line); margin:22px 0}
    .row{display:flex; flex-wrap:wrap; gap:10px}
    .pill{
      display:inline-flex; align-items:center; gap:8px; padding:10px 14px; border-radius:999px;
      background:#111827; border:1px solid var(--line); text-decoration:none; color:var(--text); font-weight:700
    }
    .pill:hover{outline:2px solid var(--brand)}
    section{margin:26px 0}
    h2{margin:0 0 12px; font-size:22px}
    .card{background:var(--card); border:1px solid var(--line); border-radius:var(--radius); padding:18px; box-shadow:var(--shadow)}
    ul{list-style:none; padding:0; margin:0}
    li{display:flex; gap:10px; align-items:flex-start; padding:8px 0; border-bottom:1px dashed var(--line)}
    li:last-child{border-bottom:0}
    .tech{display:grid; grid-template-columns:repeat(auto-fit,minmax(80px,1fr)); gap:12px}
    .tech .t{display:flex; flex-direction:column; align-items:center; gap:8px; padding:14px; background:#111827; border:1px solid var(--line); border-radius:12px}
    .tech i{font-size:30px}
    .projects{display:grid; grid-template-columns:repeat(auto-fit,minmax(260px,1fr)); gap:14px}
    .project h3{margin:0 0 6px; font-size:18px}
    .project p{margin:0; color:var(--muted)}
    footer{color:var(--muted); font-size:14px; text-align:center; padding:20px 0}
    .badge{display:inline-block; padding:4px 10px; border:1px solid var(--line); border-radius:999px; font-size:12px; margin-left:8px}
    .hint{color:var(--muted); font-size:13px}
    .emoji{filter:grayscale(.1)}
    @media (max-width:640px){ .social .pill{width:100%; justify-content:center} }
  </style>
</head>
<body>
  <div class="wrap">
    <!-- Encabezado -->
    <header>
      <div class="title">Hola <span class="emoji">👋</span> soy <strong><<<Tu Nombre>>></strong> / <<<tuUsuario>>></div>
      <p class="sub">Desarrollador • Frontend • Backend • Estudiante de Gestión Financiera</p>
      <div class="row social">
        <a class="pill" href="<<<https://youtube.com/@tuCanal>>>" target="_blank" rel="noopener">YouTube</a>
        <a class="pill" href="<<<https://www.tiktok.com/@tuUsuario>>>" target="_blank" rel="noopener">TikTok</a>
        <a class="pill" href="<<<https://www.linkedin.com/in/tuUsuario>>>" target="_blank" rel="noopener">LinkedIn</a>
        <a class="pill" href="<<<https://facebook.com/tuUsuario>>>" target="_blank" rel="noopener">Facebook</a>
        <a class="pill" href="mailto:<<<tuemail@dominio.com>>>">Gmail</a>
      </div>
      <div class="bar"></div>
    </header>

    <!-- Sobre mí -->
    <section>
      <h2>Sobre mí <span class="emoji">🙂</span></h2>
      <div class="card">
        <ul>
          <li><span>🎓</span><span><strong>INGENIERO/ESTUDIANTE EN INFORMÁTICA</strong> con enfoque en productos simples y mantenibles.</span></li>
          <li><span>📢</span><span>Pequeño <strong>creador de contenido</strong> que comparte lo que aprende con base en estudio y experiencia.</span></li>
          <li><span>💻</span><span><strong>+<<<años>>> años</strong> construyendo software (de escritorio con VB.NET + SQL Server y web con HTML/CSS/JS).</span></li>
          <li><span>🧩</span><span>He asumido roles de <em>desarrollador</em>, <em>líder</em> y <em>emprendedor</em>. Me interesan arquitectura simple y UX clara.</span></li>
          <li><span>✉️</span><span>Contacto directo: <a href="mailto:<<<tuemail@dominio.com>>>"><<<tuemail@dominio.com>>></a></span></li>
        </ul>
      </div>
    </section>

    <!-- Tecnologías -->
    <section>
      <h2>Tecnologías conocidas <span class="emoji">🧠</span></h2>
      <div class="tech">
        <div class="t"><i class="devicon-html5-plain colored"></i><span>HTML5</span></div>
        <div class="t"><i class="devicon-css3-plain colored"></i><span>CSS3</span></div>
        <div class="t"><i class="devicon-javascript-plain colored"></i><span>JavaScript</span></div>
        <div class="t"><i class="devicon-dot-net-plain colored"></i><span>.NET</span></div>
        <div class="t"><i class="devicon-vbnet-plain"></i><span>VB.NET</span></div>
        <div class="t"><i class="devicon-microsoftsqlserver-plain colored"></i><span>SQL Server</span></div>
        <div class="t"><i class="devicon-git-plain colored"></i><span>Git</span></div>
        <div class="t"><i class="devicon-github-original"></i><span>GitHub</span></div>
        <!-- Agrega más: <div class="t"><i class="devicon-php-plain colored"></i><span>PHP</span></div> -->
      </div>
      <p class="hint">Usa <a href="https://github.com/devicons/devicon" target="_blank" rel="noopener">Devicon</a> para añadir más logos (solo agrega el <code>&lt;i class="devicon-...&gt;</code>).</p>
    </section>

    <!-- Proyectos -->
    <section>
      <h2>Proyectos <span class="emoji">🚀</span></h2>
      <div class="projects">
        <article class="card project">
          <h3><a href="<<<https://github.com/tuUsuario/sistema-ventas>>>" target="_blank" rel="noopener">Sistema de Ventas</a> <span class="badge">VB.NET + SQL Server</span></h3>
          <p>Roles y permisos jerárquicos, DataGridViews, manejo de NCF y transacciones con rollback.</p>
        </article>
        <article class="card project">
          <h3><a href="<<<https://github.com/tuUsuario/portafolio-html>>>" target="_blank" rel="noopener">Portafolio HTML</a> <span class="badge">HTML/CSS</span></h3>
          <p>Landing accesible y ligera desplegada en GitHub Pages.</p>
        </article>
        <article class="card project">
          <h3><a href="<<<https://github.com/tuUsuario/reportes-dashboard>>>" target="_blank" rel="noopener">Dashboard de Reportes</a> <span class="badge">.NET + SQL</span></h3>
          <p>Consultas optimizadas e índices básicos para informes rápidos.</p>
        </article>
      </div>
    </section>

    <!-- Contacto -->
    <section>
      <h2>Contacto <span class="emoji">📬</span></h2>
      <div class="card">
        <div class="row">
          <a class="pill" href="mailto:<<<tuemail@dominio.com>>>">Email</a>
          <a class="pill" href="<<<https://www.linkedin.com/in/tuUsuario>>>">LinkedIn</a>
          <a class="pill" href="<<<https://github.com/tuUsuario>>>">GitHub</a>
          <a class="pill" href="<<<https://t.me/tuUsuario>>>">Telegram</a>
        </div>
      </div>
    </section>

    <footer>© <span id="y"></span> <<<Tu Nombre>>> — Portafolio</footer>
  </div>
  <script>document.getElementById('y').textContent=new Date().getFullYear();</script>
</body>
</html>
