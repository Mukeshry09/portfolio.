<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mukesh Kanna — Software Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;600;700;800&family=DM+Mono:ital,wght@0,300;0,400;0,500;1,300&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;1,9..40,300&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #0a0a0f;
      --bg2: #111118;
      --card: #14141e;
      --border: #1e1e2e;
      --accent: #6ee7b7;
      --accent2: #38bdf8;
      --accent3: #f472b6;
      --text: #e2e8f0;
      --muted: #64748b;
      --muted2: #475569;
      --white: #f8fafc;
      --font-display: 'Syne', sans-serif;
      --font-mono: 'DM Mono', monospace;
      --font-body: 'DM Sans', sans-serif;
    }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: var(--font-body);
      font-size: 16px;
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* ── NOISE OVERLAY ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.03'/%3E%3C/svg%3E");
      pointer-events: none;
      z-index: 9999;
      opacity: 0.4;
    }

    /* ── SCROLLBAR ── */
    ::-webkit-scrollbar { width: 4px; }
    ::-webkit-scrollbar-track { background: var(--bg); }
    ::-webkit-scrollbar-thumb { background: var(--accent); border-radius: 2px; }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      padding: 20px 48px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      backdrop-filter: blur(20px);
      background: rgba(10, 10, 15, 0.8);
      border-bottom: 1px solid rgba(255,255,255,0.04);
      transition: all 0.3s;
    }

    .nav-logo {
      font-family: var(--font-display);
      font-size: 18px;
      font-weight: 800;
      color: var(--white);
      text-decoration: none;
      letter-spacing: -0.5px;
    }

    .nav-logo span { color: var(--accent); }

    .nav-links {
      display: flex;
      gap: 32px;
      list-style: none;
    }

    .nav-links a {
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--muted);
      text-decoration: none;
      letter-spacing: 0.05em;
      transition: color 0.2s;
      position: relative;
    }

    .nav-links a::before {
      content: attr(data-num);
      color: var(--accent);
      margin-right: 4px;
      font-size: 11px;
    }

    .nav-links a:hover { color: var(--white); }

    .nav-cta {
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--accent);
      text-decoration: none;
      border: 1px solid var(--accent);
      padding: 8px 20px;
      border-radius: 4px;
      transition: all 0.2s;
      letter-spacing: 0.05em;
    }

    .nav-cta:hover {
      background: rgba(110, 231, 183, 0.1);
    }

    /* ── HERO ── */
    #hero {
      min-height: 100vh;
      display: flex;
      align-items: center;
      padding: 120px 48px 80px;
      position: relative;
      overflow: hidden;
    }

    .hero-glow {
      position: absolute;
      width: 600px;
      height: 600px;
      border-radius: 50%;
      filter: blur(120px);
      pointer-events: none;
    }

    .glow-1 {
      background: radial-gradient(circle, rgba(110,231,183,0.12) 0%, transparent 70%);
      top: -100px;
      right: -100px;
    }

    .glow-2 {
      background: radial-gradient(circle, rgba(56,189,248,0.08) 0%, transparent 70%);
      bottom: -200px;
      left: -100px;
    }

    .hero-inner {
      max-width: 1100px;
      margin: 0 auto;
      width: 100%;
      position: relative;
      z-index: 1;
    }

    .hero-eyebrow {
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--accent);
      letter-spacing: 0.15em;
      text-transform: uppercase;
      margin-bottom: 24px;
      display: flex;
      align-items: center;
      gap: 12px;
      opacity: 0;
      animation: fadeUp 0.6s ease 0.2s forwards;
    }

    .hero-eyebrow::before {
      content: '';
      width: 40px;
      height: 1px;
      background: var(--accent);
    }

    .hero-name {
      font-family: var(--font-display);
      font-size: clamp(52px, 8vw, 96px);
      font-weight: 800;
      line-height: 0.95;
      color: var(--white);
      letter-spacing: -3px;
      margin-bottom: 16px;
      opacity: 0;
      animation: fadeUp 0.6s ease 0.35s forwards;
    }

    .hero-name .line2 {
      color: transparent;
      -webkit-text-stroke: 1.5px rgba(255,255,255,0.25);
    }

    .hero-title {
      font-family: var(--font-display);
      font-size: clamp(18px, 2.5vw, 28px);
      font-weight: 500;
      color: var(--muted);
      margin-bottom: 32px;
      letter-spacing: -0.5px;
      opacity: 0;
      animation: fadeUp 0.6s ease 0.5s forwards;
    }

    .hero-title .highlight {
      color: var(--accent2);
    }

    .hero-desc {
      max-width: 520px;
      font-size: 16px;
      color: var(--muted);
      line-height: 1.8;
      margin-bottom: 48px;
      opacity: 0;
      animation: fadeUp 0.6s ease 0.65s forwards;
    }

    .hero-actions {
      display: flex;
      gap: 16px;
      flex-wrap: wrap;
      opacity: 0;
      animation: fadeUp 0.6s ease 0.8s forwards;
    }

    .btn-primary {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: var(--accent);
      color: #0a0a0f;
      font-family: var(--font-mono);
      font-size: 13px;
      font-weight: 500;
      padding: 14px 28px;
      border-radius: 4px;
      text-decoration: none;
      letter-spacing: 0.05em;
      transition: all 0.2s;
    }

    .btn-primary:hover {
      background: #a7f3d0;
      transform: translateY(-2px);
      box-shadow: 0 8px 30px rgba(110, 231, 183, 0.3);
    }

    .btn-secondary {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      background: transparent;
      color: var(--text);
      font-family: var(--font-mono);
      font-size: 13px;
      padding: 14px 28px;
      border-radius: 4px;
      border: 1px solid var(--border);
      text-decoration: none;
      letter-spacing: 0.05em;
      transition: all 0.2s;
    }

    .btn-secondary:hover {
      border-color: var(--muted2);
      background: var(--card);
      transform: translateY(-2px);
    }

    .hero-scroll {
      position: absolute;
      bottom: 40px;
      left: 48px;
      display: flex;
      align-items: center;
      gap: 12px;
      font-family: var(--font-mono);
      font-size: 11px;
      color: var(--muted2);
      letter-spacing: 0.1em;
      opacity: 0;
      animation: fadeUp 0.6s ease 1.1s forwards;
    }

    .scroll-line {
      width: 1px;
      height: 50px;
      background: linear-gradient(to bottom, var(--accent), transparent);
      animation: scrollDown 1.5s ease infinite;
    }

    @keyframes scrollDown {
      0%, 100% { transform: scaleY(1); opacity: 1; }
      50% { transform: scaleY(0.5); opacity: 0.4; }
    }

    /* ── SECTION COMMON ── */
    section { padding: 100px 48px; }

    .section-inner {
      max-width: 1100px;
      margin: 0 auto;
    }

    .section-label {
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--accent);
      letter-spacing: 0.2em;
      text-transform: uppercase;
      margin-bottom: 16px;
      display: flex;
      align-items: center;
      gap: 12px;
    }

    .section-label::after {
      content: '';
      flex: 1;
      max-width: 60px;
      height: 1px;
      background: var(--border);
    }

    .section-title {
      font-family: var(--font-display);
      font-size: clamp(32px, 4vw, 48px);
      font-weight: 800;
      color: var(--white);
      letter-spacing: -2px;
      line-height: 1.05;
      margin-bottom: 60px;
    }

    /* ── ABOUT / SKILLS ── */
    #about { background: var(--bg); }

    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 80px;
      align-items: start;
    }

    .about-text p {
      color: var(--muted);
      line-height: 1.9;
      margin-bottom: 20px;
      font-size: 15px;
    }

    .about-text p strong {
      color: var(--text);
      font-weight: 500;
    }

    .about-meta {
      margin-top: 32px;
      display: flex;
      flex-direction: column;
      gap: 12px;
    }

    .meta-item {
      display: flex;
      align-items: center;
      gap: 12px;
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--muted);
    }

    .meta-item .icon { color: var(--accent); font-size: 14px; }

    .skills-side {}

    .skills-category {
      margin-bottom: 36px;
    }

    .skills-category-title {
      font-family: var(--font-mono);
      font-size: 11px;
      color: var(--accent);
      letter-spacing: 0.15em;
      text-transform: uppercase;
      margin-bottom: 14px;
    }

    .skills-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .tag {
      font-family: var(--font-mono);
      font-size: 12px;
      padding: 6px 14px;
      border-radius: 3px;
      border: 1px solid var(--border);
      color: var(--text);
      background: var(--card);
      transition: all 0.2s;
      cursor: default;
    }

    .tag:hover {
      border-color: var(--accent);
      color: var(--accent);
      background: rgba(110, 231, 183, 0.05);
    }

    .tag.learning {
      border-color: rgba(244, 114, 182, 0.3);
      color: var(--muted);
    }

    .tag.learning:hover {
      border-color: var(--accent3);
      color: var(--accent3);
    }

    /* ── PROJECTS ── */
    #projects { background: var(--bg2); }

    .projects-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .project-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 32px;
      transition: all 0.3s;
      position: relative;
      overflow: hidden;
      cursor: default;
    }

    .project-card::before {
      content: '';
      position: absolute;
      top: 0; left: 0; right: 0;
      height: 2px;
      background: linear-gradient(90deg, var(--accent), var(--accent2));
      transform: scaleX(0);
      transform-origin: left;
      transition: transform 0.3s;
    }

    .project-card:hover {
      border-color: rgba(110, 231, 183, 0.2);
      transform: translateY(-4px);
      box-shadow: 0 20px 60px rgba(0,0,0,0.4);
    }

    .project-card:hover::before {
      transform: scaleX(1);
    }

    .project-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 20px;
    }

    .project-icon {
      font-size: 28px;
      line-height: 1;
    }

    .project-links {
      display: flex;
      gap: 12px;
    }

    .project-links a {
      color: var(--muted2);
      font-size: 16px;
      text-decoration: none;
      transition: color 0.2s;
    }

    .project-links a:hover { color: var(--accent); }

    .project-title {
      font-family: var(--font-display);
      font-size: 20px;
      font-weight: 700;
      color: var(--white);
      margin-bottom: 8px;
      letter-spacing: -0.5px;
    }

    .project-status {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      font-family: var(--font-mono);
      font-size: 10px;
      color: var(--accent3);
      letter-spacing: 0.1em;
      text-transform: uppercase;
      margin-bottom: 12px;
    }

    .project-status .dot {
      width: 5px;
      height: 5px;
      border-radius: 50%;
      background: var(--accent3);
      animation: pulse 2s infinite;
    }

    @keyframes pulse {
      0%, 100% { opacity: 1; }
      50% { opacity: 0.3; }
    }

    .project-desc {
      font-size: 14px;
      color: var(--muted);
      line-height: 1.7;
      margin-bottom: 24px;
    }

    .project-tech {
      display: flex;
      flex-wrap: wrap;
      gap: 6px;
    }

    .tech-badge {
      font-family: var(--font-mono);
      font-size: 11px;
      color: var(--accent2);
      background: rgba(56, 189, 248, 0.08);
      border: 1px solid rgba(56, 189, 248, 0.15);
      padding: 3px 10px;
      border-radius: 2px;
    }

    /* ── EXPERIENCE ── */
    #experience { background: var(--bg); }

    .timeline {
      position: relative;
      padding-left: 40px;
    }

    .timeline::before {
      content: '';
      position: absolute;
      left: 0;
      top: 8px;
      bottom: 8px;
      width: 1px;
      background: linear-gradient(to bottom, var(--accent), transparent);
    }

    .timeline-item {
      position: relative;
      margin-bottom: 52px;
    }

    .timeline-item:last-child { margin-bottom: 0; }

    .timeline-dot {
      position: absolute;
      left: -44px;
      top: 6px;
      width: 9px;
      height: 9px;
      border-radius: 50%;
      background: var(--accent);
      border: 2px solid var(--bg);
      box-shadow: 0 0 0 3px rgba(110, 231, 183, 0.2);
    }

    .timeline-date {
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--accent);
      letter-spacing: 0.1em;
      margin-bottom: 8px;
    }

    .timeline-role {
      font-family: var(--font-display);
      font-size: 20px;
      font-weight: 700;
      color: var(--white);
      letter-spacing: -0.5px;
      margin-bottom: 4px;
    }

    .timeline-company {
      font-size: 14px;
      color: var(--muted);
      margin-bottom: 14px;
      font-style: italic;
    }

    .timeline-points {
      list-style: none;
      display: flex;
      flex-direction: column;
      gap: 8px;
    }

    .timeline-points li {
      font-size: 14px;
      color: var(--muted);
      line-height: 1.7;
      padding-left: 16px;
      position: relative;
    }

    .timeline-points li::before {
      content: '▸';
      position: absolute;
      left: 0;
      color: var(--accent);
      font-size: 10px;
      top: 3px;
    }

    /* ── EDUCATION ── */
    #education { background: var(--bg2); }

    .edu-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 24px;
    }

    .edu-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 8px;
      padding: 32px;
      transition: all 0.3s;
    }

    .edu-card:hover {
      border-color: rgba(110, 231, 183, 0.2);
      transform: translateY(-2px);
    }

    .edu-degree {
      font-family: var(--font-display);
      font-size: 18px;
      font-weight: 700;
      color: var(--white);
      letter-spacing: -0.3px;
      margin-bottom: 6px;
    }

    .edu-school {
      font-size: 14px;
      color: var(--accent2);
      margin-bottom: 4px;
    }

    .edu-year {
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--muted2);
      margin-bottom: 16px;
    }

    .edu-grade {
      display: inline-flex;
      align-items: center;
      gap: 8px;
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--accent);
      background: rgba(110, 231, 183, 0.08);
      border: 1px solid rgba(110, 231, 183, 0.15);
      padding: 6px 14px;
      border-radius: 3px;
    }

    .edu-coursework {
      margin-top: 16px;
      font-size: 13px;
      color: var(--muted2);
      line-height: 1.6;
    }

    .edu-coursework strong { color: var(--muted); }

    /* ── CONTACT ── */
    #contact {
      background: var(--bg);
      text-align: center;
    }

    .contact-inner {
      max-width: 600px;
      margin: 0 auto;
    }

    .contact-desc {
      color: var(--muted);
      font-size: 16px;
      line-height: 1.8;
      margin-bottom: 48px;
    }

    .contact-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-bottom: 60px;
    }

    .contact-link {
      display: flex;
      align-items: center;
      gap: 8px;
      font-family: var(--font-mono);
      font-size: 13px;
      color: var(--muted);
      text-decoration: none;
      padding: 12px 24px;
      border: 1px solid var(--border);
      border-radius: 4px;
      transition: all 0.2s;
      background: var(--card);
    }

    .contact-link:hover {
      color: var(--accent);
      border-color: var(--accent);
      background: rgba(110, 231, 183, 0.05);
      transform: translateY(-2px);
    }

    .contact-link svg { width: 16px; height: 16px; }

    /* ── FOOTER ── */
    footer {
      padding: 32px 48px;
      border-top: 1px solid var(--border);
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    .footer-text {
      font-family: var(--font-mono);
      font-size: 12px;
      color: var(--muted2);
    }

    .footer-text span { color: var(--accent); }

    /* ── ANIMATIONS ── */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }

    .reveal.visible {
      opacity: 1;
      transform: none;
    }

    /* ── HAMBURGER ── */
    .hamburger {
      display: none;
      flex-direction: column;
      gap: 5px;
      cursor: pointer;
      background: none;
      border: none;
      padding: 4px;
    }

    .hamburger span {
      display: block;
      width: 24px;
      height: 2px;
      background: var(--text);
      border-radius: 2px;
      transition: all 0.3s;
    }

    /* ── RESPONSIVE ── */
    @media (max-width: 900px) {
      nav { padding: 18px 24px; }
      .nav-links, .nav-cta { display: none; }
      .hamburger { display: flex; }
      #hero { padding: 100px 24px 80px; }
      .hero-scroll { left: 24px; }
      section { padding: 72px 24px; }
      footer { padding: 24px; }
      .about-grid { grid-template-columns: 1fr; gap: 48px; }
      .projects-grid { grid-template-columns: 1fr; }
      .edu-grid { grid-template-columns: 1fr; }
    }

    /* ── CURSOR GLOW ── */
    .cursor-glow {
      position: fixed;
      width: 300px;
      height: 300px;
      border-radius: 50%;
      pointer-events: none;
      z-index: 0;
      background: radial-gradient(circle, rgba(110,231,183,0.04) 0%, transparent 70%);
      transform: translate(-50%, -50%);
      transition: left 0.15s ease, top 0.15s ease;
    }
  </style>
