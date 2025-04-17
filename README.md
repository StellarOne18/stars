<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />
  <title>Галактические Новости</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }body {
  font-family: 'Orbitron', sans-serif;
  background: linear-gradient(to bottom, #000014, #020d2a);
  color: #fff;
  overflow-x: hidden;
}

header {
  background: rgba(0, 0, 50, 0.8);
  padding: 40px 0;
  text-align: center;
  border-bottom: 4px solid #0ff;
  box-shadow: 0 0 15px #0ff;
}

header h1 {
  font-size: 3em;
  color: #0ff;
  text-shadow: 0 0 10px #0ff;
}

.container {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px;
}

.intro {
  text-align: center;
  margin-bottom: 40px;
}

.intro p {
  font-size: 1.2em;
  color: #aaa;
}

.articles {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

.card {
  background: rgba(255, 255, 255, 0.05);
  border: 1px solid #0ff;
  border-radius: 15px;
  padding: 20px;
  box-shadow: 0 0 15px rgba(0, 255, 255, 0.2);
  transition: transform 0.3s;
}

.card:hover {
  transform: translateY(-10px);
  box-shadow: 0 0 20px #0ff;
}

.card h2 {
  color: #0ff;
  font-size: 1.5em;
  margin-bottom: 10px;
  .card h2 a {
  color: #0ff;
  text-decoration: none;
}

.card h2 a:hover {
  text-decoration: underline;
}

}

.card p {
  color: #ccc;
  font-size: 1em;
  line-height: 1.6em;
}

.footer {
  background: #000014;
  text-align: center;
  padding: 20px;
  font-size: 0.9em;
  color: #555;
}

.planet {
  position: fixed;
  width: 100px;
  height: 100px;
  border-radius: 50%;
  background-size: cover;
  opacity: 0.6;
  animation: spin 60s linear infinite;
}

.planet.earth {
  background-image: url('https://upload.wikimedia.org/wikipedia/commons/9/97/The_Earth_seen_from_Apollo_17.jpg');
  top: 100px;
  left: -50px;
}

.planet.jupiter {
  background-image: url('https://upload.wikimedia.org/wikipedia/commons/e/e2/Jupiter.jpg');
  bottom: 80px;
  right: -60px;
  width: 120px;
  height: 120px;
  animation-duration: 90s;
}

@keyframes spin {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

  </style>
</head>
<body>
  <header>
    <h1>Галактические Новости</h1>
  </header>  <!-- Украшения -->  <div class="planet earth"></div>
  <div class="planet jupiter"></div>  <div class="container">
    <div class="intro">
      <p>Добро пожаловать в мир космических открытий! Здесь вы найдёте самые интересные новости, статьи и факты о Вселенной.</p>
    </div><div class="articles">
  <div class="card">
    <h2><a id="myhref" href="https://stellarone18.github.io/stars/#%D0%B7%D0%B0%D0%B3%D0%B0%D0%B4%D0%BE%D1%87%D0%BD%D1%8B%D0%B5-%D1%81%D0%B8%D0%B3%D0%BD%D0%B0%D0%BB%D1%8B-%D0%B8%D0%B7-%D0%B3%D0%BB%D1%83%D0%B1%D0%B8%D0%BD-%D0%BA%D0%BE%D1%81%D0%BC%D0%BE%D1%81%D0%B0">Первые снимки с нового телескопа</a></h2>
    <p>Новый телескоп передал потрясающие изображения галактик, удалённых на миллиарды световых лет. Учёные в восторге от уровня детализации.</p>
  </div>

  <div class="card">
    <h2>Марс: подготовка к миссии</h2>
    <p>NASA и другие космические агентства продолжают активную подготовку к будущей пилотируемой миссии на Марс. Вот что уже сделано.Возможные гипотезы</p>
  </div>

  <div class="card">
    <h2>Загадочные сигналы из глубин космоса</h2>
    <p>Астрономы снова зафиксировали серии быстрых радиовсплесков (FRB), происхождение которых до сих пор остаётся неизвестным.</p>
  </div>

  <div class="card">
    <h2>Экзопланета с атмосферой</h2>
    <p>Учёные обнаружили экзопланету с потенциально пригодной для жизни атмосферой. Это открытие может изменить поиски жизни за пределами Земли.</p>
  </div>
</div>
<div class="card">
    <h2>Космические аппараты</h2>
    <p>Космические миссии,исследование и новые открытии.</p>
  </div>
</div>

  </div>  <div class="footer">
    &copy; 2025 Галактические Новости | Все права защищены
  </div>
</body>
</html>
