<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Puptag — Fast-Paced VR Movement</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg: #0a0a0b;
      --surface: #111113;
      --border: rgba(255,255,255,0.07);
      --accent: #4da8ff;
      --accent2: #a78bfa;
      --text: #f0f0f2;
      --muted: #888892;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'DM Sans', sans-serif;
      font-weight: 300;
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* ─── NAV ─────────────────────────────────── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1.2rem 4rem;
      background: rgba(10,10,11,0.85);
      backdrop-filter: blur(14px);
      border-bottom: 1px solid var(--border);
    }

    .nav-logo {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 1.3rem;
      letter-spacing: 0.08em;
      color: var(--text);
      text-decoration: none;
    }
    .nav-logo span { color: var(--accent); }

    .nav-links {
      display: flex;
      gap: 2.5rem;
      list-style: none;
    }
    .nav-links a {
      color: var(--muted);
      text-decoration: none;
      font-size: 0.875rem;
      letter-spacing: 0.04em;
      transition: color 0.2s;
    }
    .nav-links a:hover { color: var(--text); }

    .nav-cta {
      background: var(--accent);
      color: #000 !important;
      font-weight: 500 !important;
      padding: 0.5rem 1.25rem;
      border-radius: 4px;
      transition: opacity 0.2s !important;
    }
    .nav-cta:hover { opacity: 0.85; color: #000 !important; }

    /* ─── HERO ────────────────────────────────── */
    #home {
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      position: relative;
      overflow: hidden;
      padding: 8rem 2rem 4rem;
    }

    .hero-bg {
      position: absolute;
      inset: 0;
      background: url('Screenshot_2026-03-01_125758.png') center/cover no-repeat;
      filter: brightness(0.18) saturate(0.6);
      transform: scale(1.05);
      animation: slowzoom 20s ease-in-out infinite alternate;
    }

    @keyframes slowzoom {
      from { transform: scale(1.05); }
      to   { transform: scale(1.12); }
    }

    .hero-overlay {
      position: absolute;
      inset: 0;
      background: radial-gradient(ellipse at center, transparent 30%, var(--bg) 90%);
    }

    .hero-content {
      position: relative;
      z-index: 2;
      max-width: 780px;
    }

    .hero-badge {
      display: inline-block;
      background: rgba(77,168,255,0.12);
      border: 1px solid rgba(77,168,255,0.3);
      color: var(--accent);
      font-size: 0.75rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      padding: 0.35rem 1rem;
      border-radius: 100px;
      margin-bottom: 1.5rem;
      font-family: 'Syne', sans-serif;
      font-weight: 600;
    }

    .hero-title {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: clamp(3.5rem, 9vw, 7rem);
      line-height: 0.95;
      letter-spacing: -0.02em;
      margin-bottom: 1.5rem;
    }

    .hero-title .line2 {
      display: block;
      color: transparent;
      -webkit-text-stroke: 1px rgba(255,255,255,0.3);
    }

    .hero-sub {
      font-size: 1.05rem;
      color: var(--muted);
      max-width: 520px;
      margin: 0 auto 2.5rem;
      line-height: 1.7;
    }

    .hero-btns {
      display: flex;
      gap: 1rem;
      justify-content: center;
      flex-wrap: wrap;
    }

    .btn-primary {
      background: var(--accent);
      color: #000;
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: 0.9rem;
      letter-spacing: 0.06em;
      padding: 0.85rem 2rem;
      border-radius: 5px;
      text-decoration: none;
      transition: opacity 0.2s, transform 0.2s;
    }
    .btn-primary:hover { opacity: 0.88; transform: translateY(-2px); }

    .btn-secondary {
      border: 1px solid var(--border);
      color: var(--muted);
      font-family: 'Syne', sans-serif;
      font-weight: 600;
      font-size: 0.9rem;
      letter-spacing: 0.06em;
      padding: 0.85rem 2rem;
      border-radius: 5px;
      text-decoration: none;
      background: rgba(255,255,255,0.03);
      transition: border-color 0.2s, color 0.2s, transform 0.2s;
    }
    .btn-secondary:hover { border-color: rgba(255,255,255,0.2); color: var(--text); transform: translateY(-2px); }

    /* ─── STATS BAR ───────────────────────────── */
    .stats-bar {
      background: var(--surface);
      border-top: 1px solid var(--border);
      border-bottom: 1px solid var(--border);
      padding: 1.5rem 4rem;
      display: flex;
      justify-content: center;
      gap: 5rem;
      flex-wrap: wrap;
    }

    .stat {
      text-align: center;
    }
    .stat-number {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 1.8rem;
      color: var(--accent);
    }
    .stat-label {
      font-size: 0.78rem;
      color: var(--muted);
      letter-spacing: 0.08em;
      text-transform: uppercase;
      margin-top: 0.15rem;
    }

    /* ─── SECTIONS ────────────────────────────── */
    section {
      padding: 6rem 4rem;
      max-width: 1200px;
      margin: 0 auto;
    }

    .section-label {
      font-family: 'Syne', sans-serif;
      font-weight: 600;
      font-size: 0.72rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: var(--accent);
      margin-bottom: 0.75rem;
    }

    .section-title {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: clamp(1.8rem, 4vw, 2.8rem);
      letter-spacing: -0.02em;
      margin-bottom: 1rem;
      line-height: 1.1;
    }

    .section-body {
      color: var(--muted);
      max-width: 560px;
      font-size: 1rem;
      line-height: 1.75;
    }

    /* ─── ABOUT ───────────────────────────────── */
    #about .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: center;
    }

    .about-img {
      position: relative;
      border-radius: 8px;
      overflow: hidden;
      aspect-ratio: 16/9;
    }
    .about-img img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
    }
    .about-img::after {
      content: '';
      position: absolute;
      inset: 0;
      border: 1px solid var(--border);
      border-radius: 8px;
      pointer-events: none;
    }

    .features {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1rem;
      margin-top: 2.5rem;
    }

    .feature-card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 1.25rem;
      transition: border-color 0.2s;
    }
    .feature-card:hover { border-color: rgba(77,168,255,0.25); }

    .feature-icon {
      font-size: 1.3rem;
      margin-bottom: 0.5rem;
    }
    .feature-title {
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: 0.9rem;
      margin-bottom: 0.3rem;
    }
    .feature-desc {
      font-size: 0.8rem;
      color: var(--muted);
      line-height: 1.5;
    }

    /* ─── GALLERY ─────────────────────────────── */
    #gallery {
      max-width: 100%;
      padding: 6rem 4rem;
    }
    #gallery .inner {
      max-width: 1200px;
      margin: 0 auto;
    }

    .gallery-header {
      margin-bottom: 2.5rem;
    }

    .gallery-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      grid-template-rows: auto auto;
      gap: 0.75rem;
    }

    .gallery-item {
      position: relative;
      overflow: hidden;
      border-radius: 6px;
      aspect-ratio: 16/9;
      cursor: pointer;
      background: var(--surface);
    }

    .gallery-item:first-child {
      grid-column: span 2;
      aspect-ratio: auto;
    }

    .gallery-item img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: transform 0.5s ease, filter 0.3s;
      filter: brightness(0.85);
    }

    .gallery-item:hover img {
      transform: scale(1.04);
      filter: brightness(1);
    }

    .gallery-item::after {
      content: '';
      position: absolute;
      inset: 0;
      border: 1px solid var(--border);
      border-radius: 6px;
      pointer-events: none;
    }

    /* ─── DOWNLOAD ────────────────────────────── */
    #download {
      text-align: center;
    }

    .download-box {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 4rem 3rem;
      max-width: 640px;
      margin: 0 auto;
      position: relative;
      overflow: hidden;
    }

    .download-box::before {
      content: '';
      position: absolute;
      top: -60px; left: 50%;
      transform: translateX(-50%);
      width: 300px;
      height: 300px;
      background: radial-gradient(circle, rgba(77,168,255,0.08) 0%, transparent 70%);
      pointer-events: none;
    }

    .download-title {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 2rem;
      margin-bottom: 0.75rem;
    }

    .download-sub {
      color: var(--muted);
      margin-bottom: 2rem;
      font-size: 0.95rem;
    }

    .platform-chips {
      display: flex;
      justify-content: center;
      gap: 0.6rem;
      flex-wrap: wrap;
      margin-bottom: 2rem;
    }

    .chip {
      background: rgba(255,255,255,0.05);
      border: 1px solid var(--border);
      border-radius: 100px;
      padding: 0.3rem 0.85rem;
      font-size: 0.78rem;
      color: var(--muted);
      letter-spacing: 0.04em;
    }

    .download-btns {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      align-items: center;
    }

    .btn-download {
      display: flex;
      align-items: center;
      gap: 0.6rem;
      background: var(--accent);
      color: #000;
      font-family: 'Syne', sans-serif;
      font-weight: 700;
      font-size: 0.95rem;
      letter-spacing: 0.04em;
      padding: 0.9rem 2.2rem;
      border-radius: 6px;
      text-decoration: none;
      width: 100%;
      max-width: 320px;
      justify-content: center;
      transition: opacity 0.2s, transform 0.2s;
    }
    .btn-download:hover { opacity: 0.88; transform: translateY(-2px); }

    .btn-download.secondary {
      background: transparent;
      color: var(--muted);
      border: 1px solid var(--border);
    }
    .btn-download.secondary:hover { color: var(--text); border-color: rgba(255,255,255,0.2); }

    /* ─── FOOTER ──────────────────────────────── */
    footer {
      border-top: 1px solid var(--border);
      padding: 2rem 4rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .footer-logo {
      font-family: 'Syne', sans-serif;
      font-weight: 800;
      font-size: 1rem;
      letter-spacing: 0.08em;
    }
    .footer-logo span { color: var(--accent); }

    footer p {
      color: var(--muted);
      font-size: 0.8rem;
    }

    /* ─── LIGHTBOX ────────────────────────────── */
    .lightbox {
      display: none;
      position: fixed;
      inset: 0;
      background: rgba(0,0,0,0.92);
      z-index: 999;
      align-items: center;
      justify-content: center;
    }
    .lightbox.active { display: flex; }
    .lightbox img {
      max-width: 90vw;
      max-height: 85vh;
      border-radius: 6px;
      object-fit: contain;
    }
    .lightbox-close {
      position: absolute;
      top: 1.5rem;
      right: 2rem;
      font-size: 2rem;
      color: var(--muted);
      cursor: pointer;
      transition: color 0.2s;
      background: none;
      border: none;
      line-height: 1;
    }
    .lightbox-close:hover { color: var(--text); }

    /* ─── SCROLL REVEAL ───────────────────────── */
    .reveal {
      opacity: 0;
      transform: translateY(24px);
      transition: opacity 0.65s ease, transform 0.65s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: none;
    }

    /* ─── RESPONSIVE ──────────────────────────── */
    @media (max-width: 900px) {
      nav { padding: 1rem 1.5rem; }
      .nav-links { display: none; }
      section { padding: 4rem 1.5rem; }
      #gallery { padding: 4rem 1.5rem; }
      #about .about-grid { grid-template-columns: 1fr; gap: 2.5rem; }
      .gallery-grid { grid-template-columns: 1fr 1fr; }
      .gallery-item:first-child { grid-column: span 2; }
      .stats-bar { padding: 1.5rem; gap: 2.5rem; }
      footer { padding: 1.5rem; }
    }

    @media (max-width: 560px) {
      .gallery-grid { grid-template-columns: 1fr; }
      .gallery-item:first-child { grid-column: auto; }
      .features { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#home" class="nav-logo">PUP<span>TAG</span></a>
  <ul class="nav-links">
    <li><a href="#home">Home</a></li>
    <li><a href="#about">About</a></li>
    <li><a href="#gallery">Gallery</a></li>
    <li><a href="#download" class="nav-cta">Download</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="home">
  <div class="hero-bg"></div>
  <div class="hero-overlay"></div>
  <div class="hero-content">
    <div class="hero-badge">PC VR · App Lab · Free to Play</div>
    <h1 class="hero-title">
      PUP<span class="line2">TAG</span>
    </h1>
    <p class="hero-sub">
      Fast-paced gorilla movement tag built for VR. Master wall climbs, jukes, and high-speed chases across wild maps — and outrun everyone.
    </p>
    <div class="hero-btns">
      <a href="#download" class="btn-primary">Get the Game</a>
      <a href="#gallery" class="btn-secondary">See Screenshots</a>
    </div>
  </div>
</section>

<!-- STATS -->
<div class="stats-bar">
  <div class="stat">
    <div class="stat-number">4</div>
    <div class="stat-label">Game Modes</div>
  </div>
  <div class="stat">
    <div class="stat-number">VR</div>
    <div class="stat-label">Platform</div>
  </div>
  <div class="stat">
    <div class="stat-number">Free</div>
    <div class="stat-label">To Play</div>
  </div>
  <div class="stat">
    <div class="stat-number">∞</div>
    <div class="stat-label">Skill Ceiling</div>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <div class="about-grid">
    <div class="about-text reveal">
      <div class="section-label">About the Game</div>
      <h2 class="section-title">Movement is everything.</h2>
      <p class="section-body">
        Puptag is a competitive VR movement game where gorilla-style locomotion meets high-stakes tag. Sprint, vault, and climb across diverse maps — from snowy mountain courses to neon-lit city streets — while chasing down opponents or escaping by a hair.
      </p>
      <p class="section-body" style="margin-top:1rem;">
        With four distinct game modes — Casual, Infection, Hunt, and Paintbrawl — every match is a fresh test of your movement skill and game sense.
      </p>
      <div class="features">
        <div class="feature-card">
          <div class="feature-icon">🎮</div>
          <div class="feature-title">4 Game Modes</div>
          <div class="feature-desc">Casual, Infection, Hunt, and Paintbrawl — each with its own flow.</div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🏔️</div>
          <div class="feature-title">Diverse Maps</div>
          <div class="feature-desc">Snow, caves, forests, and urban environments to master.</div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">🐾</div>
          <div class="feature-title">Skill-Based</div>
          <div class="feature-desc">Wall climbs, jukes, and momentum — your movement is your weapon.</div>
        </div>
        <div class="feature-card">
          <div class="feature-icon">⚡</div>
          <div class="feature-title">Optimized VR</div>
          <div class="feature-desc">Smooth locomotion built for PC VR and App Lab.</div>
        </div>
      </div>
    </div>
    <div class="about-img reveal" style="transition-delay:0.15s">
      <img src="Screenshot_2026-03-01_125711.png" alt="Puptag snow map gameplay" />
    </div>
  </div>
</section>

<!-- GALLERY -->
<div id="gallery">
  <div class="inner">
    <div class="gallery-header reveal">
      <div class="section-label">Gallery</div>
      <h2 class="section-title">See the world of Puptag.</h2>
    </div>
    <div class="gallery-grid">
      <div class="gallery-item reveal" style="transition-delay:0.0s">
        <img src="Screenshot_2026-03-01_125758.png" alt="Interior lobby" />
      </div>
      <div class="gallery-item reveal" style="transition-delay:0.1s">
        <img src="Screenshot_2026-03-01_125711.png" alt="Snow map" />
      </div>
      <div class="gallery-item reveal" style="transition-delay:0.15s">
        <img src="Screenshot_2026-03-01_125624.png" alt="Forest map" />
      </div>
      <div class="gallery-item reveal" style="transition-delay:0.2s">
        <img src="Screenshot_2026-03-01_125810.png" alt="City map" />
      </div>
      <div class="gallery-item reveal" style="transition-delay:0.25s">
        <img src="Screenshot_2026-03-01_125746.png" alt="Cave tunnel" />
      </div>
      <div class="gallery-item reveal" style="transition-delay:0.3s">
        <img src="Screenshot_2026-03-01_125723.png" alt="Game menu" />
      </div>
    </div>
  </div>
</div>

<!-- DOWNLOAD -->
<section id="download">
  <div class="download-box reveal">
    <div class="section-label" style="text-align:center;margin-bottom:1rem;">Get Puptag</div>
    <h2 class="download-title">Ready to run?</h2>
    <p class="download-sub">Available free on Meta App Lab and PC VR. Jump in solo or with friends.</p>
    <div class="platform-chips">
      <span class="chip">PC VR</span>
      <span class="chip">Meta Quest (App Lab)</span>
      <span class="chip">Free to Play</span>
    </div>
    <div class="download-btns">
      <a href="#" class="btn-download secondary" style="cursor:not-allowed;opacity:0.5;" onclick="return false;">
        <span>▶</span> App Lab — Coming Soon
      </a>
      <a href="https://drive.google.com/uc?export=download&id=1VbeEWR8NZabSKcM2ACXl06ARIiTR60-s" class="btn-download" target="_blank" rel="noopener">
        <span>↓</span> Download for PC VR
      </a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">PUP<span>TAG</span></div>
  <p>© 2026 Puptag. All rights reserved.</p>
  <p style="color:var(--muted)">Built for VR movement lovers.</p>
</footer>

<!-- LIGHTBOX -->
<div class="lightbox" id="lightbox">
  <button class="lightbox-close" id="lightboxClose">×</button>
  <img id="lightboxImg" src="" alt="" />
</div>

<script>
  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) {
        e.target.classList.add('visible');
        observer.unobserve(e.target);
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));

  // Lightbox
  const lightbox = document.getElementById('lightbox');
  const lightboxImg = document.getElementById('lightboxImg');
  document.querySelectorAll('.gallery-item img').forEach(img => {
    img.addEventListener('click', () => {
      lightboxImg.src = img.src;
      lightboxImg.alt = img.alt;
      lightbox.classList.add('active');
    });
  });
  document.getElementById('lightboxClose').addEventListener('click', () => lightbox.classList.remove('active'));
  lightbox.addEventListener('click', e => { if (e.target === lightbox) lightbox.classList.remove('active'); });
  document.addEventListener('keydown', e => { if (e.key === 'Escape') lightbox.classList.remove('active'); });
</script>
</body>
</html>
