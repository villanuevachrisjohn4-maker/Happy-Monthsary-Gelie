<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>To My Favorite Nonchalant Person</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fffbea;
      color: #333;
      padding: 30px;
    }

    button {
      margin-top: 15px;
      padding: 10px 15px;
      font-size: 14px;
      cursor: pointer;
    }

    footer {
      margin-top: 30px;
      font-size: 12px;
      color: #666;
    }
  </style>
</head>

<body>

  <h2>To My Favorite Nonchalant Person ☝️</h2>

  <p>
    Happy <strong>2 months</strong> with you, my Nonchalant.<br>
    Even when you act calm and unbothered, you are my favorite person.
  </p>

  <p>
    Just like this song, everything feels brighter with you.<br>
    Thank you for choosing me every day 🤍
  </p>

  <!-- 🎵 Audio -->
  <audio id="bgMusic" loop>
    <source src="music/yellow.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <!-- 🎶 Music Button -->
  <button onclick="toggleMusic()">Pause / Play Music 🎶</button>

  <!-- 💛 Hidden Message -->
  <p id="hiddenMessage" style="display:none; margin-top:20px;">
    You're my yellow 💛
  </p>

  <button onclick="showMessage()">Click Me 💗</button>

  <footer>
    Made by your Favorite QA Person
  </footer>

  <!-- 📜 JavaScript -->
  <script>
    const music = document.getElementById("bgMusic");

    function toggleMusic() {
      if (music.paused) {
        music.play();
      } else {
        music.pause();
      }
    }

    function showMessage() {
      document.getElementById("hiddenMessage").style.display = "block";
    }
  </script>

</body>
</html>
