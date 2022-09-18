<!doctype html>
<title>Пример</title>
<style>
* {
  box-sizing: border-box; 
}
body {
  margin: 0;
}
#main {
  display: flex;
  min-height: calc(100vh - 40vh);
}
#main > article {
  flex: 1;
}
#main > nav, 
#main > aside {
  flex: 0 0 20vw; 
  background: beige;
}
#main > nav {
  order: -1;
}
header, footer, article, nav, aside {
  padding: 1em; 
}
header, footer {
  background: yellowgreen;
  height: 20vh; 
}
</style>
<body>
  <header>Шапка</header>
  <div id="main">
    <article>Статья</article>
    <nav>Навигация</nav>
    <aside>Боковая панель</aside>
  </div>
  <footer>Подвал</footer>
</body>
