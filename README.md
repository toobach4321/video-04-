<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>BMI Calculator</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <div class="container">
    <h1>BMI Calculator</h1>

    <div class="toggle-theme">
      <label>
        <input type="checkbox" id="theme-toggle" />
        <span>🌙 / ☀️</span>
      </label>
    </div>

    <div class="calculator">
      <input type="number" id="weight" placeholder="Weight (kg)" />
      <input type="number" id="height" placeholder="Height (cm)" />
      <button onclick="calculateBMI()">Calculate</button>
      <div id="result"></div>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
