<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dastin Design Studio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Inter', sans-serif;
      background: #0a0a0a;
      color: #fff;
      overflow-x: hidden;
    }
    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3rem;
      font-weight: 600;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.2rem;
      font-weight: 300;
      max-width: 600px;
    }
    .projects {
      padding: 80px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 40px;
      background: #111;
    }
    .project-card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 10px;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: scale(1.05);
    }
    .project-card h3 {
      font-size: 1.1rem;
      margin-bottom: 10px;
    }
    .project-card p {
      font-size: 0.9rem;
      color: #ccc;
    }
    footer {
      text-align: center;
      padding: 40px 20px;
      font-size: 0.8rem;
      color: #777;
      background: #0a0a0a;
    }
  </style>
</head>
<body>
  <header>
    <h1>Dastin Design Studio</h1>
    <p>Exploring creative futures through design, interaction and immersive technologies.</p>
  </header>

  <section class="projects">
    <div class="project-card">
      <h3>Project One</h3>
      <p>A future-forward interface experiment with motion and 3D space.</p>
    </div>
    <div class="project-card">
      <h3>Project Two</h3>
      <p>An immersive portfolio that blends narrative, visuals and sound.</p>
    </div>
    <div class="project-card">
      <h3>Project Three</h3>
      <p>AI-assisted concept tool for creative collaborations in digital design.</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Dastin Design Studio — All rights reserved.
  </footer>
</body>
</html>
