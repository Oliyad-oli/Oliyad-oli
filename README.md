<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Oliad Dandena - Portfolio</title>
  
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  
  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Animate.css for animations -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
  
  <style>
    /* Custom gradient text */
    .gradient-text {
      background: linear-gradient(90deg, #00c6ff, #0072ff);
      -webkit-background-clip: text;
      color: transparent;
    }
    /* Footer animation */
    #thanks {
      font-size: 2rem;
      font-weight: bold;
      background: linear-gradient(90deg,#f7971e,#ffd200);
      -webkit-background-clip: text;
      color: transparent;
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-800">

  <!-- Welcome Animation -->
  <div class="text-center py-20">
    <h1 class="text-5xl font-bold animate__animated animate__fadeInDown">👋 Welcome to my Portfolio!</h1>
    <p class="text-xl mt-4 animate__animated animate__fadeInUp animate__delay-1s">Hi, I'm <span class="gradient-text">Oliad Dandena</span></p>
  </div>

  <div class="container mx-auto px-4">

    <!-- About Me -->
    <section class="my-12 animate__animated animate__fadeInUp">
      <h2 class="text-3xl font-bold mb-4">⚡ About Me</h2>
      <p>Hey! I'm <strong>Oliad</strong>, a passionate <strong>Full-Stack Developer</strong> who loves turning ideas into real working applications.<br>
         I enjoy building beautiful UIs, powerful backends, and fun projects.<br>
         Also… I’m a little bit funny 😄 — code may fail but <strong>I never fail to fix it</strong> 😉.</p>
    </section>

    <!-- Skills -->
    <section class="my-12 animate__animated animate__fadeInUp animate__delay-1s">
      <h2 class="text-3xl font-bold mb-4">🛠️ Skills</h2>

      <h4 class="text-xl font-semibold mt-4">Frontend</h4>
      <p>
        <img src="https://img.shields.io/badge/HTML-FF5733?logo=html5&logoColor=white" />
        <img src="https://img.shields.io/badge/CSS-264de4?logo=css3&logoColor=white" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black" />
        <img src="https://img.shields.io/badge/React-61DBFB?logo=react&logoColor=black" />
      </p>

      <h4 class="text-xl font-semibold mt-4">Backend</h4>
      <p>
        <img src="https://img.shields.io/badge/Node.js-3C873A?logo=node.js&logoColor=white" />
        <img src="https://img.shields.io/badge/Express.js-black?logo=express&logoColor=white" />
        <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Java-007396?logo=java&logoColor=white" />
      </p>

      <h4 class="text-xl font-semibold mt-4">Database</h4>
      <p>
        <img src="https://img.shields.io/badge/MySQL-046089?logo=mysql&logoColor=white" />
        <img src="https://img.shields.io/badge/MongoDB-4EA94B?logo=mongodb&logoColor=white" />
      </p>

      <h4 class="text-xl font-semibold mt-4">Other Skills</h4>
      <p>
        <img src="https://img.shields.io/badge/UI%2FUX-FF61F6?logo=figma&logoColor=white" />
        <img src="https://img.shields.io/badge/Full--Stack_Developer-blueviolet" />
      </p>
    </section>

    <!-- Featured Project -->
    <section class="my-12 animate__animated animate__fadeInUp animate__delay-2s">
      <h2 class="text-3xl font-bold mb-4">🚀 Featured Project</h2>
      <h4 class="text-xl font-semibold">📊 CryptoTracker System</h4>
      <ul class="list-disc ml-6">
        <li>Live market data</li>
        <li>Interactive charts</li>
        <li>Beautiful UI</li>
        <li>Fast performance</li>
      </ul>
      <p class="mt-2 text-gray-700 italic">Project coming soon…</p>
    </section>

    <!-- GitHub Stats -->
    <section class="my-12 animate__animated animate__fadeInUp animate__delay-3s text-center">
      <h2 class="text-3xl font-bold mb-4">📈 GitHub Stats</h2>
      <div class="flex flex-col md:flex-row justify-center gap-4">
        <img height="150" src="https://github-readme-stats.vercel.app/api?username=oliyad-oli&show_icons=true&theme=tokyonight" />
        <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=oliyad-oli&layout=compact&theme=tokyonight" />
      </div>
    </section>

    <!-- Fun Facts -->
    <section class="my-12 animate__animated animate__fadeInUp animate__delay-4s">
      <h2 class="text-3xl font-bold mb-4">😎 Fun Facts</h2>
      <ul class="list-disc ml-6">
        <li>I fix bugs faster when I drink coffee ☕</li>
        <li>I talk to my code like it can hear me 🤣</li>
        <li>My projects look amazing… after the 99th version 👍</li>
      </ul>
    </section>

    <!-- Contact -->
    <section class="my-12 animate__animated animate__fadeInUp animate__delay-5s">
      <h2 class="text-3xl font-bold mb-4">📫 Contact Me</h2>
      <p>📧 Email: <a href="mailto:oliyaddandana@gmail.com" class="text-blue-600 underline">oliyaddandana@gmail.com</a></p>
      <p>💼 Portfolio: <a href="https://oliyad-oli.github.io/mypersonal-portfolio/" target="_blank" class="text-blue-600 underline">coming soon…</a></p>
    </section>

    <!-- Thanks Animation -->
    <section class="text-center py-12 animate__animated animate__fadeInUp animate__delay-6s">
      <h2 id="thanks" class="animate__animated animate__pulse animate__infinite">✨ Thanks for Watching! ✨</h2>
    </section>

  </div>

  <!-- Bootstrap JS -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
