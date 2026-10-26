
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Futuristic Portfolio</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #080b16;
      color: #edf2ff;
    }
    header {
      padding: 22px 8%;
      display: flex;
      justify-content: space-between;
      border-bottom: 1px solid #263451;
    }
    a { color: #6fffe9; text-decoration: none; }
    .hero {
      padding: 90px 8%;
      min-height: 65vh;
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      justify-content: center;
      background: radial-gradient(circle at 80% 20%, #193b68, #080b16 65%);
    }
    h1 { font-size: clamp(42px, 8vw, 76px); margin: 20px 0; }
    h1 span { color: #6fffe9; }
    p { color: #a9b5d1; line-height: 1.7; }
    button {
      background: #6fffe9;
      color: #071b20;
      border: 0;
      border-radius: 8px;
      padding: 13px 20px;
      cursor: pointer;
      font-weight: bold;
    }
    .projects {
      padding: 30px 8% 70px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 18px;
    }
    .card {
      padding: 24px;
      background: #11182b;
      border: 1px solid #263451;
      border-radius: 15px;
      transition: transform .2s, border-color .2s;
    }
    .card:hover { transform: translateY(-5px); border-color: #6fffe9; }
    footer { text-align: center; padding: 25px; color: #a9b5d1; }
  </style>
</head>
<body>
  <header>
    <b>◈ YOURNAME</b>
    <a href="#projects">My Projects ↓</a>
  </header>

  <section class="hero">
    <p>WELCOME TO MY DIGITAL WORLD</p>
    <h1>Building the <span>future.</span></h1>
    <p>Student • Creator • Future Developer</p>
    <p>I turn creative ideas into useful digital experiences.</p>
    <button onclick="document.getElementById('projects').scrollIntoView({behavior:'smooth'})">
      Explore Projects
    </button>
  </section>

  <h2 style="padding: 0 8%;">Featured Projects</h2>
  <section class="projects" id="projects">
    <article class="card">
      <h3>🚀 Project Alpha</h3>
      <p>A modern productivity website.</p>
    </article>
    <article class="card">
      <h3>🌌 Project Nova</h3>
      <p>A dashboard for useful insights.</p>
    </article>
    <article class="card">
      <h3>⚡ Project Orbit</h3>
      <p>A creative web experiment.</p>
    </article>
  </section>

  <footer>© 2026 YOURNAME · Built with HTML, CSS & JavaScript</footer>
</body>
</html>
# Portfolio-
