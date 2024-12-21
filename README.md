# Tic-Tac-Toe-Game
A simple X-O game built with HTML for fun and learning 
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>لعبة X-O</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>لعبة X-O</h1>
    <p>العب واستمتع مع أصدقائك!</p>
  </header>

  <main>
    <div class="game-board">
      <div class="cell" data-index="0"></div>
      <div class="cell" data-index="1"></div>
      <div class="cell" data-index="2"></div>
      <div class="cell" data-index="3"></div>
      <div class="cell" data-index="4"></div>
      <div class="cell" data-index="5"></div>
      <div class="cell" data-index="6"></div>
      <div class="cell" data-index="7"></div>
      <div class="cell" data-index="8"></div>
    </div>
    <button id="reset">إعادة اللعبة</button>
    <p id="status"></p>
  </main>

  <footer>
    <p>&copy; 2024 - لعبة X-O</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

