<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Priya Sharma's GitHub Profile</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron&family=Fira+Code&display=swap');

    body {
      background-color: #1e1e1e;
      color: #e0e0e0;
      font-family: 'Fira Code', monospace;
    }

    .container {
      text-align: center;
      padding: 20px;
      background-color: #2a2a2a;
      border-radius: 15px;
      box-shadow: 0 0 30px rgba(0, 242, 234, 0.7);
      position: relative;
      overflow: hidden;
    }

    .container img {
      border: 2px solid #00f2ea;
      border-radius: 10px;
      animation: floating 5s ease-in-out infinite;
    }

    .floating-circle {
      position: absolute;
      top: 50%;
      left: -50px;
      width: 100px;
      height: 100px;
      border: 2px solid #00f2ea;
      border-radius: 50%;
      animation: rotate-circle 10s linear infinite;
    }

    .floating-circle.reversed {
      top: 30%;
      right: -80px;
      width: 150px;
      height: 150px;
      border: 2px solid #f28b00;
      animation: rotate-circle 15s linear infinite reverse;
    }

    .social-links a {
      margin: 0 10px;
      transition: transform 0.3s ease;
    }

    .social-links a:hover {
      transform: scale(1.1);
    }

    .visitor-badge {
      border-radius: 5px;
      border: 1px solid #00f2ea;
      padding: 5px;
      box-shadow: 0 0 15px rgba(0, 242, 234, 0.5);
      animation: glow 2s infinite alternate;
    }

    h1 {
      font-family: 'Orbitron', sans-serif;
      color: #00f2ea;
      letter-spacing: 3px;
      text-shadow: 0 0 15px rgba(0, 242, 234, 0.8);
      animation: text-flicker 4s infinite alternate;
    }

    h3 {
      font-family: 'Fira Code', monospace;
      font-size: 1.5rem;
      color: #0ff;
      text-transform: uppercase;
      letter-spacing: 2px;
      border-bottom: 2px solid #00f2ea;
      padding-bottom: 5px;
    }

    .tech-stack img {
      height: 40px;
      margin: 5px;
    }

    .tech-stack {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      padding-top: 10px;
    }

    .github-stats {
      position: relative;
      overflow: hidden;
      padding: 30px;
    }

    .github-stats img {
      box-shadow: 0 0 15px #00f2ea;
      border-radius: 10px;
      animation: pulse 2s infinite;
    }

    .github-stats .orbit {
      position: absolute;
      bottom: -40px;
      left: 50%;
      width: 300px;
      height: 200px;
      background: radial-gradient(closest-side, rgba(0, 242, 234, 0.5), rgba(0, 242, 234, 0));
      border-radius: 50%;
      animation: orbit 5s linear infinite;
    }

    @keyframes rotate-circle {
      0% {
        transform: rotate(0deg) translateX(50px);
      }
      100% {
        transform: rotate(360deg) translateX(50px);
      }
    }

    @keyframes floating {
      0% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-10px);
      }
      100% {
        transform: translateY(0);
      }
    }

    @keyframes glow {
      0% {
        box-shadow: 0 0 15px rgba(0, 242, 234, 0.5);
      }
      100% {
        box-shadow: 0 0 30px rgba(0, 242, 234, 0.8);
      }
    }

    @keyframes text-flicker {
      0% {
        opacity: 0.9;
        text-shadow: 0 0 5px #00f2ea, 0 0 10px #00f2ea, 0 0 15px #00f2ea;
      }
      50% {
        opacity: 1;
        text-shadow: 0 0 10px #00f2ea, 0 0 20px #00f2ea, 0 0 30px #00f2ea;
      }
      100% {
        opacity: 0.9;
        text-shadow: 0 0 5px #00f2ea, 0 0 10px #00f2ea, 0 0 15px #00f2ea;
      }
    }

    @keyframes pulse {
      0% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.05);
      }
      100% {
        transform: scale(1);
      }
    }

    @keyframes orbit {
      0% {
        transform: translateX(-50%) rotate(0deg);
      }
      100% {
        transform: translateX(-50%) rotate(360deg);
      }
    }
  </style>
</head>
<body>

<div class="container">
  <img src="https://cdna.artstation.com/p/assets/images/images/025/789/352/original/pixel-jeff-galaxy-far-far-away.gif?1586928273" alt="Galaxy Background" />
  <div class="floating-circle"></div>
  <div class="floating-circle reversed"></div>
</div>

<div class="social-links">
  <a href="https://www.linkedin.com/in/priya-sharma-8453442a3/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo" />
  </a>
  <img src="https://img.shields.io/static/v1?message=@priyaa_04&logo=discord&label=&color=5137bc&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="discord logo" />
  <a href="https://www.instagram.com/sharma.priya4/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="instagram logo" />
  </a>
</div>

<div class="visitor-badge">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Priyasharma04.Priyasharma04&" alt="Visitor Badge" />
</div>

<h1>Hey! I’m Priya Sharma</h1>

<h3>👩‍💻 About Me</h3>

<p>
  <span style="color: #00f2ea;">>> Geeking Out On</span> 
  <strong style="color: #0ff; background-color: #002b36; padding: 2px 4px; border-radius: 3px;">Leveling Up My Tech Stack</strong><br><br>

  <span style="color: #f28b00;">>> Tinkering With</span> 
  <strong style="color: #ffa500; background-color: #1e1e1e; padding: 2px 4px; border-radius: 3px; border: 1px solid #f28b00;">Web Development</strong><br><br>

  <span style="color: #ff007f;">>> Orbiting Around</span> 
  <strong style="color: #ff007f; font-style: italic; background-color: #1e1e1e; padding: 2px 4px; border-radius: 3px;">My Passion for Astronomy</strong>
</p>

<h3>🛠 Language and tools</h3>

<div class="tech-stack">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain-wordmark.svg" alt="Docker logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5 logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3 logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" alt="TailwindCSS logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" alt="Vue.js logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++ logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="NumPy logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Figma logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git logo" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB logo" />
</div>

<h3>📊 Github Stats :</h3>

<div class="github-stats">
  <img src="https://streak-stats.demolab.com?user=Priyasharma04&locale=en&mode=daily&theme=dark&hide_border=false&border_radius=5&order=3" alt="GitHub Streak Stats" />
  <div class="orbit"></div>
</div>

</body>
</html>
