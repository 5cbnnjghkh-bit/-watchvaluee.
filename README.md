<!-- INCOLLA QUESTO CODICE AL POSTO DEL TUO index.html -->

<!DOCTYPE html>

<html lang="it">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>WatchValue.it</title>

  <style>

    * {

      margin: 0;

      padding: 0;

      box-sizing: border-box;

    }

    body {

      font-family: Arial, sans-serif;

      background: #0a0a0a;

      color: white;

    }

    /* HERO */

    .hero {

      min-height: 100vh;

      background:

        linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.75)),

        url("https://images.unsplash.com/photo-1523170335258-f5ed11844a49?auto=format&fit=crop&w=1600&q=80");

      background-size: cover;

      background-position: center;

      display: flex;

      align-items: center;

      justify-content: center;

      text-align: center;

      padding: 20px;

    }

    .hero-content {

      max-width: 800px;

    }

    .hero h1 {

      font-size: 64px;

      color: white;

      margin-bottom: 20px;

      font-family: Georgia, serif;

    }

    .hero h1 span {

      color: #d4af37;

    }

    .hero p {

      font-size: 22px;

      color: #dddddd;

      margin-bottom: 30px;

    }

    .btn-main {

      display: inline-block;

      background: #d4af37;

      color: black;

      padding: 14px 30px;

      border-radius: 50px;

      text-decoration: none;

      font-weight: bold;

    }

    /* SECTION */

    .container {

      max-width: 1200px;

      margin: auto;

      padding: 60px 20px;

    }

    .section-title {

      text-align: center;

      font-size: 42px;

      margin-bottom: 40px;

      color: #d4af37;

      font-family: Georgia, serif;

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

      border-radius: 16px;

      overflow: hidden;

      border: 1px solid #2a2a2a;

      box-shadow: 0 10px 30px rgba(0,0,0,0.4);

    }

    .card img {

      width: 100%;

      height: 240px;

      object-fit: cover;

    }

    .card-content {

      padding: 20px;

    }

    .card h3 {

      font-size: 24px;

      margin-bottom: 10px;

    }

    .card p {

      color: #bdbdbd;

      margin-bottom: 20px;

    }

    .card a {

      display: block;

      text-align: center;

      background: #d4af37;

      color: black;

      text-decoration: none;

      padding: 12px;

      border-radius: 8px;

      font-weight: bold;

    }

    footer {

      text-align: center;

      color: #777;

      padding: 40px 20px;

      border-top: 1px solid #222;

    }

    @media (max-width: 768px) {

      .hero h1 {

        font-size: 42px;

      }

      .hero p {

        font-size: 18px;

      }

    }

  </style>

</head>

<body>

  <!-- HERO -->

  <section class="hero">

    <div class="hero-content">

      <h1>Watch<span>Value</span>.it</h1>

      <p>Le migliori offerte di orologi su Vinted.</p>

      <a href="#offerte" class="btn-main">Scopri le offerte</a>

    </div>

  </section>

  <!-- OFFERTE -->

  <section class="container" id="offerte">

    <h2 class="section-title">Offerte del Giorno</h2>

    <div class="grid">

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=Omega+De+Ville" alt="Omega De Ville">

        <div class="card-content">

          <h3>Omega De Ville</h3>

          <p>Elegante dress watch classico.</p>

          <a href="https://www.vinted.it/items/8951164292-orologio-da-uomo-de-ville" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=Ruzza+Watch" alt="Ruzza Watch">

        <div class="card-content">

          <h3>Ruzza Watch</h3>

          <p>Orologio dal design sportivo.</p>

          <a href="https://www.vinted.it/items/8925173854-ruzza-watch" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=Omega" alt="Omega">

        <div class="card-content">

          <h3>Omega</h3>

          <p>Modello Omega in ottime condizioni.</p>

          <a href="https://www.vinted.it/items/8950474935-uaireadoiri-omega" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=Orologio+di+Lusso" alt="Orologio di Lusso">

        <div class="card-content">

          <h3>Orologio di Lusso</h3>

          <p>Design elegante e raffinato.</p>

          <a href="https://www.vinted.it/items/8950352668-orologio-di-lusso" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=Omega+Black" alt="Omega Black">

        <div class="card-content">

          <h3>Omega Black</h3>

          <p>Look total black moderno.</p>

          <a href="https://www.vinted.it/items/8950800657-iwotshi-ye-omega-black" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=Seiko+Mod+Daytona+Panda" alt="Seiko Mod Daytona Panda">

        <div class="card-content">

          <h3>Seiko Mod Daytona Panda</h3>

          <p>Uno dei modelli più richiesti.</p>

          <a href="https://www.vinted.it/items/8941728695-seiko-mod-daytona-panda" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

      <div class="card">

        <img src="https://via.placeholder.com/600x400?text=GS+Mod+Datejust" alt="GS Mod Datejust 36mm">

        <div class="card-content">

          <h3>GS Mod Datejust 36mm</h3>

          <p>Movimento NH35 e cassa 904L.</p>

          <a href="https://www.vinted.it/items/8949349801-gs-mod-datejust-36mm-nh35-904l-bleu" target="_blank">Vai all'annuncio</a>

        </div>

      </div>

    </div>

  </section>

  <footer>

    © 2025 WatchValue.it — Le migliori offerte di orologi su Vinted.

  </footer>

</body>

</html>