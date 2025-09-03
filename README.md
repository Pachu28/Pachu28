<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <title>Tu Nombre — Portafolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Portafolio de Tu Nombre: proyectos, habilidades y contacto.">
  <meta property="og:title" content="Tu Nombre — Portafolio">
  <meta property="og:description" content="Proyectos, habilidades y contacto.">
  <meta property="og:type" content="website">
  <link rel="icon" href="data:,">
  <style>
    :root{
      --bg:#0b0d10;
      --card:#12161b;
      --muted:#9aa5b1;
      --text:#e6edf3;
      --brand:#4f8cff;
      --accent:#22c55e;
      --border:#1f2630;
      --shadow: 0 10px 30px rgba(0,0,0,.35);
      --radius:22px;
      --gap:18px;
      --max:1100px;
    }
    @media (prefers-color-scheme: light){
      :root{ --bg:#f7f8fb; --card:#fff; --text:#0b1220; --border:#e7eaf0; --shadow: 0 8px 24px rgba(0,0,0,.08); }
    }
    *{box-sizing:border-box}
    html,body{margin:0}
    body{
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      background:linear-gradient(180deg, var(--bg), #0b0d1000 60%), var(--bg);
      color:var(--text);
      line-height:1.6;
    }
    a{color:var(--brand); text-decoration:none}
    a:hover{text-decoration:underline}
    .wrap{max-width:var(--max); margin:0 auto; padding:24px}
    header{
      display:flex; align-items:center; justify-content:space-between; gap:var(--gap);
      padding:10px 0 24px 0;
    }
    .brand{display:flex; align-items:center; gap:14px}
    .avatar{
      width:56px; height:56px; border-radius:50%; border:1px solid var(--border); box-shadow:var(--shadow);
      background:#999 center/cover no-repeat;
    }
    nav a{margin-left:16px; font-weight:600}
    .hero{
      display:grid; grid-template-columns: 1.2fr .8fr; gap:28px; align-items:center;
    }
    .title{font-size:clamp(28px, 5vw, 44px); line-height:1.15; margin:6px 0}
    .subtitle{color:var(--muted); font-size:clamp(14px, 2.5vw, 18px)}
    .cta{display:flex; gap:12px; margin-top:18px}
    .btn{
      display:inline-block; padding:12px 18px; border-radius:999px; font-weight:700; border:1px solid var(--border);
      background:var(--brand); color:white; box-shadow:var(--shadow);
    }
    .btn.secondary{background:transparent; color:var(--text)}
    .card{
      background:var(--card); border:1px solid var(--border); border-radius:var(--radius); box-shadow:var(--shadow);
      padding:22px;
    }
    section{margin:40px 0}
    h2{font-size:24px; margin:0 0 14px 0}
    .grid{display:grid; gap:var(--gap)}
    .skills{grid-template-columns: repeat(auto-fit, minmax(160px, 1fr))}
    .pill{
      display:inline-flex; align-items:center; gap:8px; border:1px solid var(--border); padding:8px 12px; border-radius:999px; font-weight:600;
      background:rgba(255,255,255,.02)
    }
    .projects{grid-template-columns: repeat(auto-fill, minmax(260px, 1fr))}
    .project h3{margin:0 0 8px 0; font-size:18px}
    .project p{margin:0 0 10px 0; color:var(--muted)}
    .meta{font-size:13px; color:var(--muted)}
    .about p{margin:0}
    footer{padding:24px 0; border-top:1px dashed var(--border); color:var(--muted); font-size:14px}
    .badge{display:inline-block; font-size:12px; padding:4px 10px; border-radius:999px; border:1px solid var(--border); margin-left:8px}
    .hero-illus{min-height:220px; border-radius:var(--radius); border:1px dashed var(--border)}
    .sr-only{position:absolute; width:1px; height:1px; padding:0; margin:-1px; overflow:hidden; clip:rect(0,0,0,0); white-space:nowrap; border:0}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="avatar" style="background-image:url('https://avatars.githubusercontent.com/u/1?v=4');" aria-hidden="true"></div>
        <div>
          <div style="font-weight:800; font-size:18px;">Tu Nombre</div>
          <div class="meta">@tu-usuario <span class="badge">Disponible para proyectos</span></div>
        </div>
      </div>
      <nav aria-label="Navegación principal">
        <a href="#proyectos">Proyectos</a>
        <a href="#habilidades">Habilidades</a>
        <a href="#sobre-mi">Sobre mí</a>
        <a href="#contacto">Contacto</a>
      </nav>
    </header>

    <main class="grid hero">
      <div>
        <p class="meta">Desarrollador Web • VB.NET • SQL Server</p>
        <h1 class="title">Construyo soluciones limpias y funcionales en <span style="color:var(--brand)">HTML/CSS/JS</span> y <span style="color:var(--accent)">.NET</span></h1>
        <p class="subtitle">Me enfoco en interfaces claras, datos bien modelados y despliegues simples con GitHub Pages.</p>
        <div class="cta">
          <a class="btn" href="https://github.com/tu-usuario" target="_blank" rel="noopener">Ver GitHub</a>
          <a class="btn secondary" href="#contacto">Contactar</a>
        </div>
      </div>
      <div class="hero-illus card" aria-hidden="true"></div>
    </main>

    <section id="proyectos">
      <h2>Proyectos</h2>
      <div class="grid projects">
        <article class="card project">
          <h3><a href="https://github.com/tu-usuario/proyecto1" target="_blank" rel="noopener">Proyecto 1</a></h3>
          <p>Sistema de ventas con roles y permisos (VB.NET + SQL Server), enfoque en jerarquías y DataGridViews.</p>
          <div class="meta">VB.NET · SQL Server · WinForms</div>
        </article>
        <article class="card project">
          <h3><a href="https://github.com/tu-usuario/proyecto2" target="_blank" rel="noopener">Proyecto 2</a></h3>
          <p>Portafolio estático accesible con HTML puro, sin dependencias. Despliegue en GitHub Pages.</p>
          <div class="meta">HTML · CSS · Accesibilidad</div>
        </article>
        <article class="card project">
          <h3><a href="https://github.com/tu-usuario/proyecto3" target="_blank" rel="noopener">Proyecto 3</a></h3>
          <p>API y dashboard para reportes. Buenas prácticas de consultas y normalización básica.</p>
          <div class="meta">.NET · SQL · Dashboard</div>
        </article>
      </div>
    </section>

    <section id="habilidades">
      <h2>Habilidades</h2>
      <div class="grid skills">
        <div class="card">
          <strong>Frontend</strong><br>
          <span class="pill">HTML5</span>
          <span class="pill">CSS3</span>
          <span class="pill">JavaScript</span>
        </div>
        <div class="card">
          <strong>Backend</strong><br>
          <span class="pill">VB.NET</span>
          <span class="pill">.NET</span>
          <span class="pill">REST</span>
        </div>
        <div class="card">
          <strong>Datos</strong><br>
          <span class="pill">SQL Server</span>
          <span class="pill">Transacciones</span>
          <span class="pill">Índices</span>
        </div>
        <div class="card">
          <strong>Herramientas</strong><br>
          <span class="pill">Git</span>
          <span class="pill">GitHub</span>
          <span class="pill">GitHub Pages</span>
        </div>
      </div>
    </section>

    <section id="sobre-mi">
      <h2>Sobre mí</h2>
      <div class="card about">
        <p>Me apasiona crear interfaces limpias y sistemas estables. Trabajo con VB.NET y SQL Server para escritorio, y con HTML/CSS/JS para web. Busco mejorar continuamente en arquitectura, rendimiento y UX.</p>
      </div>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <div class="card">
        <p class="sr-only">Formas de contacto</p>
        <p>📧 <a href="mailto:tu-email@ejemplo.com">tu-email@ejemplo.com</a></p>
        <p>🔗 <a href="https://www.linkedin.com/in/tu-usuario/" target="_blank" rel="noopener">LinkedIn</a> · <a href="https://github.com/tu-usuario" target="_blank" rel="noopener">GitHub</a></p>
      </div>
    </section>

    <footer>
      © <span id="year"></span> Tu Nombre — Hecho con HTML puro y GitHub Pages
    </footer>
  </div>
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
