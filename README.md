<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Azucena Sierra Garcia | Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #204050;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      margin-top: 0.5rem;
      font-size: 1.2rem;
    }

    nav {
      text-align: center;
      margin: 1rem 0;
    }

    nav a {
      margin: 0 1rem;
      text-decoration: none;
      color: #204050;
      font-weight: bold;
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: 2rem 1rem;
    }

    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .project-card {
      background: white;
      padding: 1rem;
      border: 1px solid #ccc;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
    }

    footer {
      background: #204050;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Azucena Sierra Garcia</h1>
  <p>Soil Scientist | Agroecologist | Portfolio</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#portfolio">Portfolio</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Me</h2>
  <p>This is a brief description. You can introduce yourself here and describe your research, mission, or professional background.</p>
</section>

<section id="portfolio">
  <h2>Portfolio</h2>
  <div class="portfolio-grid">
    <div class="project-card">
      <h3>Project Title 1</h3>
      <p>Short description of your project or publication. Link to PDF or GitHub repo.</p>
    </div>
    <div class="project-card">
      <h3>Project Title 2</h3>
      <p>Short description of your workshop, research or blog post.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
</section>

<footer>
  <p>&copy; 2025 Azucena Sierra Garcia. All rights reserved.</p>
</footer>

</body>
</html>
