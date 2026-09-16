<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gold Shop — Standoff 2</title>

<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #090b10;
  color: white;
}

.container {
  max-width: 1000px;
  margin: auto;
  padding: 25px;
}

header {
  text-align: center;
  padding: 50px 10px;
}

h1 {
  font-size: 42px;
  margin: 0 0 10px;
}

h1 span {
  color: #ffd43b;
}

.subtitle {
  color: #aeb4c0;
  font-size: 18px;
}

.shop {
  background: #12151d;
  border: 1px solid #292e3a;
  border-radius: 25px;
  padding: 30px;
}

.shop h2 {
  text-align: center;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(210px, 1fr));
  gap: 18px;
  margin-top: 25px;
}

.card {
  background: #191d27;
  border: 1px solid #303644;
  border-radius: 18px;
  padding: 25px;
  text-align: center;
}

.gold {
  color: #ffd43b;
  font-size: 27px;
  font-weight: bold;
}

.price {
  font-size: 22px;
  margin: 15px 0 20px;
}

.btn {
  display: inline-block;
  padding: 12px 25px;
  background: #ffd43b;
  color: #111;
  text-decoration: none;
  border-radius: 12px;
  font-weight: bold;
}

.btn:hover {
  opacity: 0.85;
}

footer {
  text-align: center;
  color: #777;
  margin-top: 30px;
}
</style>
</head>

<body>

<div class="container">

<header>
  <h1>🪙 <span>Gold Shop</span></h1>
  <div class="subtitle">Продаж Gold для Standoff 2</div>
</header>

<section class="shop">

<h2>💰 Обери пакет Gold</h2>

<div class="cards">

<div class="card">
  <div class="gold">100 Gold</div>
  <div class="price">50 грн</div>
  <a class="btn" href="https://t.me/" target="_blank">Замовити</a>
</div>

<div class="card">
  <div class="gold">500 Gold</div>
  <div class="price">200 грн</div>
  <a class="btn" href="https://t.me/" target="_blank">Замовити</a>
</div>

<div class="card">
  <div class="gold">1000 Gold</div>
  <div class="price">350 грн</div>
  <a class="btn" href="https://t.me/" target="_blank">Замовити</a>
</div>

</div>

</section>

<footer>
© 2026 Gold Shop • Standoff 2
</footer>

</div>

</body>
</html>
