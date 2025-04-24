<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SDG 8: Decent Work & Economic Growth</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #8A1538;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .impact {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2rem;
      margin-top: 2rem;
    }
    .impact img {
      width: 100%;
      border-radius: 10px;
    }
    .interactive {
      margin-top: 3rem;
      background: #fff;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }
    button {
      padding: 0.8rem 1.2rem;
      font-size: 1rem;
      background-color: #8A1538;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    button:hover {
      background-color: #a92a4f;
    }
    .output {
      margin-top: 1rem;
      font-weight: 600;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #222;
      color: #fff;
    }
  </style>
</head>

<body>
  <header>
    <h1>🌍 SDG 8: Decent Work & Economic Growth</h1>
    <p>Empowering people through inclusive and sustainable economic growth 💼📈</p>
  </header>

  <section>
    <h2>Why It Matters</h2>
    <p>SDG 8 focuses on promoting inclusive and sustainable economic growth, employment, and decent work for all. Economic development is crucial to reducing poverty, improving health, and ensuring equality.</p>
    <div class="impact">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/SDG8-icon.png" alt="SDG 8 Icon">
      <div>
        <h3>Impact on Global Development 🌐</h3>
        <ul>
          <li>Boosts productivity and technological innovation</li>
          <li>Reduces unemployment and underemployment</li>
          <li>Encourages entrepreneurship and fair trade</li>
          <li>Improves living standards across nations</li>
        </ul>
      </div>
    </div>
  </section>

  <section class="interactive">
    <h2>🌟 Interactive Insight</h2>
    <p>Click below to see how SDG 8 can impact a sector of development:</p>
    <button onclick="showImpact()">Show Impact</button>
    <p class="output" id="impactOutput"></p>
  </section>

  <footer>
    <p>Created to raise awareness about SDG 8 🌎</p>
  </footer>

  <script>
    const impacts = [
      "Increased jobs in green energy 💡",
      "Support for women-led businesses 👩‍💼",
      "Better access to youth training programs 🎓",
      "Digital transformation and tech innovation 💻",
      "Resilient economies post-COVID-19 🏥"
    ];

    function showImpact() {
      const output = document.getElementById('impactOutput');
      const randomIndex = Math.floor(Math.random() * impacts.length);
      output.textContent = impacts[randomIndex];
    }
  </script>
</body>

</html>
