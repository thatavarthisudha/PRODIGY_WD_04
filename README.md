# PRODIGY_WD_04
<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sudha Thatavarthi - Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
    };
  </script>
  <style>
    .fade-in {
      animation: fadeIn 1s ease-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .skill-bar {
      width: 0;
      transition: width 2s ease;
    }
    .glow:hover {
      box-shadow: 0 0 15px rgba(255, 255, 255, 0.5);
    }
    .tab-btn.active {
      background: linear-gradient(to right, #7F00FF, #E100FF);
      color: white !important;
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans">
<header class="text-center py-10 fade-in">
  <img src="https://static.vecteezy.com/system/resources/previews/000/604/630/original/letter-s-logo-technology-logo-design-concept-template-vector.jpg" alt="Sudha Logo" class="w-24 h-24 mx-auto rounded-full shadow-lg mb-4 border-4 border-purple-500" />
  <h1 class="text-5xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 via-pink-500 to-red-500">
    Sudha Thatavarthi
  </h1>
  <p class="text-lg mt-3 text-gray-300">Aspiring Tech Professional</p>
  <p class="text-sm text-gray-400">JavaScript • HTML • CSS • Python Basics</p>
</header>
  <section class="max-w-4xl mx-auto px-4 fade-in">
    <div class="flex justify-center gap-3 mb-6">
      <button onclick="showTab('education', this)" class="tab-btn bg-purple-700 px-4 py-2 rounded hover:scale-105 glow transition active">Education</button>
      <button onclick="showTab('experience', this)" class="tab-btn bg-pink-700 px-4 py-2 rounded hover:scale-105 glow transition">Experience</button>
      <button onclick="showTab('goals', this)" class="tab-btn bg-red-700 px-4 py-2 rounded hover:scale-105 glow transition">Goals</button>
    </div>

    <div id="education" class="tab-content bg-gray-800 p-6 rounded-lg shadow-lg">
      <h2 class="text-2xl font-bold text-purple-400 mb-2">🎓 Education</h2>
      <p class="text-lg">JNTUK Kakinada - B.Tech (Jan 2022 - Dec 2026)</p>
      <p class="text-sm text-gray-400">Pursuing B,TECH in Electronics and  Comunication Engineering.</p>
</div>
 <div id="education" class="tab-content bg-gray-800 p-6 rounded-lg shadow-lg">
      <p class="text-lg">Sri Chaithanya Junior College- Intermediate (2020-2022)</p>
<p class="text-sm text-gray-400">In the Stream of M.P.C.</p>
</div>
 <div id="education" class="tab-content bg-gray-800 p-6 rounded-lg shadow-lg">
<p class="text-lg">Pragati Little Public School- Secondary School (2019-2020)</p>
</div>
    <div id="experience" class="tab-content hidden bg-gray-800 p-6 rounded-lg shadow-lg">
      <h2 class="text-2xl font-bold text-pink-400 mb-2">💼 Internship</h2>
      <p class="text-lg">BHEL – May 2024</p>
      <p class="text-sm text-gray-400">One-month hands-on training at Bharat Heavy Electricals Limited.</p>
    </div>

    <div id="goals" class="tab-content hidden bg-gray-800 p-6 rounded-lg shadow-lg">
      <h2 class="text-2xl font-bold text-red-400 mb-2">🚀 Career Goals</h2>
      <p class="text-lg">To become a full-stack developer and contribute to real-world tech innovations.</p>
    </div>
  </section>
  <section class="max-w-4xl mx-auto mt-10 px-4 fade-in">
    <h2 class="text-3xl font-bold text-center bg-gradient-to-r from-green-400 to-blue-500 bg-clip-text text-transparent mb-6">🛠️ Skills</h2>
    <div class="space-y-5">
      <div>
        <p>JavaScript</p>
        <div class="h-4 bg-gray-700 rounded">
          <div class="skill-bar h-4 rounded bg-gradient-to-r from-yellow-400 to-yellow-600" data-skill="60%"></div>
        </div>
      </div>
      <div>
        <p>HTML</p>
        <div class="h-4 bg-gray-700 rounded">
          <div class="skill-bar h-4 rounded bg-gradient-to-r from-pink-500 to-pink-700" data-skill="90%"></div>
        </div>
      </div>
      <div>
        <p>CSS</p>
        <div class="h-4 bg-gray-700 rounded">
          <div class="skill-bar h-4 rounded bg-gradient-to-r from-indigo-400 to-indigo-600" data-skill="80%"></div>
        </div>
      </div>
      <div>
        <p>Python (Basics)</p>
        <div class="h-4 bg-gray-700 rounded">
          <div class="skill-bar h-4 rounded bg-gradient-to-r from-green-400 to-green-600" data-skill="40%"></div>
        </div>
      </div>
    </div>
  </section>
  <section class="max-w-4xl mx-auto mt-12 px-4 fade-in">
    <h2 class="text-3xl font-bold text-center text-orange-400 mb-4">📜 Certifications</h2>
    <ul class="list-disc list-inside text-gray-300 space-y-2">
      <li>CSS Certificate - HackerRank</li>
      <li>JavaScript Essentials 1</li>
      <li>HTML5 & CSS3 - Infosys Springboard</li>
      <li>TCS ION - Career Edge: Young Professional</li>
    </ul>
  </section>
  <section id="contact" class="max-w-4xl mx-auto mt-12 px-4 fade-in">
    <h2 class="text-3xl font-bold text-center text-cyan-400 mb-4">📬 Contact</h2>
    <div class="bg-gray-800 p-6 rounded-lg text-center shadow-lg">
      <p>Email: <a href="mailto:thatavarthisudha8@gmail.com" class="text-blue-400 underline">thatavarthisudha8@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/sudhathatavarthi" target="_blank" class="text-blue-400 underline">linkedin.com/in/sudhathatavarthi</a></p>
    </div>
  </section>
  <footer class="text-center text-sm text-gray-500 py-8 mt-10">
    © 2025 Sudha Thatavarthi. All rights reserved.
  </footer>
  <script>
    // Tab control
    function showTab(id, btn) {
      const contents = document.querySelectorAll('.tab-content');
      const buttons = document.querySelectorAll('.tab-btn');
      contents.forEach(c => c.classList.add('hidden'));
      document.getElementById(id).classList.remove('hidden');
      buttons.forEach(b => b.classList.remove('active'));
      btn.classList.add('active');
    }
    window.addEventListener('DOMContentLoaded', () => {
      document.querySelectorAll('.skill-bar').forEach(bar => {
        const level = bar.getAttribute('data-skill');
        setTimeout(() => bar.style.width = level, 300);
      });
    });
  </script>
</body>
</html>
