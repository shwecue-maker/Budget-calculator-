# Budget-calculator-
Budget calculator 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Budget Calculator</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>💰 Budget Calculator</h1>

    <div class="form-group">
      <label for="income">Monthly Income ($):</label>
      <input type="number" id="income" placeholder="Enter your income">
    </div>

    <div class="form-group">
      <label for="expenses">Monthly Expenses ($):</label>
      <input type="number" id="expenses" placeholder="Enter your expenses">
    </div>

    <button onclick="calculateBudget()">Calculate</button>

    <div id="result"></div>
  </div>

  <script src="script.js"></script>
</body>
</html>
