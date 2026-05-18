# -watchvaluee.
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WatchValue.it | Le migliori offerte di orologi</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background: #0b0b0b;
      color: #ffffff;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
    }

    /* HEADER */
    header {
      background: linear-gradient(135deg, #0b0b0b, #1c1c1c);
      padding: 60px 20px 40px;
      text-align: center;
      border-bottom: 1px solid #222;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 700;
      letter-spacing: 1px;
      margin-bottom: 10px;
    }

    header h1 span {
      color: #d4af37; /* oro */
    }

    header p {
      color: #b5b5b5;
      max-width: 700px;
      margin: 0 auto;
      font-size: 1.1rem;
    }

    /* CONTAINER */
    .container {
      max-width: 1200px;
      margin: auto;
      padding: 50px 20px;
    }

    /* FILTRI */
    .filters {
      display: flex;
      gap: 12px;
      justify-content: center;
      flex-wrap: wrap;
      margin-bottom: 40px;
    }

    .filter-btn {
      background: #1a1a1a;
      border: 1px solid #333;
      color: #fff;
      padding: 10px 18px;
      border-radius: 999px;
      cursor: pointer;
    }

    .filter-btn:hover {
      border-color: #d4af37;
      color: #d4af37;
    }

    /* GRID */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 30px;
    }

    /* CARD */
    .card {
      background: #151515;
      border: 1px solid #222;
      border-radius: 18px;
      overflow: hidden;
      box-shadow: 0 10px 30px rgba(0,0,0,0.35);
      transition: transform 0.25s ease, border-color 0.25s ease;
    }

    .card:hover {
      transform: translateY(-6px);
      border-color: #d4af37;
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
      display: inline-block;
      font-size: 0.8rem;
      color: #d4af37;
      font-weight: 700;
      letter-spacing: 1px;
      text-transform: uppercase;
      margin-bottom: 10px;
    }

    .card h2 {
      font-size: 1.4rem;
      margin-bottom: 12px;
      color: #ffffff;
    }

    .price {
      font-size: 2rem;
      font-weight: 700;
      color: #d4af37;
      margin-bottom: 12px;
    }

    .description {
      color: #b5b5b5;
      margin-bottom: 20px;
      font-size: 0.95rem;
    }

    .btn {
      display: inline-block;
      width: 100%;
      text-align: center;
      padding: 14px 20px;
      background: #d4af37;
      color: #000;
      font-weight: 700;
      border-radius: 10px;
      transition: background 0.2s ease;
    }

    .btn:hover {
      background: #e7c55a;
    }

    /* FOOTER */
    footer {
      text-align: center;
      color: #777;
      padding: 40px 20px;
      border-top: 1px solid #222;
      margin-top: 50px;
      font-size: 0.9rem;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }

      .card img {
        height: 220px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Watch<span>Value</span>.it</h1>
    <p>
      Le migliori offerte di MoonSwatch, Seiko e Tissot trovate su Vinted.
      Aggiornato ogni giorno.
    </p>
  </header>

  <main class="container">

    <div class="filters">
      <button class="filter-btn">MoonSwatch</button>
      <button class="filter-btn">Seiko</button>
      <button class="filter-btn">Tissot</button>
    </div>

    <section class="grid">

      <!-- CARD 1 -->
      <article class="card">
        <img src="https://via.placeholder.com/600x400?text=MoonSwatch" alt="MoonSwatch Mission to Mercury">
        <div class="card-content">
          <span class="brand">MoonSwatch</span>
          <h2>Mission to Mercury</h2>
          <p class="price">220 €</p>
          <p class="description">
            Originale con scatola e documenti. Prezzo molto interessante.
          </p>
          <a class="btn"
             href="https://www.vinted.it"
             target="_blank"
             rel="noopener noreferrer">
            Vai all'annuncio
          </a>
        </div>
      </article>

      <!-- CARD 2 -->
      <article class="card">
        <img src="https://via.placeholder.com/600x400?text=Seiko+5" alt="Seiko 5 Automatic">
        <div class="card-content">
          <span class="brand">Seiko</span>
          <h2>Seiko 5 Automatic</h2>
          <p class="price">95 €</p>
          <p class="description">
            Ottimo entry level automatico in condizioni eccellenti.
          </p>
          <a class="btn"
             href="https://www.vinted.it"
             target="_blank"
             rel="noopener noreferrer">
            Vai all'annuncio
          </a>
        </div>
      </article>

      <!-- CARD 3 -->
      <article class="card">
        <img src="https://via.placeholder.com/600x400?text=Tissot+PRX" alt="Tissot PRX">
        <div class="card-content">
          <span class="brand">Tissot</span>
          <h2>Tissot PRX Quartz</h2>
          <p class="price">260 €</p>
          <p class="description">
            Ottimo prezzo per un modello molto richiesto.
          </p>
          <a class="btn"
             href="https://www.vinted.it"
             target="_blank"
             rel="noopener noreferrer">
            Vai all'annuncio
          </a>
        </div>
      </article>

    </section>
  </main>

  <footer>
    © 2025 WatchValue.it — Selezione indipendente di offerte trovate su Vinted.
  </footer>

</body>
</html>