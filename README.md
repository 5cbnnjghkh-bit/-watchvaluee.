<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WatchValue.it | Le migliori offerte di orologi su Vinted</title>

  <!-- Font eleganti -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    :root {
      --gold: #d4af37;
      --gold-light: #f0d87a;
      --dark: #050505;
      --card: rgba(20, 20, 20, 0.92);
      --text: #ffffff;
      --muted: #c9c9c9;
      --border: rgba(212, 175, 55, 0.18);
    }

    body {
      font-family: "Inter", sans-serif;
      color: var(--text);
      background: #000;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
    }

    /* HERO */
    .hero {
      min-height: 100vh;
      background:
        linear-gradient(rgba(0,0,0,0.72), rgba(0,0,0,0.82)),
        url("https://images.unsplash.com/photo-1523170335258-f5ed11844a49?auto=format&fit=crop&w=1600&q=80");
      background-size: cover;
      background-position: center;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 30px 20px;
    }

    .hero-content {
      max-width: 850px;
    }

    .hero h1 {
      font-family: "Playfair Display", serif;
      font-size: 4.5rem;
      margin-bottom: 20px;
      letter-spacing: 1px;
    }

    .hero h1 span {
      color: var(--gold);
    }

    .hero p {
      font-size: 1.25rem;
      color: #e5e5e5;
      margin-bottom: 35px;
    }

    .btn-main {
      display: inline-block;
      background: var(--gold);
      color: #000;
      padding: 14px 34px;
      border-radius: 999px;
      font-weight: 700;
      box-shadow: 0 10px 30px rgba(212,175,55,0.25);
      transition: 0.25s;
    }

    .btn-main:hover {
      background: var(--gold-light);
      transform: translateY(-2px);
    }

    /* SECTION */
    .section {
      max-width: 1300px;
      margin: auto;
      padding: 80px 20px;
    }

    .section-title {
      font-family: "Playfair Display", serif;
      font-size: 3rem;
      text-align: center;
      margin-bottom: 10px;
    }

    .section-subtitle {
      text-align: center;
      color: var(--muted);
      margin-bottom: 50px;
    }

    /* GRID */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 30px;
    }

    /* CARD */
    .card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 20px;
      overflow: hidden;
      backdrop-filter: blur(8px);
      box-shadow: 0 20px 50px rgba(0,0,0,0.45);
      transition: transform 0.3s ease, border-color 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
      border-color: rgba(212,175,55,0.45);
    }

    .card img {
      width: 100%;
      height: 260px;
      object-fit: cover;
      display: block;
    }

    .card-content {
      padding: 24px;
    }

    .brand {
      color: var(--gold);
      font-size: 0.75rem;
      font-weight: 700;
      letter-spacing: 1.5px;
      text-transform: uppercase;
      margin-bottom: 8px;
    }

    .card h3 {
      font-size: 1.4rem;
      margin-bottom: 12px;
      line-height: 1.3;
    }

    .description {
      color: var(--muted);
      font-size: 0.95rem;
      margin-bottom: 20px;
    }

    .btn {
      display: block;
      text-align: center;
      background: var(--gold);
      color: #000;
      padding: 14px;
      border-radius: 10px;
      font-weight: 700;
      transition: 0.25s;
    }

    .btn:hover {
      background: var(--gold-light);
    }

    /* FOOTER */
    footer {
      text-align: center;
      color: #777;
      padding: 35px 20px;
      border-top: 1px solid #1d1d1d;
      background: #050505;
    }

    /* MOBILE */
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 2.8rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .section-title {
        font-size: 2.2rem;
      }
    }
  </style>
</head>
<body>

  <!-- HERO -->
  <section class="hero">
    <div class="hero-content">
      <h1>Watch<span>Value</span>.it</h1>
      <p>
        Le migliori offerte di MoonSwatch, Seiko, Tissot e Omega trovate su Vinted.
      </p>
      <a href="#offerte" class="btn-main">Scopri le offerte</a>
    </div>
  </section>

  <!-- OFFERTE -->
  <section class="section" id="offerte">
    <h2 class="section-title">Offerte del Giorno</h2>
    <p class="section-subtitle">
      Annunci selezionati manualmente e aggiornati ogni giorno.
    </p>

    <div class="grid">

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=Omega+De+Ville" alt="Omega De Ville">
        <div class="card-content">
          <div class="brand">Omega</div>
          <h3>Omega De Ville</h3>
          <p class="description">Elegante dress watch classico.</p>
          <a class="btn" href="https://www.vinted.it/items/8951164292-orologio-da-uomo-de-ville" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=Ruzza+Watch" alt="Ruzza Watch">
        <div class="card-content">
          <div class="brand">Watch</div>
          <h3>Ruzza Watch</h3>
          <p class="description">Design sportivo e moderno.</p>
          <a class="btn" href="https://www.vinted.it/items/8925173854-ruzza-watch" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=Omega" alt="Omega">
        <div class="card-content">
          <div class="brand">Omega</div>
          <h3>Omega</h3>
          <p class="description">Modello Omega in ottime condizioni.</p>
          <a class="btn" href="https://www.vinted.it/items/8950474935-uaireadoiri-omega" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=Orologio+di+Lusso" alt="Orologio di Lusso">
        <div class="card-content">
          <div class="brand">Luxury</div>
          <h3>Orologio di Lusso</h3>
          <p class="description">Design elegante e raffinato.</p>
          <a class="btn" href="https://www.vinted.it/items/8950352668-orologio-di-lusso" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=Omega+Black" alt="Omega Black">
        <div class="card-content">
          <div class="brand">Omega</div>
          <h3>Omega Black</h3>
          <p class="description">Look total black moderno.</p>
          <a class="btn" href="https://www.vinted.it/items/8950800657-iwotshi-ye-omega-black" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=Seiko+Mod+Daytona+Panda" alt="Seiko Mod Daytona Panda">
        <div class="card-content">
          <div class="brand">Seiko Mod</div>
          <h3>Daytona Panda</h3>
          <p class="description">Uno dei modelli più richiesti.</p>
          <a class="btn" href="https://www.vinted.it/items/8941728695-seiko-mod-daytona-panda" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

      <article class="card">
        <img src="https://via.placeholder.com/800x500?text=GS+Mod+Datejust+36mm" alt="GS Mod Datejust 36mm">
        <div class="card-content">
          <div class="brand">GS Mod</div>
          <h3>Datejust 36mm</h3>
          <p class="description">Movimento NH35 e cassa 904L.</p>
          <a class="btn" href="https://www.vinted.it/items/8949349801-gs-mod-datejust-36mm-nh35-904l-bleu" target="_blank">Vai all'annuncio</a>
        </div>
      </article>

    </div>
  </section>

  <footer>
    © 2025 WatchValue.it — Selezione indipendente di offerte trovate su Vinted.
  </footer>

</body>
</html>