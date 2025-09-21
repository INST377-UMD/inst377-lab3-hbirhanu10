[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/LXHgsJqg)
# INST377-Lab

# Name: Hiyaw BIrhanu

# Comments: 

index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Rock Paper Scissors</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="band">
    <h1>Rock Paper Scissors</h1>
  </header>

  <nav class="top-nav">
    <ul>
      <li><a href="https://www.rpsgame.org/" target="_blank">Play Online</a></li>
      <li><a href="https://en.wikipedia.org/wiki/Rock_paper_scissors" target="_blank">History</a></li>
      <li><a href="https://www.worldrps.com/" target="_blank">World RPS</a></li>
    </ul>
  </nav>


  <section class="content-row">
    <main class="main">
      <h2>Play the Game</h2>
      <form>
        <label for="playerName">Name:</label>
        <input type="text" id="playerName" name="playerName" placeholder="Enter your name" required>

        <label for="move">Choose your move:</label>
        <select id="move" name="move">
          <option value="rock">Rock</option>
          <option value="paper">Paper</option>
          <option value="scissors">Scissors</option>
        </select>

        <button type="submit">Submit</button>
      </form>
    </main>

    <aside class="sidebar">
      <h3>Rules</h3>
      <ol>
        <li>Rock beats Scissors</li>
        <li>Scissors beat Paper</li>
        <li>Paper beats Rock</li>
        <li>Same move = Tie</li>
      </ol>
    </aside>
  </section>

  <footer class="band">
    <p>&copy; 2025 INST377 - Lab 3</p>
  </footer>
</body>
</html>






styles.css 

.band {
  background-color: rgb(225, 173, 173);
  text-align: center;
  margin: 10px;
  padding: 10px;
}


.top-nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 20px;
  padding: 0;
}

.top-nav a {
  text-decoration: none;
  color: black;
}

.top-nav a:hover {
  color: blue;
}

.content-row {
  display: flex;
  gap: 10px;
}

.main {
  width: 70%;
  background-color: #dfe7d2;
  margin: 5px;
  padding: 10px;
}

.sidebar {
  width: 30%;
  background-color: #d74545;
  margin: 5px;
  padding: 10px;
}

.sidebar:hover {
  background-color: #bbb;
}

input[type="text"] {
  width: 60%;
  transition: width 0.3s;
}

input[type="text"]:focus {
  width: 90%;
}

