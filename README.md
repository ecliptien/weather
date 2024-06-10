
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Weather</title>
  <link rel="stylesheet" href="style.css">
</head>
<body> 
  <main>

    <div class="container">
      <h1>Météo</h1>
      <div class="search">
        <input id="searchInput" type="text" placeholder="Paris, New York, Tokyo...">
        <button id="searchButton">Rechercher</button>
      </div>

      <div class="weather-card hidden">
        <h2 id="city"></h2>
        <div class="weather">
          <img id="icon" src="" width="60">
          <span id="temp"></span>
        </div>
      </div>

    </div>

  </main>

  <script src="test.js"></script>
</body>
</html>