</head>
<body>

  <div class="cursor-glow" id="cursorGlow"></div>

  <!-- NAV -->
  <nav>
    <a href="#hero" class="nav-logo">MK<span>.</span></a>
    <ul class="nav-links">
      <li><a href="#about" data-num="01">About</a></li>
      <li><a href="#projects" data-num="02">Projects</a></li>
      <li><a href="#experience" data-num="03">Experience</a></li>
      <li><a href="#education" data-num="04">Education</a></li>
    </ul>
    <a href="mailto:mukeshry09@gmail.com" class="nav-cta">Contact Me</a>
    <button class="hamburger" aria-label="Menu">
      <span></span><span></span><span></span>
    </button>
  </nav>

  <!-- HERO -->
  <section id="hero">
    <div class="hero-glow glow-1"></div>
    <div class="hero-glow glow-2"></div>
    <div class="hero-inner">
      <div class="hero-eyebrow">Hi, I'm Mukesh Kanna</div>
      <h1 class="hero-name">
        Software<br>
        <span class="line2">Developer</span>
      </h1>
      <p class="hero-title">
        Building <span class="highlight">web experiences</span> with React &amp; JavaScript
      </p>
      <p class="hero-desc">
        ECE graduate turned software developer — passionate about building clean, responsive, and user-friendly web applications. Currently levelling up in full-stack development with React, REST APIs, Node.js, and Java.
      </p>
      <div class="hero-actions">
        <a href="#projects" class="btn-primary">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="16 18 22 12 16 6"/><polyline points="8 6 2 12 8 18"/></svg>
          View Projects
        </a>
        <a href="https://github.com/Mukeshry09" target="_blank" class="btn-secondary">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
          GitHub
        </a>
        <a href="https://linkedin.com/in/mukesh-kanna-51a7b33b8/" target="_blank" class="btn-secondary">
          <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
          LinkedIn
        </a>
      </div>
    </div>
    <div class="hero-scroll">
      <div class="scroll-line"></div>
      scroll
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <div class="section-inner">
      <div class="section-label">01 — About</div>
      <h2 class="section-title reveal">Who I Am</h2>
      <div class="about-grid">
        <div class="about-text reveal">
          <p>I'm a <strong>Software Developer</strong> from Madurai, India — an ECE graduate from SRM Institute (CGPA 8.45) who found a passion for building things on the web.</p>
          <p>My engineering background gave me a strong foundation in <strong>structured problem-solving</strong>, which I now apply to writing clean, maintainable code. I've worked in technical environments at <strong>IIT Madras</strong> and an aerospace firm, gaining exposure to professional workflows and collaborative team dynamics.</p>
          <p>Currently, I'm focused on growing my full-stack skills — deepening my knowledge of <strong>React, REST APIs, Node.js</strong>, and Java while shipping real projects.</p>
          <div class="about-meta">
            <div class="meta-item"><span class="icon">📍</span> Madurai, Tamil Nadu, India</div>
            <div class="meta-item"><span class="icon">📧</span> mukeshry09@gmail.com</div>
            <div class="meta-item"><span class="icon">🚀</span> Available Immediately</div>
            <div class="meta-item"><span class="icon">🌐</span> Remote / Hybrid / On-site (Open to relocate)</div>
          </div>
        </div>
        <div class="skills-side reveal">
          <div class="skills-category">
            <div class="skills-category-title">Frontend</div>
            <div class="skills-tags">
              <span class="tag">HTML5</span>
              <span class="tag">CSS3</span>
              <span class="tag">JavaScript (ES6+)</span>
              <span class="tag">React.js</span>
              <span class="tag">CSS Flexbox/Grid</span>
              <span class="tag">Responsive Design</span>
            </div>
          </div>
          <div class="skills-category">
            <div class="skills-category-title">Languages</div>
            <div class="skills-tags">
              <span class="tag">Java</span>
              <span class="tag">C</span>
              <span class="tag">C++</span>
            </div>
          </div>
          <div class="skills-category">
            <div class="skills-category-title">Tools & Environment</div>
            <div class="skills-tags">
              <span class="tag">Git</span>
              <span class="tag">GitHub</span>
              <span class="tag">VS Code</span>
              <span class="tag">Node.js</span>
              <span class="tag">npm</span>
            </div>
          </div>
          <div class="skills-category">
            <div class="skills-category-title">Currently Learning</div>
            <div class="skills-tags">
              <span class="tag learning">React Hooks</span>
              <span class="tag learning">REST API Integration</span>
              <span class="tag learning">Tailwind CSS</span>
              <span class="tag learning">TypeScript</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <div class="section-inner">
      <div class="section-label">02 — Projects</div>
      <h2 class="section-title reveal">What I've Built</h2>
      <div class="projects-grid">

        <div class="project-card reveal">
          <div class="project-header">
            <div class="project-icon">🗂️</div>
            <div class="project-links">
              <a href="https://github.com/Mukeshry09" target="_blank" title="GitHub">
                <svg viewBox="0 0 24 24" width="18" height="18" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
              </a>
            </div>
          </div>
          <h3 class="project-title">Personal Portfolio Website</h3>
          <p class="project-desc">Responsive personal portfolio to showcase skills, projects, and experience. Built with a mobile-first approach using CSS Flexbox and Grid with smooth scroll navigation. Deployed on GitHub Pages.</p>
          <div class="project-tech">
            <span class="tech-badge">HTML5</span>
            <span class="tech-badge">CSS3</span>
            <span class="tech-badge">JavaScript</span>
            <span class="tech-badge">GitHub Pages</span>
          </div>
        </div>

        <div class="project-card reveal">
          <div class="project-header">
            <div class="project-icon">✅</div>
            <div class="project-links">
              <a href="https://github.com/Mukeshry09" target="_blank" title="GitHub">
                <svg viewBox="0 0 24 24" width="18" height="18" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
              </a>
            </div>
          </div>
          <h3 class="project-title">To-Do List App</h3>
          <p class="project-desc">Fully functional task manager with add, delete, and mark-complete features. Uses localStorage to persist tasks across sessions without a backend — a deep dive into DOM manipulation and ES6+.</p>
          <div class="project-tech">
            <span class="tech-badge">HTML</span>
            <span class="tech-badge">CSS</span>
            <span class="tech-badge">Vanilla JS</span>
            <span class="tech-badge">localStorage</span>
          </div>
        </div>

        <div class="project-card reveal">
          <div class="project-header">
            <div class="project-icon">⚛️</div>
            <div class="project-links">
              <a href="https://github.com/Mukeshry09" target="_blank" title="GitHub">
                <svg viewBox="0 0 24 24" width="18" height="18" fill="currentColor"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
              </a>
            </div>
          </div>
          <h3 class="project-title">React Component Library</h3>
          <div class="project-status"><span class="dot"></span>In Progress</div>
          <p class="project-desc">Building a reusable collection of UI components — buttons, cards, modals, and forms. Practising component composition, props, useState, and useEffect. Goal: integrate live REST API data.</p>
          <div class="project-tech">
            <span class="tech-badge">React.js</span>
            <span class="tech-badge">CSS Modules</span>
            <span class="tech-badge">React Hooks</span>
            <span class="tech-badge">REST API</span>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience">
    <div class="section-inner">
      <div class="section-label">03 — Experience</div>
      <h2 class="section-title reveal">Where I've Worked</h2>
      <div class="timeline reveal">

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">Dec 2025 — Present</div>
          <div class="timeline-role">Business Operations Intern</div>
          <div class="timeline-company">K2 Ventures · Remote</div>
          <ul class="timeline-points">
            <li>Assisted in operational documentation, data validation, and reporting using digital tools.</li>
            <li>Developed attention to structured workflows and data accuracy in a remote professional environment.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">Apr 2025 — May 2025</div>
          <div class="timeline-role">Project Associate – Technical Intern</div>
          <div class="timeline-company">NCCRD, IIT Madras · Chennai</div>
          <ul class="timeline-points">
            <li>Worked in a structured technical environment supporting research-grade engineering analysis at IIT Madras.</li>
            <li>Documented processes, system outputs, and findings following formal quality standards.</li>
            <li>Collaborated with engineering teams, gaining exposure to technical communication and dev team workflows.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-dot"></div>
          <div class="timeline-date">Mar 2025</div>
          <div class="timeline-role">Embedded Systems Intern</div>
          <div class="timeline-company">Harpy Aerospace Pvt. Ltd. · Chennai</div>
          <ul class="timeline-points">
            <li>Performed functional testing, debugging, and troubleshooting on embedded system components.</li>
            <li>Applied C-level programming knowledge in a professional hardware-software environment.</li>
            <li>Documented technical findings and implemented structured improvement recommendations.</li>
          </ul>
        </div>

      </div>
    </div>
  </section>

  <!-- EDUCATION -->
  <section id="education">
    <div class="section-inner">
      <div class="section-label">04 — Education</div>
      <h2 class="section-title reveal">Academic Background</h2>
      <div class="edu-grid">
        <div class="edu-card reveal">
          <div class="edu-degree">B.Tech – Electronics &amp; Communication Engineering</div>
          <div class="edu-school">SRM Institute of Science and Technology, Kattankulathur, Chennai</div>
          <div class="edu-year">2020 – 2024</div>
          <div class="edu-grade">🎓 CGPA: 8.45 / 10.0</div>
          <div class="edu-coursework">
            <strong>Relevant Coursework:</strong> Programming in C, Data Structures, Computer Networks, Embedded Systems, Python
          </div>
        </div>
        <div class="edu-card reveal">
          <div class="edu-degree">Higher Secondary Certificate (CBSE)</div>
          <div class="edu-school">Velammal Vidhyalaya, Madurai</div>
          <div class="edu-year">2019</div>
          <div class="edu-grade">📊 Score: 71%</div>
        </div>
        <div class="edu-card reveal">
          <div class="edu-degree">Secondary School Certificate — 10th (CBSE)</div>
          <div class="edu-school">Mahatma Montessori CBSE School, Madurai</div>
          <div class="edu-year">2017</div>
          <div class="edu-grade">🏅 Score: 88%</div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <div class="section-inner">
      <div class="contact-inner">
        <div class="section-label" style="justify-content:center;">05 — Contact</div>
        <h2 class="section-title reveal" style="letter-spacing:-2px;">Let's Work Together</h2>
        <p class="contact-desc reveal">
          I'm currently looking for junior developer or software developer opportunities. Whether you have a role, a project, or just want to connect — my inbox is always open.
        </p>
        <div class="contact-links reveal">
          <a href="mailto:mukeshry09@gmail.com" class="contact-link">
            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
            mukeshry09@gmail.com
          </a>
          <a href="https://github.com/Mukeshry09" target="_blank" class="contact-link">
            <svg viewBox="0 0 24 24" fill="currentColor" width="16" height="16"><path d="M12 0C5.374 0 0 5.373 0 12c0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576C20.566 21.797 24 17.3 24 12c0-6.627-5.373-12-12-12z"/></svg>
            GitHub
          </a>
          <a href="https://linkedin.com/in/mukesh-kanna-51a7b33b8/" target="_blank" class="contact-link">
            <svg viewBox="0 0 24 24" fill="currentColor" width="16" height="16"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
            LinkedIn
          </a>
        </div>
        <a href="mailto:mukeshry09@gmail.com" class="btn-primary reveal" style="display:inline-flex; margin: 0 auto;">
          Say Hello →
        </a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <div class="footer-text">Designed &amp; Built by <span>Mukesh Kanna</span></div>
    <div class="footer-text">
      <a href="https://github.com/Mukeshry09" target="_blank" style="color:inherit; text-decoration:none;">github.com/Mukeshry09</a>
    </div>
  </footer>

  <script>
    // Cursor glow
    const glow = document.getElementById('cursorGlow');
    document.addEventListener('mousemove', e => {
      glow.style.left = e.clientX + 'px';
      glow.style.top = e.clientY + 'px';
    });

    // Scroll reveal
    const reveals = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver(entries => {
      entries.forEach((entry, i) => {
        if (entry.isIntersecting) {
          setTimeout(() => {
            entry.target.classList.add('visible');
          }, i * 80);
          observer.unobserve(entry.target);
        }
      });
    }, { threshold: 0.1 });
    reveals.forEach(el => observer.observe(el));

    // Nav active state
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('.nav-links a');
    window.addEventListener('scroll', () => {
      let current = '';
      sections.forEach(s => {
        if (window.scrollY >= s.offsetTop - 120) current = s.id;
      });
      navLinks.forEach(a => {
        a.style.color = a.getAttribute('href') === '#' + current ? 'var(--accent)' : '';
      });
    });
  </script>
</body>
</html>
