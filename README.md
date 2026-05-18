# -watchvaluee.
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

header {

  background: linear-gradient(to right, #000, #111);

  padding: 60px 20px;

  text-align: center;

}

header h1 {

  font-size: 48px;

  color: #d4af37;

}

header p {

  margin-top: 10px;

  color: #cccccc;

  font-size: 18px;

}

.container {

  max-width: 1200px;

  margin: auto;

  padding: 40px 20px;

}

.grid {

  display: grid;

  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));

  gap: 30px;

}

.card {

  background: #151515;

  border: 1px solid #2a2a2a;

  border-radius: 16px;

  overflow: hidden;

}

.card img {

  width: 100%;

  height: 250px;

  object-fit: cover;

}

.card-content {

  padding: 20px;

}

.brand {

  color: #d4af37;

  font-size: 12px;

  text-transform: uppercase;

  font-weight: bold;

}

.card h2 {

  margin: 10px 0;

  font-size: 24px;

}

.price {

  font-size: 32px;

  color: #d4af37;

  font-weight: bold;

  margin: 10px 0;

}

.description {

  color: #cccccc;

  margin-bottom: 20px;

}

.btn {

  display: block;

  text-align: center;

  background: #d4af37;

  color: black;

  text-decoration: none;

  padding: 14px;

  border-radius: 8px;

  font-weight: bold;

}

footer {

  text-align: center;

  color: #777;

  padding: 40px 20px;

}

</style>

</head>

<body>

<header>

  <h1>WatchValue.it</h1>

  <p>Le migliori offerte di orologi su Vinted</p>

</header>

<div class="container">

  <div class="grid">

    <div class="card">

      <img src="https://via.placeholder.com/600x400?text=MoonSwatch" alt="MoonSwatch">

      <div class="card-content">

        <div class="brand">MoonSwatch</div>

        <h2>Mission to Mercury</h2>

        <div class="price">220 €</div>

        <p class="description">Originale con scatola e documenti.</p>

        <a class="btn" href="https://www.vinted.it" target="_blank">

          Vai all'annuncio

        </a>

      </div>

    </div>

    <div class="card">

      <img src="https://via.placeholder.com/600x400?text=Seiko+5" alt="Seiko 5">

      <div class="card-content">

        <div class="brand">Seiko</div>

        <h2>Seiko 5 Automatic</h2>

        <div class="price">95 €</div>

        <p class="description">Ottimo entry level automatico.</p>

        <a class="btn" href="https://www.vinted.it" target="_blank">

          Vai all'annuncio

        </a>

      </div>

    </div>

    <div class="card">

      <img src="https://via.placeholder.com/600x400?text=Tissot+PRX" alt="Tissot PRX">

      <div class="card-content">

        <div class="brand">Tissot</div>

        <h2>Tissot PRX Quartz</h2>

        <div class="price">260 €</div>

        <p class="description">Prezzo molto interessante.</p>

        <a class="btn" href="https://www.vinted.it" target="_blank">

          Vai all'annuncio

        </a>

      </div>

    </div>

  </div>

</div>

<footer>

  © 2025 WatchValue.it

</footer>

</body>

</html>