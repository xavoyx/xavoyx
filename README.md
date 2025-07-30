<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Xavo – Entwickler & Discord-Profi</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root {
      --bg: #0e0e10;
      --bg-light: #1c1c21;
      --primary: #61dafb;
      --accent: #7289da;
      --text: #e4e4e4;
      --card-radius: 16px;
      --shadow: 0 10px 30px rgba(0,0,0,0.3);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: var(--primary);
      text-decoration: none;
      transition: color 0.3s;
    }

    a:hover {
      color: #fff;
    }

    .container {
      width: 90%;
      max-width: 1100px;
      margin: 0 auto;
      padding: 3rem 0;
    }

    header {
      text-align: center;
      padding: 4rem 0;
    }

    header h1 {
      font-size: 3rem;
      font-weight: 800;
      color: var(--primary);
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
    }

    .card {
      background: var(--bg-light);
      border-radius: var(--card-radius);
      padding: 2rem;
      box-shadow: var(--shadow);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 20px 40px rgba(97, 218, 251, 0.15);
    }

    .section {
      margin-bottom: 4rem;
    }

    .section-title {
      font-size: 2rem;
      font-weight: 600;
      margin-bottom: 1.5rem;
      border-left: 6px solid var(--primary);
      padding-left: 1rem;
    }

    .stats-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 2rem;
      justify-content: center;
    }

    .stats-grid img {
      border-radius: 10px;
      max-width: 100%;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .stats-grid img:hover {
      transform: scale(1.02);
      box-shadow: 0 0 15px rgba(97, 218, 251, 0.2);
    }

    footer {
      text-align: center;
      padding: 3rem 0;
      font-size: 0.9rem;
      color: #666;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2.2rem;
      }

      .section-title {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>

  <header class="container">
    <h1>Hey, ich bin Xavo 👋</h1>
    <p>Fullstack Entwickler · Discord-Bot Entwickler · Open Source Enthusiast</p>
  </header>

  <main class="container">

    <section class="section">
      <h2 class="section-title">Discord Status</h2>
      <div class="card" style="text-align:center;">
        <a href="https://discord.com/users/1314991090616766564" target="_blank">
          <img src="https://lanyard.cnrad.dev/api/1314991090616766564" alt="Xavo Discord Presence">
        </a>
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">GitHub Stats</h2>
      <div class="stats-grid">
        <img src="https://github-readme-stats.vercel.app/api?username=xavoyx&theme=blueberry&show_icons=true&hide_border=true&count_private=true" alt="GitHub Stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=xavoyx&theme=blueberry&show_icons=true&hide_border=false&layout=compact" alt="Top Languages">
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">Über mich</h2>
      <div class="card">
        <p>Ich bin ein kreativer und engagierter Entwickler mit Fokus auf moderne Webtechnologien, Discord-Bots, APIs und UI/UX. Ich liebe es, Projekte von der Idee bis zur Umsetzung zu begleiten und innovative Lösungen zu bauen.</p>
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">Projekte</h2>
      <div class="card">
        <p>Bald findest du hier eine Übersicht meiner besten Open Source Repositories und Live-Demos.</p>
        <p>👉 <a href="https://github.com/xavoyx" target="_blank">Besuche mein GitHub-Profil</a></p>
      </div>
    </section>

  </main>

  <footer>
    &copy; 2025 Xavo · Made with 💙
  </footer>

</body>
</html>
