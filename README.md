# niranjan-singh-website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Niranjan Singh – Powerlifter & Strength Coach | India</title>
  <meta name="description" content="Niranjan Singh is an Indian powerlifter and strength coach. Founder of Barbell Executioner." />
  <meta name="robots" content="index, follow" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0b0b0b;
      --card: #141414;
      --text: #f2f2f2;
      --muted: #b3b3b3;
      --accent: #e10600;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }
    a { color: var(--accent); text-decoration: none; }
    .container { max-width: 1100px; margin: 0 auto; padding: 4rem 1.5rem; }
    header {
      min-height: 90vh;
      display: flex;
      align-items: center;
      background: linear-gradient(180deg, #000 0%, #0b0b0b 100%);
    }
    .hero h1 {
      font-size: clamp(2.5rem, 6vw, 4rem);
      font-weight: 800;
      letter-spacing: -1px;
    }
    .hero h2 {
      margin-top: 0.5rem;
      font-size: 1.25rem;
      font-weight: 500;
      color: var(--muted);
    }
    .hero p {
      margin-top: 2rem;
      max-width: 650px;
      font-size: 1.05rem;
    }
    .cta {
      display: inline-block;
      margin-top: 2.5rem;
      padding: 0.9rem 1.8rem;
      background: var(--accent);
      color: #fff;
      font-weight: 600;
      border-radius: 6px;
    }
    section { margin-top: 4rem; }
    section h3 {
      font-size: 2rem;
      margin-bottom: 1rem;
      font-weight: 700;
    }
    .card {
      background: var(--card);
      border-radius: 10px;
      padding: 2rem;
      margin-top: 1.5rem;
    }
    .facts {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 1.2rem;
      margin-top: 1.5rem;
    }
    .fact {
      background: var(--card);
      padding: 1.5rem;
      border-radius: 8px;
    }
    .fact span {
      display: block;
      font-size: 0.85rem;
      color: var(--muted);
    }
    footer {
      border-top: 1px solid #1f1f1f;
      margin-top: 5rem;
      padding: 2rem 1.5rem;
      text-align: center;
      color: var(--muted);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

<header>
  <div class="container hero">
    <h1>Niranjan Singh</h1>
    <h2>Powerlifter & Strength Coach</h2>
    <p>
      Niranjan Singh is an Indian powerlifter and the founder of Barbell Executioner. He focuses on competition-ready powerlifting, long-term strength development, and coaching athletes for high-performance results.
    </p>
    <a class="cta" href="https://www.instagram.com/barbell_executioner" target="_blank">Follow on Instagram</a>
  </div>
</header>

<main class="container">

  <section>
    <h3>Who Is Niranjan Singh?</h3>
    <div class="card">
      <p>
        Niranjan Singh is a competitive Indian powerlifter and strength coach specializing in structured powerlifting systems. His approach is built on technical mastery, intelligent progression, and precise meet-day execution.
      </p>
      <p style="margin-top:1rem;">
        As the founder of Barbell Executioner, he coaches athletes preparing for local, state, and national-level powerlifting competitions. His work emphasizes discipline, consistency, and results-driven training.
      </p>
    </div>
  </section>

  <section>
    <h3>Quick Facts</h3>
    <div class="facts">
      <div class="fact"><strong>Name</strong><span>Niranjan Singh</span></div>
      <div class="fact"><strong>Profession</strong><span>Powerlifter & Strength Coach</span></div>
      <div class="fact"><strong>Specialization</strong><span>Competitive Powerlifting</span></div>
      <div class="fact"><strong>Founder</strong><span>Barbell Executioner</span></div>
      <div class="fact"><strong>Location</strong><span>India</span></div>
    </div>
  </section>

</main>

<footer>
  © <span id="year"></span> Niranjan Singh · Barbell Executioner
</footer>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>

</body>
</html>
