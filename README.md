<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Gaming Website</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Welcome to GameZone</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#games">Games</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home">
      <h2>Start Your Adventure</h2>
      <p>Discover exciting games and challenges!</p>
    </section>

    <section id="games">
      <h2>Featured Games</h2>
      <div class="game-list">
        <div class="game">
          <h3>Game 1</h3>
          <button onclick="playGame('Game 1')">Play Now</button>
        </div>
        <div class="game">
          <h3>Game 2</h3>
          <button onclick="playGame('Game 2')">Play Now</button>
        </div>
        <div class="game">
          <h3>Game 3</h3>
          <button onclick="playGame('Game 3')">Play Now</button>
        </div>
      </div>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>GameZone is the ultimate platform for online games. Play solo or with friends and enjoy hours of fun!</p>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: support@gamezone.com</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 GameZone</p>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>
