# Birds-site
birds-site/
├── index.html          ← Всё о птицах
├── passeriformes.html  ← Воробьинообразные
├── piciformes.html     ← Дятлообразные
├── anseriformes.html   ← Гусеобразные
└── style.css
body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.6;
  margin: 0;
  padding: 0;
  background-color: #f8f9fa;
  color: #111;
}

header {
  background: linear-gradient(to right, #1e3a8a, #3b82f6);
  color: white;
  padding: 2rem;
  text-align: center;
}

nav {
  background: #1e40af;
  padding: 1rem;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 1.2rem;
  text-decoration: none;
  font-weight: bold;
  transition: 0.2s;
}

nav a:hover {
  color: #bbf7d0;
  text-decoration: underline;
}

main {
  max-width: 900px;
  margin: 2rem auto;
  padding: 0 1.5rem;
}

h1, h2 {
  color: #1e40af;
}

.bird-group {
  background: white;
  padding: 1.5rem;
  margin: 1.5rem 0;
  border-radius: 10px;
  box-shadow: 0 3px 10px rgba(0,0,0,0.08);
}

footer {
  background: #1e293b;
  color: #94a3b8;
  text-align: center;
  padding: 1.5rem;
  margin-top: 3rem;
}
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Птицы — Всё о птицах</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Птицы — удивительный мир пернатых</h1>
</header>

<nav>
  <a href="index.html">Всё о птицах</a>
  <a href="passeriformes.html">Воробьинообразные</a>
  <a href="piciformes.html">Дятлообразные</a>
  <a href="anseriformes.html">Гусеобразные</a>
</nav>

<main>

  <section class="bird-group">
    <h2>Кто такие птицы?</h2>
    <p>Птицы (Aves) — класс теплокровных позвоночных животных, единственная современная группа, у которой развиты перья, клюв без зубов и способность к полёту (у большинства видов).</p>
  </section>

  <section class="bird-group">
    <h2>Основные признаки птиц</h2>
    <ul>
      <li>Перья (единственные животные с настоящими перьями)</li>
      <li>Клюв без зубов</li>
      <li>Передние конечности превращены в крылья</li>
      <li>Задние конечности — лапы (обычно 4 пальца)</li>
      <li>Высокий метаболизм и температура тела ~40–42 °C</li>
      <li>Лёгкие + воздушные мешки → эффективное дыхание</li>
      <li>Отсутствие мочевого пузыря (экономия веса)</li>
      <li>Яйца с твёрдой скорлупой</li>
    </ul>
  </section>

  <section class="bird-group">
    <h2>Сколько видов существует?</h2>
    <p>На 2025–2026 год описано ≈ <strong>11 000</strong> современных видов птиц.<br>
    Это больше, чем видов млекопитающих (~6 500).</p>
  </section>

</main>

<footer>
  © 2026 — Сайт о птицах • Сделано для любителей пернатых
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Воробьинообразные (Passeriformes)</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Воробьинообразные</h1>
</header>

<nav>
  <a href="index.html">Всё о птицах</a>
  <a href="passeriformes.html">Воробьинообразные</a>
  <a href="piciformes.html">Дятлообразные</a>
  <a href="anseriformes.html">Гусеобразные</a>
</nav>

<main>

  <section class="bird-group">
    <h2>Самый большой отряд птиц</h2>
    <p>Воробьинообразные (Passeriformes) — это более <strong>6 500 видов</strong> ≈ 60% всех современных птиц.</p>
  </section>

  <section class="bird-group">
    <h2>Характерные признаки</h2>
    <ul>
      <li>Ноги с четырьмя пальцами (3 вперёд + 1 назад)</li>
      <li>Сложная песня (развитый голосовой аппарат — сиринкс)</li>
      <li>Очень разнообразное питание</li>
      <li>Маленькие и средние размеры (от 6,5 см до ~1 кг)</li>
    </ul>
  </section>

  <section class="bird-group">
    <h2>Известные представители</h2>
    <ul>
      <li>Воробей домовый</li>
      <li>Синица большая</li>
      <li>Соловей обыкновенный</li>
      <li>Ворона серая / ворон</li>
      <li>Скворец обыкновенный</li>
      <li>Ласточка деревенская</li>
      <li>Жаворонок полевой</li>
      <li>Щегол</li>
      <li>Канарейка</li>
      <li>Грач</li>
    </ul>
  </section>

</main>

<footer>
  © 2026 — Сайт о птицах
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Дятлообразные (Piciformes)</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Дятлообразные</h1>
</header>

<nav>
  <a href="index.html">Всё о птицах</a>
  <a href="passeriformes.html">Воробьинообразные</a>
  <a href="piciformes.html">Дятлообразные</a>
  <a href="anseriformes.html">Гусеобразные</a>
</nav>

<main>

  <section class="bird-group">
    <h2>Особенности дятлов</h2>
    <p>Отряд Piciformes включает около 450 видов, большинство из которых — дятлы.</p>
  </section>

  <section class="bird-group">
    <h2>Суперспособности дятла</h2>
    <ul>
      <li>Мозг защищён специальной губчатой костью и особой жидкостью</li>
      <li>Язык очень длинный (у некоторых длиннее тела), обёрнут вокруг черепа</li>
      <li>Крепкий клюв и жёсткий хвост-опора</li>
      <li>Могут стучать со скоростью до 20 ударов в секунду</li>
      <li>Сила удара ≈ 1000 g (человек бы потерял сознание)</li>
    </ul>
  </section>

  <section class="bird-group">
    <h2>Представители</h2>
    <ul>
      <li>Дятел большой пёстрый</li>
      <li>Дятел чёрный (желна)</li>
      <li>Дятел зелёный</li>
      <li>Дятел трёхпалый</li>
      <li>Вертинка</li>
      <li>Тукан (в тропиках)</li>
      <li>Якамара</li>
    </ul>
  </section>

</main>

<footer>
  © 2026 — Сайт о птицах
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Гусеобразные (Anseriformes)</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
  <h1>Гусеобразные</h1>
</header>

<nav>
  <a href="index.html">Всё о птицах</a>
  <a href="passeriformes.html">Воробьинообразные</a>
  <a href="piciformes.html">Дятлообразные</a>
  <a href="anseriformes.html">Гусеобразные</a>
</nav>

<main>

  <section class="bird-group">
    <h2>Водоплавающие «крикуны»</h2>
    <p>Отряд Anseriformes — утки, гуси, лебеди и несколько экзотических видов (≈ 180 видов).</p>
  </section>

  <section class="bird-group">
    <h2>Характерные черты</h2>
    <ul>
      <li>Пластинчатый клюв с роговыми пластинками (фильтрация у уток)</li>
      <li>Перепончатые лапы</li>
      <li>Копчиковая железа → водоотталкивающий секрет</li>
      <li>Многие виды совершают дальние перелёты</li>
    </ul>
  </section>

  <section class="bird-group">
    <h2>Популярные виды</h2>
    <ul>
      <li>Лебедь-кликун</li>
      <li>Лебедь-шипун</li>
      <li>Гусь серый / гуменник</li>
      <li>Кряква</li>
      <li>Чирок-свистунок</li>
      <li>Огарь</li>
      <li>Пеганка</li>
      <li>Гоголь</li>
      <li>Казарка канадская</li>
    </ul>
  </section>

</main>

<footer>
  © 2026 — Сайт о птицах
</footer>

</body>
</html>
