<html lang="es" dir="ltr">
<head>
  <!-- ======= Meta básicas ======= -->
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />

  <title data-i18n="seo.title">Melvin Garita — Estrategia, Excelencia Organizacional e IA para banca</title>
  <meta name="description" content="Estrategia, Excelencia Organizacional, Analítica e Inteligencia Artificial aplicada a la banca. Más de 20 años liderando ejecución estratégica, transformación, eficiencia operativa y analítica avanzada." data-i18n-attr="content:seo.description" />
  <meta name="robots" content="index,follow,max-image-preview:large" />
  <link rel="canonical" href="https://melvingarita.github.io/"/>

  <!-- PWA / color del navegador -->
  <meta name="theme-color" content="#0a1a36" media="(prefers-color-scheme: light)">
  <meta name="theme-color" content="#060914" media="(prefers-color-scheme: dark)">

  <!-- ======= Open Graph / Twitter ======= -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="Melvin Garita">
  <meta property="og:title" content="Estrategia, Excelencia Organizacional e IA para banca" data-i18n-attr="content:og.title">
  <meta property="og:description" content="Transformación, eficiencia y analítica avanzada con resultados medibles." data-i18n-attr="content:og.description">
  <meta property="og:url" content="https://melvingarita.github.io/">
  <meta property="og:image" content="https://melvingarita.github.io/mg.jpg">
  <meta property="og:image:alt" content="Portada del sitio de Melvin Garita" data-i18n-attr="content:og.imageAlt">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Estrategia, Excelencia Organizacional e IA para banca" data-i18n-attr="content:twitter.title">
  <meta name="twitter:description" content="Transformación, eficiencia y analítica avanzada con resultados medibles." data-i18n-attr="content:twitter.description">
  <meta name="twitter:image" content="https://melvingarita.github.io/mg.jpg">

  <!-- ======= Fuentes (performance) ======= -->
  <link rel="preconnect" href="https://fonts.googleapis.com" crossorigin>
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800;900&family=Plus+Jakarta+Sans:wght@700;800&display=swap" rel="stylesheet">

  <!-- ======= Favicon ======= -->
  <link rel="icon" href="/favicon.ico">
  <link rel="icon" href="/icon.svg" type="image/svg+xml">
  <link rel="apple-touch-icon" href="/apple-touch-icon.png">

  <style>
    :root{
      --bg: #f7f8fb; --text: #111827; --muted:#4b5563;
      --brand:#15b588; --brand-600:#0e8f6b; --accent:#0ea5e9; --warning:#b45309;
      --card:#ffffff; --line: rgba(15,23,42,.08); --shadow: 0 10px 30px rgba(2,6,23,.10);
      --radius-xl:18px; --radius-lg:14px; --radius-md:12px; --container:1120px; --focus:0 0 0 3px rgba(14,165,233,.45);
    }
    @media (prefers-color-scheme: dark){
      :root{ --bg:#060914; --text:#e5e7eb; --muted:#9ca3af; --card:#0f1524; --line: rgba(255,255,255,.08); --shadow:0 10px 30px rgba(0,0,0,.35) }
    }
    *{ box-sizing:border-box }
    html:focus-within{ scroll-behavior:smooth }
    body{ margin:0; background:var(--bg); color:var(--text); font-family:Inter, system-ui, -apple-system, Segoe UI, Roboto, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol", sans-serif; line-height:1.55; text-rendering:optimizeLegibility }
    a{ color:inherit; }
    :focus-visible{ outline:none; box-shadow:var(--focus); border-radius:10px }
    @media (prefers-reduced-motion: reduce){ *{ animation:none!important; transition:none!important; scroll-behavior:auto!important } }
    .container{ width:min(100% - 32px, var(--container)); margin-inline:auto }
    header.site-header{ padding-top:10px }
    .topnav{ display:flex; align-items:center; justify-content:space-between; gap:12px; margin-bottom:10px }
    .brand{ font-weight:800; letter-spacing:.03em; font-family:"Plus Jakarta Sans", Inter, system-ui, sans-serif }
    .mainnav ul{ list-style:none; padding:0; margin:0; display:flex; gap:16px }
    .mainnav a{ text-decoration:none; font-weight:600; color:#334155; padding:8px 10px; border-radius:10px }
    .mainnav a[aria-current="page"]{ background:rgba(14,165,233,.12); color:#0a5d8a }
    @media (prefers-color-scheme: dark){ .mainnav a{ color:#cbd5e1 } .mainnav a[aria-current="page"]{ background:rgba(14,165,233,.18); color:#a7e3ff } }
    .skip-link{ position:absolute; left:-9999px; top:auto; width:1px; height:1px; overflow:hidden }
    .skip-link:focus-visible{ left:12px; top:12px; width:auto; height:auto; z-index:9999; background:#111827; color:#fff; padding:10px 14px; border-radius:10px }

    .hero{
      margin-top:16px; border-radius:var(--radius-xl); padding:28px 24px 26px;
      box-shadow:var(--shadow); position:relative; overflow:hidden; color:#eaf2ff;
      background:
        radial-gradient(900px 500px at 75% -10%, rgba(14,165,233,.25), rgba(14,165,233,0) 60%),
        radial-gradient(900px 500px at 10% 10%, rgba(21,181,136,.22), rgba(21,181,136,0) 55%),
        linear-gradient(135deg, #0c1732 0%, #081327 35%, #0a1a36 100%);
    }
    .brand-chip{ display:inline-flex; align-items:center; gap:10px; background:rgba(255,255,255,.08); color:#b7e9d9; border:1px solid rgba(255,255,255,.12); padding:6px 14px; border-radius:999px; font-weight:700; font-size:12.5px; letter-spacing:.3px; text-transform:uppercase; backdrop-filter:blur(6px) }
    .hero h1{ margin:14px 0 10px; font-family:"Plus Jakarta Sans", Inter, system-ui, sans-serif; font-weight:800; line-height:1.05; letter-spacing:-.02em; font-size:clamp(28px,4.4vw,48px); color:#fff }
    .hero p{ margin:0 0 18px; color:#d9e4ff; max-width:72ch; font-size:clamp(14px,2vw,18px) }
    .hero-actions{ display:flex; flex-wrap:wrap; gap:12px }
    .btn{ --_bg:#0f172a; --_fg:#e5eefb; --_bd:rgba(255,255,255,.14); display:inline-flex; align-items:center; gap:10px; padding:12px 16px; border-radius:12px; border:1px solid var(--_bd); background:var(--_bg); color:var(--_fg); text-decoration:none; font-weight:700; transition:transform .08s ease, background .25s ease, border-color .25s ease, color .25s ease }
    .btn:active{ transform:translateY(1px) scale(.99) }
    .btn-primary{ --_bg:var(--brand); --_bd:transparent; --_fg:#062e24; color:#062e24 }
    .btn-primary:hover{ background:var(--brand-600); color:#eafff8 }
    .btn-ghost{ background:rgba(2,6,23,.4) }
    .btn-ghost:hover{ background:rgba(2,6,23,.55) }
    .btn .ico{ width:18px; height:18px; display:inline-block }
    section{ margin-top:28px }
    .section-title{ font-size:14px; letter-spacing:.18em; text-transform:uppercase; color:#6b7280; margin-bottom:14px; font-weight:800 }
    @media (prefers-color-scheme: dark){ .section-title{ color:#9aa4b2 } }
    .grid{ display:grid; gap:14px; grid-template-columns:1fr }
    @media (min-width:720px){ .grid{ grid-template-columns:repeat(3,1fr) } }
    .card{ background:var(--card); border-radius:var(--radius-lg); padding:18px; box-shadow:var(--shadow); border:1px solid var(--line) }
    .card .eyebrow{ display:inline-flex; align-items:center; gap:8px; color:#64748b; font-weight:700; font-size:13px; margin-bottom:8px }
    .card h3{ margin:0 0 6px; font-size:22px; line-height:1.15; letter-spacing:-.01em }
    .card h3 .muted{ color:#6b7280; font-weight:800 }
    @media (prefers-color-scheme: dark){ .card h3 .muted{ color:#a3a7b0 } }
    .card p{ margin:0; color:var(--muted) }
    .badge{ width:26px; height:26px; border-radius:8px; display:inline-grid; place-items:center; background:#eff6ff; color:#1d4ed8; border:1px solid var(--line) }
    .badge.badge-green{ background:#e9fbf5; color:#0f766e }
    .badge.badge-amber{ background:#fff7ed; color:var(--warning) }
    .chips{ display:flex; flex-wrap:wrap; gap:10px }
    .chip{ display:inline-flex; align-items:center; gap:8px; background:#fff; color:#0f172a; padding:10px 12px; border-radius:999px; border:1px solid var(--line); box-shadow:var(--shadow); font-weight:700; font-size:14px }
    @media (prefers-color-scheme: dark){ .chip{ background:#0f1524; color:#e5e7eb } }
    .chip .dot{ width:10px; height:10px; border-radius:999px; background:var(--accent); box-shadow:0 0 0 4px rgba(14,165,233,.15) }
    footer{ color:#6b7280; font-size:14px; padding:28px 0 40px; text-align:center }
  </style>
</head>
<body>
  <!-- Skip link -->
  <a class="skip-link" href="#contenido" data-i18n="a11y.skip">Saltar al contenido</a>

  <!-- ======= Header / Nav ======= -->
  <header class="site-header" role="banner">
    <div class="container topnav">
      <strong class="brand">Melvin Garita</strong>
      <nav class="mainnav" aria-label="Navegación principal">
        <ul role="list">
          <li><a href="https://melvingarita.github.io/home" data-i18n="nav.home">Inicio</a></li>
          <li><a href="https://melvingarita.github.io/logros" data-i18n="nav.achievements">Logros</a></li>
          <li><a href="https://melvingarita.github.io/enfoque" aria-current="page" data-i18n="nav.approach">Enfoque</a></li>
          <li><a href="https://www.linkedin.com/in/melvingarita" data-i18n="nav.contact">Contacto</a></li>
        </ul>
      </nav>
    </div>

    <!-- HERO -->
    <div class="container hero" aria-labelledby="titulo-hero" aria-describedby="desc-hero">

      <h1 id="titulo-hero" data-i18n="hero.title">
        Estrategia, Excelencia Organizacional, Analítica e Inteligencia Artificial<br/>aplicada a la banca
      </h1>
      <p id="desc-hero" data-i18n="hero.lead">
        Ejecutivo con más de veinte años liderando ejecución estratégica, transformación organizacional,
        eficiencia operativa y analítica avanzada en instituciones financieras. Impulso iniciativas de digitalización,
        automatización e IA que reducen costos, escalan capacidades y elevan la calidad del servicio con métricas claras.
      </p>

      <div class="hero-actions" role="group" aria-label="Acciones principales">
        <a class="btn btn-primary" href="https://melvingarita.github.io/cv" target="_blank" rel="noopener" data-i18n="cta.cv">
          Ver Curriculum Vitae
        </a>

        <a class="btn btn-ghost" href="https://www.linkedin.com/in/melvingarita" target="_blank" rel="noopener me" data-i18n="cta.linkedin">
          Conectemos en LinkedIn
        </a>

        <button class="btn btn-ghost" type="button" id="langToggle"
                aria-pressed="false"
                aria-label="Cambiar idioma a inglés"
                data-i18n-attr="aria-label:cta.lang.aria"
                data-i18n="cta.lang.label">
          English Version
        </button>
      </div>
    </div>
  </header>

  <!-- ======= Main ======= -->
  <main id="contenido" class="container" role="main">
    <!-- LOGROS DESTACADOS -->
    <section aria-labelledby="logros">
      <h2 class="section-title" id="logros" data-i18n="sections.achievements">LOGROS DESTACADOS</h2>
      <ul class="grid" role="list">
        <li>
          <article class="card" aria-labelledby="card1-title" aria-describedby="card1-desc">
            <div class="eyebrow">
              <span class="badge" aria-hidden="true">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M12 6v12m6-6H6" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>
              </span>
              <span data-i18n="cards.strategy.eyebrow">Estrategia</span>
            </div>
            <h3 id="card1-title"><span data-i18n="cards.strategy.title">Estrategia</span> <span class="muted" data-i18n="cards.strategy.title2">Empresarial</span></h3>
            <p id="card1-desc" data-i18n="cards.strategy.body">Revisión de modelos de negocio y KPIs; adopción de marcos ágiles a nivel empresarial.</p>
          </article>
        </li>

        <li>
          <article class="card" aria-labelledby="card2-title" aria-describedby="card2-desc">
            <div class="eyebrow">
              <span class="badge badge-green" aria-hidden="true">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="M4 13c4 0 4-6 8-6s4 12 8 12" stroke="currentColor" stroke-width="2" stroke-linecap="round"/></svg>
              </span>
              <span data-i18n="cards.optimization.eyebrow">Optimización</span>
            </div>
            <h3 id="card2-title"><span data-i18n="cards.optimization.title">Optimización de costos</span> <span class="muted" data-i18n="cards.optimization.title2">financieros y operativos</span></h3>
            <p id="card2-desc" data-i18n="cards.optimization.body">Implementación de soluciones de IA en servicio al cliente, elevando eficiencia y calidad.</p>
          </article>
        </li>

        <li>
          <article class="card" aria-labelledby="card3-title" aria-describedby="card3-desc">
            <div class="eyebrow">
              <span class="badge badge-amber" aria-hidden="true">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none"><path d="m12 17 5.196 3.09-1.381-5.927L20.39 9.91l-6.045-.51L12 3.9 9.655 9.4l-6.046.51 4.575 4.253-1.381 5.927L12 17Z" stroke="currentColor" stroke-width="1.6" stroke-linejoin="round"/></svg>
              </span>
              <span data-i18n="cards.excellence.eyebrow">Excelencia</span>
            </div>
            <h3 id="card3-title"><span data-i18n="cards.excellence.title">Excelencia</span> <span class="muted" data-i18n="cards.excellence.title2">Organizacional</span></h3>
            <p id="card3-desc" data-i18n="cards.excellence.body">Premio Nacional a la Excelencia (2020) y reconocimientos internacionales en ejecución estratégica.</p>
          </article>
        </li>
      </ul>
    </section>

    <!-- MI ENFOQUE -->
    <section aria-labelledby="enfoque">
      <h2 class="section-title" id="enfoque" data-i18n="sections.approach">MI ENFOQUE</h2>
      <div class="chips" role="list" aria-describedby="enfoque">
        <span class="chip" role="listitem"><span class="dot" aria-hidden="true"></span> <span data-i18n="chips.metrics">Transformación con métricas</span></span>
        <span class="chip" role="listitem"><span class="dot" aria-hidden="true" style="background:#22c55e; box-shadow:0 0 0 4px rgba(34,197,94,.15)"></span> <span data-i18n="chips.tech">Tecnología con propósito</span></span>
        <span class="chip" role="listitem"><span class="dot" aria-hidden="true" style="background:#f59e0b; box-shadow:0 0 0 4px rgba(245,158,11,.15)"></span> <span data-i18n="chips.people">Liderazgo que desarrolla personas</span></span>
      </div>
    </section>

    <!-- CONTACTO -->
    <section aria-labelledby="contacto" id="contacto">
      <h2 class="section-title" data-i18n="sections.contact">CONTACTO</h2>
      <p>
        <span data-i18n="contact.text">¿Conversamos?</span>
        <a href="https://www.linkedin.com/in/melvingarita" target="_blank" rel="noopener me" data-i18n="contact.linkedin">LinkedIn</a>
        · <a href="mailto:melvin.garita@gmail.com" data-i18n="contact.email">Contáctame </a>
      </p>
    </section>
  </main>

  <!-- ======= Footer ======= -->
  <footer class="container" role="contentinfo">
    © <span id="year"></span> Melvin Garita — <span data-i18n="footer.keywords">Estrategia | Excelencia Organizacional | Analítica/IA</span>
  </footer>

  <!-- ======= JSON-LD (Person) ======= -->
  <script type="application/ld+json" id="jsonld-person">
  {
    "@context":"https://schema.org",
    "@type":"Person",
    "name":"Melvin Garita",
    "jobTitle":"Ejecutivo de Estrategia y Excelencia Organizacional",
    "description":"Estrategia, Excelencia Organizacional, Analítica e Inteligencia Artificial aplicada a la banca.",
    "url":"https://melvingarita.github.io/",
    "sameAs":["https://www.linkedin.com/in/melvingarita"]
  }
  </script>

  <!-- ======= I18N: Diccionario y Aplicador ======= -->
  <script>
    // Año dinámico
    document.getElementById('year').textContent = new Date().getFullYear();

    // ---- Diccionario completo (extiéndelo si agregas más contenido) ----
    const DICT = {
      es: {
        "seo.title": "Melvin Garita — Estrategia, Excelencia Organizacional e IA para banca",
        "seo.description": "Estrategia, Excelencia Organizacional, Analítica e Inteligencia Artificial aplicada a la banca. Más de 20 años liderando ejecución estratégica, transformación, eficiencia operativa y analítica avanzada.",
        "og.title": "Estrategia, Excelencia Organizacional e IA para banca",
        "og.description": "Transformación, eficiencia y analítica avanzada con resultados medibles.",
        "og.imageAlt": "Portada del sitio de Melvin Garita",
        "twitter.title": "Estrategia, Excelencia Organizacional e IA para banca",
        "twitter.description": "Transformación, eficiencia y analítica avanzada con resultados medibles.",

        "a11y.skip": "Saltar al contenido",

        "nav.home": "Inicio",
        "nav.achievements": "Logros",
        "nav.approach": "Enfoque",
        "nav.contact": "Contacto",

        "hero.title": "Estrategia, Excelencia Organizacional, Analítica e Inteligencia Artificial<br/>aplicada a la banca",
        "hero.lead": "Ejecutivo con más de veinte años liderando ejecución estratégica, transformación organizacional, eficiencia operativa y analítica avanzada en instituciones financieras. Impulso iniciativas de digitalización, automatización e IA que reducen costos, escalan capacidades y elevan la calidad del servicio con métricas claras.",

        "cta.cv": "Ver Curriculum Vitae",
        "cta.linkedin": "Conectemos en LinkedIn",
        "cta.lang.label": "English Version",
        "cta.lang.aria": "Cambiar idioma a inglés",

        "sections.achievements": "LOGROS DESTACADOS",
        "sections.approach": "MI ENFOQUE",
        "sections.contact": "CONTACTO",

        "cards.strategy.eyebrow": "Estrategia",
        "cards.strategy.title": "Estrategia",
        "cards.strategy.title2": "Empresarial",
        "cards.strategy.body": "Revisión de modelos de negocio y KPIs; adopción de marcos ágiles a nivel empresarial.",

        "cards.optimization.eyebrow": "Optimización",
        "cards.optimization.title": "Optimización de costos",
        "cards.optimization.title2": "financieros y operativos",
        "cards.optimization.body": "Implementación de soluciones de IA en servicio al cliente, elevando eficiencia y calidad.",

        "cards.excellence.eyebrow": "Excelencia",
        "cards.excellence.title": "Excelencia",
        "cards.excellence.title2": "Organizacional",
        "cards.excellence.body": "Premio Nacional a la Excelencia (2020) y reconocimientos internacionales en ejecución estratégica.",

        "chips.metrics": "Transformación con métricas",
        "chips.tech": "Tecnología con propósito",
        "chips.people": "Liderazgo que desarrolla personas",

        "contact.text": "¿Conversamos?",
        "contact.linkedin": "LinkedIn",
        "contact.email": "Contáctame",

        "footer.keywords": "Estrategia | Excelencia Organizacional | Analítica/IA",

        // JSON-LD (texto cambiante)
        "jsonld.jobTitle": "Ejecutivo de Estrategia y Excelencia Organizacional",
        "jsonld.description": "Estrategia, Excelencia Organizacional, Analítica e Inteligencia Artificial aplicada a la banca."
      },
      en: {
        "seo.title": "Melvin Garita — Strategy, Organizational Excellence & AI for Banking",
        "seo.description": "Strategy, Organizational Excellence, Analytics and Artificial Intelligence for banking. 20+ years leading strategic execution, transformation, operational efficiency and advanced analytics.",
        "og.title": "Strategy, Organizational Excellence & AI for Banking",
        "og.description": "Transformation, efficiency and advanced analytics with measurable outcomes.",
        "og.imageAlt": "Cover image of Melvin Garita's website",
        "twitter.title": "Strategy, Organizational Excellence & AI for Banking",
        "twitter.description": "Transformation, efficiency and advanced analytics with measurable outcomes.",

        "a11y.skip": "Skip to content",

        "nav.home": "Home",
        "nav.achievements": "Achievements",
        "nav.approach": "Approach",
        "nav.contact": "Contact",

        "hero.title": "Strategy, Organizational Excellence, Analytics and Artificial Intelligence for Banking",
        "hero.lead": "Executive leader with 20+ years driving strategic execution, organizational transformation, operational efficiency, and advanced analytics in financial institutions. I lead digitization, automation and AI initiatives that reduce costs, scale capabilities and improve service quality with clear metrics.",

        "cta.cv": "View Resume",
        "cta.linkedin": "Connect on LinkedIn",
        "cta.lang.label": "Versión en español",
        "cta.lang.aria": "Switch language to Spanish",

        "sections.achievements": "HIGHLIGHTED ACHIEVEMENTS",
        "sections.approach": "MY APPROACH",
        "sections.contact": "CONTACT",

        "cards.strategy.eyebrow": "Strategy",
        "cards.strategy.title": "Business Strategy",
        "cards.strategy.title2": "",
        "cards.strategy.body": "Business model & KPI reviews; adoption of agile-at-scale frameworks.",

        "cards.optimization.eyebrow": "Optimization",
        "cards.optimization.title": "Cost Optimization",
        "cards.optimization.title2": "financial & operational",
        "cards.optimization.body": "AI solutions in customer service delivering higher efficiency and quality.",

        "cards.excellence.eyebrow": "Excellence",
        "cards.excellence.title": "Organizational Excellence",
        "cards.excellence.title2": "",
        "cards.excellence.body": "National Excellence Award (2020) and international recognition in strategy execution.",

        "chips.metrics": "Metrics-driven transformation",
        "chips.tech": "Technology with purpose",
        "chips.people": "People-developing leadership",

        "contact.text": "Shall we talk?",
        "contact.linkedin": "LinkedIn",
        "contact.email": "Contact me",

        "footer.keywords": "Strategy | Organizational Excellence | Analytics/AI",

        "jsonld.jobTitle": "Strategy & Organizational Excellence Executive",
        "jsonld.description": "Strategy, Organizational Excellence, Analytics and Artificial Intelligence for banking."
      }
    };

    // ---- Aplicador de traducciones ----
    function applyI18n(lang='es') {
      const dict = DICT[lang];
      if (!dict) return;

      // 1) Textos en elementos
      document.querySelectorAll('[data-i18n]').forEach(el => {
        const key = el.getAttribute('data-i18n');
        if (!key || !(key in dict)) return;
        // Si el texto de destino contiene <br/> u otras etiquetas, usamos innerHTML
        const val = dict[key];
        if (/<[a-z][\s\S]*>/i.test(val)) el.innerHTML = val;
        else el.textContent = val;
      });

      // 2) Atributos (aria-label, placeholder, content, etc.)
      document.querySelectorAll('[data-i18n-attr]').forEach(el => {
        const defs = el.getAttribute('data-i18n-attr').split('|'); // permite múltiples: "aria-label:key|title:key2"
        defs.forEach(def => {
          const [attr, key] = def.split(':');
          if (attr && key && (key in dict)) el.setAttribute(attr.trim(), dict[key].trim());
        });
      });

      // 3) <html lang>
      document.documentElement.setAttribute('lang', lang);

      // 4) <title> y meta description (por si no estaban en data-i18n-attr)
      if (dict['seo.title']) document.title = dict['seo.title'];
      const desc = document.querySelector('meta[name="description"]');
      if (desc && dict['seo.description']) desc.setAttribute('content', dict['seo.description']);

      // 5) Open Graph / Twitter (opcional, ya lo manejamos con data-i18n-attr)
      // 6) JSON-LD (actualiza jobTitle/description)
      const jsonldEl = document.getElementById('jsonld-person');
      if (jsonldEl) {
        try {
          const data = JSON.parse(jsonldEl.textContent);
          if (dict['jsonld.jobTitle']) data.jobTitle = dict['jsonld.jobTitle'];
          if (dict['jsonld.description']) data.description = dict['jsonld.description'];
          jsonldEl.textContent = JSON.stringify(data);
        } catch(e){}
      }
    }

    // Estado y botón
    const langBtn = document.getElementById('langToggle');
    let currentLang = 'es'; // inicia en español

    function toggleLang(){
      currentLang = (currentLang === 'es') ? 'en' : 'es';
      langBtn.setAttribute('aria-pressed', String(currentLang === 'en'));
      applyI18n(currentLang);
    }

    // Inicializa todo en ES
    applyI18n('es');
    langBtn.addEventListener('click', toggleLang);

    // Marca de nav activo (accesible)
    document.querySelectorAll('.mainnav a').forEach(a => {
      a.addEventListener('click', () => {
        document.querySelectorAll('.mainnav a[aria-current="page"]').forEach(el => el.removeAttribute('aria-current'));
        a.setAttribute('aria-current','page');
      });
    });
  </script>
</body>
</html>
