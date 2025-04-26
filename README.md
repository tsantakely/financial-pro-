# financial-pro-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Finance Trainer - Accounting Basics</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom, #d4f5e9, #ffffff);
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background-color: #1f7a4d;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #2e8b57;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
      animation: fadeIn 1.5s ease-in;
    }
    section {
      margin-bottom: 3rem;
    }
    h1, h2 {
      color: #1f7a4d;
    }
    button {
      background-color: #1f7a4d;
      color: white;
      padding: 0.8rem 1.5rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-size: 1rem;
      transition: background-color 0.3s;
    }
    button:hover {
      background-color: #145c35;
    }
    .quiz, .case-study {
      background-color: #f0fdf7;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      padding: 2rem;
      font-size: 0.9rem;
      color: gray;
    }
    @keyframes fadeIn {
      from {opacity: 0;}
      to {opacity: 1;}
    }
  </style>
</head>
<body>

<header>
  <h1>Welcome to Finance Trainer</h1>
  <p>Master 80% of Accounting Basics to Analyze Investments!</p>
</header>

<nav>
  <a href="#basics">Accounting Basics</a>
  <a href="#indicators">Key Indicators</a>
  <a href="#case">Case Studies</a>
  <a href="#quiz">Quiz</a>
</nav>

<main>
  
  <section id="basics">
    <h2>📚 Accounting Basics</h2>
    <p>Learn how to read the 3 fundamental financial statements:</p>
    <ul>
      <li><strong>Profit & Loss (P&L)</strong> — measures profitability</li>
      <li><strong>Balance Sheet</strong> — snapshot of assets, liabilities, equity</li>
      <li><strong>Free Cash Flow (FCF)</strong> — real cash left after operations and investments</li>
    </ul>
  </section>

  <section id="indicators">
    <h2>📊 Key Financial Indicators</h2>
    <ul>
      <li><strong>EBIT</strong> (Earnings Before Interest and Taxes): measures operating profit.</li>
      <li><strong>EBITDA</strong> (EBIT + Depreciation & Amortization): adds non-cash expenses back.</li>
      <li><strong>FCF</strong> (Free Cash Flow): cash available to investors.</li>
      <li><strong>DCF</strong> (Discounted Cash Flow): present value of expected future cash flows.</li>
    </ul>
    <button onclick="alert('Tip: Higher FCF is usually a very positive signal for investors! 🚀')">Pro Tip</button>
  </section>

  <section id="case" class="case-study">
    <h2>📚 Case Studies</h2>
    <h3>Airbus SE</h3>
    <p>Analyze Airbus 2023 financial statements: focus on EBIT margin and Order Backlog growth 📈.</p>
    <h3>L'Oréal Group</h3>
    <p>Look at L'Oréal's EBITDA vs Net Income growth to assess operational efficiency 💄.</p>
  </section>

  <section id="quiz" class="quiz">
    <h2>📝 Quick Quiz</h2>
    <p><strong>Q1:</strong> What does a strong Free Cash Flow (FCF) indicate?</p>
    <button onclick="alert('✅ Correct! It shows financial health and ability to invest or pay dividends.')">Good Cash Generation</button>
    <button onclick="alert('❌ Not exactly. Try again!')">High Debt</button>
    <button onclick="alert('❌ Nope! Try again.')">Low Revenue</button>
  </section>

</main>

<footer>
  Built with ❤️ by Your Name | Finance Training 2025
</footer>

</body>
</html>
