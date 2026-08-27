<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Harsh Verma — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;500;700;900&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg-grad: linear-gradient(135deg, #e9d7ff 0%, #f3e8ff 40%, #eef2ff 100%);
      --accent-grad: linear-gradient(90deg,#7c3aed 0%,#4f46e5 50%,#06b6d4 100%);
      --purple:#6d28d9;
      --indigo:#4f46e5;
      --muted:#6b7280;
      --glass: rgba(255,255,255,0.85);
      --card-shadow: 0 6px 20px rgba(79,70,229,0.08);
    }
    html,body{height:100%;}
    body{
      margin:0;font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background: radial-gradient(1200px 600px at 10% 10%, rgba(124,58,237,0.08), transparent 10%),
                  radial-gradient(900px 400px at 90% 90%, rgba(79,70,229,0.06), transparent 8%),
                  var(--bg-grad);
      -webkit-font-smoothing:antialiased; -moz-osx-font-smoothing:grayscale;
      color:#0f172a;
      padding:40px 24px;
    }
    /* Navbar */
    .nav-wrap{display:flex;justify-content:center}
    nav{background:var(--glass);backdrop-filter:blur(6px);border-radius:9999px;padding:10px 18px;box-shadow:0 6px 18px rgba(15,23,42,0.06);width:100%;max-width:1100px;display:flex;align-items:center;gap:12px}
    .logo{font-weight:800;color:var(--indigo);letter-spacing:-0.3px}
    .nav-center{display:flex;gap:22px;margin:0 auto;align-items:center}
    .nav-center a{color:#374151;text-decoration:none;font-weight:600;padding:6px 4px;position:relative}
    .nav-center a.active{color:var(--purple)}
    .nav-center a.active::after{content:'';position:absolute;left:0;right:0;height:3px;background:linear-gradient(90deg,#8b5cf6,#4f46e5);bottom:-8px;border-radius:3px}
    .nav-actions{display:flex;align-items:center;gap:12px}
    .btn-contact{padding:8px 14px;border-radius:999px;border:none;color:white;font-weight:700;background:var(--accent-grad);box-shadow:0 8px 20px rgba(79,70,229,0.12)}
    .toggle{width:40px;height:40px;border-radius:50%;background:#111827;color:white;display:grid;place-items:center}

    /* Hero */
    .container{max-width:1100px;margin:44px auto 0;display:grid;grid-template-columns:1fr 420px;gap:40px;align-items:center}
    .left{padding:8px 6px}
    .badge{display:inline-flex;gap:8px;align-items:center;padding:8px 12px;border-radius:999px;background:rgba(124,58,237,0.09);color:var(--purple);font-weight:600;font-size:13px}
    .dot{width:10px;height:10px;border-radius:50%;background:var(--indigo);box-shadow:0 0 8px rgba(99,102,241,0.35)}
    .label{margin-top:14px;font-size:12px;letter-spacing:2px;color:var(--muted);font-weight:700}
    h1{font-size:54px;margin:10px 0 8px;line-height:1;color:transparent;background:linear-gradient(90deg,#6d28d9,#4f46e5);-webkit-background-clip:text;background-clip:text;font-weight:900}
    .subtitle{color:var(--muted);font-weight:600;margin-bottom:14px}
    p.lead{color:#475569;max-width:60ch;line-height:1.6}
    .cta-row{display:flex;gap:12px;margin-top:22px}
    .btn-primary{padding:12px 18px;border-radius:12px;border:none;color:white;font-weight:700;background:var(--accent-grad);box-shadow:0 10px 30px rgba(79,70,229,0.12)}
    .btn-outline{padding:12px 18px;border-radius:12px;border:2px solid rgba(124,58,237,0.15);background:transparent;color:var(--purple);font-weight:700}

    /* Stats */
    .stats{display:flex;gap:14px;margin-top:28px}
    .stat{background:white;padding:14px;border-radius:12px;min-width:150px;box-shadow:var(--card-shadow);text-align:left}
    .stat b{display:block;font-size:20px;color:var(--indigo);font-weight:800}
    .stat span{color:var(--muted);font-weight:600}

    /* Right avatar */
    .avatar-wrap{display:flex;justify-content:center}
    .avatar-outer{background:linear-gradient(180deg, rgba(124,58,237,0.18), rgba(99,102,241,0.08));padding:12px;border-radius:999px;box-shadow:0 20px 60px rgba(99,102,241,0.12)}
    .avatar{width:320px;height:320px;border-radius:50%;overflow:hidden;display:block;background:white;position:relative;box-shadow:0 8px 30px rgba(79,70,229,0.08)}
    .avatar-ring{position:absolute;inset:0;border-radius:50%;padding:10px;box-sizing:border-box;pointer-events:none}
    .avatar img, .avatar svg{width:100%;height:100%;display:block}

    /* Responsive */
    @media (max-width:980px){
      .container{grid-template-columns:1fr;gap:28px}
      nav{padding:10px}
      .nav-center{display:none}
      .avatar{width:260px;height:260px}
      h1{font-size:40px}
      .stats{flex-wrap:wrap}
    }
  </style>
</head>
<body>
  <div class="nav-wrap">
    <nav role="navigation" aria-label="Main navigation">
      <div class="logo">Harsh Verma</div>
      <div class="nav-center" role="menubar">
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services" class="active">Services</a>
        <a href="#portfolio">Portfolio</a>
      </div>
      <div class="nav-actions">
        <button class="btn-contact">Contact</button>
        <button class="toggle" aria-label="Toggle dark mode">🌙</button>
      </div>
    </nav>
  </div>

  <main class="container" role="main">
    <section class="left">
      <div class="badge"><span class="dot"></span>Available for freelance projects</div>
      <div class="label">HELLO, I'M</div>
      <h1>Harsh Verma</h1>
      <div class="subtitle">Graphic Designer | Video Editor | Web Developer</div>
      <p class="lead">I’m a multidisciplinary creative with 4+ years of experience crafting visual identities, editing immersive video content, and building polished websites. I collaborate with brands and creators to deliver high-quality, thoughtful design and front-end builds.</p>

      <div class="cta-row">
        <button class="btn-primary">View My Work</button>
        <button class="btn-outline">Get In Touch</button>
      </div>

      <div class="stats" aria-label="Key stats">
        <div class="stat"><b>50+</b><span>Projects delivered</span></div>
        <div class="stat"><b>30+</b><span>Happy clients</span></div>
        <div class="stat"><b>4+</b><span>Years Creative experience</span></div>
      </div>
    </section>

    <aside class="avatar-wrap" aria-hidden="false">
      <div class="avatar-outer">
        <div class="avatar">
          <!-- Cartoon SVG avatar -->
          <svg viewBox="0 0 240 240" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Cartoon avatar">
            <defs>
              <linearGradient id="g1" x1="0" x2="1">
                <stop offset="0" stop-color="#8b5cf6" />
                <stop offset="1" stop-color="#06b6d4" />
              </linearGradient>
              <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
                <feGaussianBlur stdDeviation="8" result="b"/>
                <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
              </filter>
            </defs>
            <rect width="240" height="240" rx="120" fill="#fff"/>
            <circle cx="120" cy="86" r="48" fill="#FDE68A"/>
            <path d="M78 120c12-8 48-18 84 0v28H78v-28z" fill="#FCA5A5"/>
            <ellipse cx="102" cy="82" rx="6" ry="8" fill="#111827"/>
            <ellipse cx="138" cy="82" rx="6" ry="8" fill="#111827"/>
            <path d="M92 102c8 6 24 6 32 0" stroke="#111827" stroke-linecap="round" stroke-width="3" fill="none"/>
            <g transform="translate(36,28)">
              <path d="M48 40c-12-4-28 2-36 10 0 0 10-24 40-26 26-2 36 24 36 24s-14-12-40-8z" fill="#4f46e5" opacity="0.95"/>
            </g>
            <circle cx="120" cy="120" r="106" fill="none" stroke="url(#g1)" stroke-width="8" filter="url(#glow)"/>
          </svg>
        </div>
      </div>
    </aside>
  </main>

</body>
</html>
