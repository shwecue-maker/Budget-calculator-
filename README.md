# Budget Calculator

A simple web-based tool to calculate your monthly budget.

## Features

- Input monthly income
- Input monthly expenses
- Instant calculation of remaining budget

## Usage

To use the Budget Calculator, open `index.html` in your browser.

## Example HTML

```html
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
**B. Move Full HTML to Project File**

Create an `index.html` file and place your full HTML document there. Reference your stylesheet and script as you did.

**C. Accessibility and Best Practices**

- Add `name` attributes to your `<input>` elements.
- Consider using a `<form>` and a submit button for better accessibility and semantics.
- Use labels with `for` attributes matching input `id`.

**Example `index.html`:**
```html
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
    <form onsubmit="calculateBudget(); return false;">
      <div class="form-group">
        <label for="income">Monthly Income ($):</label>
        <input type="number" id="income" name="income" placeholder="Enter your income" required>
      </div>
      <div class="form-group">
        <label for="expenses">Monthly Expenses ($):</label>
        <input type="number" id="expenses" name="expenses" placeholder="Enter your expenses" required>
      </div>
      <button type="submit">Calculate</button>
    </form>
    <div id="result"></div>
  </div>
  <script src="script.js"></script>
</body>
</html>
