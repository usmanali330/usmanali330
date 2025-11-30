<!-- 🌙✨ GLOBAL DARK/LIGHT MODE + ANIMATIONS -->
<style>
/* Toggle Switch */
.theme-toggle {
  position: fixed;
  top: 15px;
  right: 20px;
  cursor: pointer;
  z-index: 999;
  background: #ffffffaa;
  padding: 8px 15px;
  border-radius: 20px;
  backdrop-filter: blur(10px);
  transition: 0.4s ease;
}
.theme-toggle:hover {
  transform: scale(1.05);
}

/* Light & Dark Themes */
:root {
  --bg: #ffffff;
  --text: #1a1a1a;
  --card-bg: #f7f7f7;
}
[data-theme="dark"] {
  --bg: #0d1117;
  --text: #e6edf3;
  --card-bg: #161b22;
}

body {
  background: var(--bg);
  color: var(--text);
  transition: background 0.4s ease, color 0.4s ease;
}

/* Waving Emoji */
.wave {
  display: inline-block;
  animation: waveAnim 1.8s infinite ease-in-out;
}
@keyframes waveAnim {
  0% { transform: rotate(0deg); }
  20% { transform: rotate(18deg); }
  40% { transform: rotate(-10deg); }
  60% { transform: rotate(10deg); }
  80% { transform: rotate(-5deg); }
  100% { transform: rotate(0deg); }
}

/* Glow Hover */
.glow:hover {
  transform: scale(1.08);
  filter: drop-shadow(0 0 10px #00eaff);
  transition: 0.35s ease-in-out;
}

/* Animated Fade-In */
.fade {
  animation: fadeIn 1.3s ease-in-out;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

/* Project Cards */
.card-grid {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
  padding: 15px;
}
.card {
  background: var(--card-bg);
  width: 280px;
  padding: 18px;
  border-radius: 15px;
  box-shadow: 0 0 15px #0002;
  transition: 0.4s ease;
  animation: fadeIn 1.5s ease;
}
.card:hover {
  transform: translateY(-8px) scale(1.03);
  box-shadow: 0 0 25px #00eaff55;
}

/* Particle Effect (CSS Only) */
.particles {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  pointer-events: none;
  background-image: radial-gradient(circle, #00eaff33 2px, transparent 3px);
  background-size: 30px 30px;
  animation: floatParticles 25s linear infinite;
  opacity: 0.2;
}
@keyframes floatParticles {
  from { transform: translateY(0); }
  to { transform: translateY(-600px); }
}
</style>

<div class="particles"></div>

<!-- Dark / Light Mode Toggle Button -->
<div class="theme-toggle" onclick="
  document.body.toggleAttribute('data-theme');
">
  🌙 / ☀️ Mode
</div>


<!-- HEADER SECTION -->
<h1 align="center" class="fade">
  <span class="wave">👋</span> Hi, I'm <span style="color:#00eaff">Usman Ali</span>
</h1>

<h3 align="center" class="fade">
  A Passionate <b>Frontend React Developer</b> from Pakistan 🇵🇰
</h3>

<br/>

<!-- QUICK INFO -->
<p align="center" class="fade">
  🔭 Working on <b style="color:#00eaff;">K2X</b> <br/>
  🌱 Learning <b style="color:#00eaff;">React JS</b> <br/>
  🤝 Looking to collaborate on <b style="color:#00eaff;">Frontend Projects</b> <br/>
  💬 Ask me about <b style="color:#00eaff;">React + Tailwind</b> <br/>
  📩 Email: <b>usmanalishah5040@gmail.com</b>
</p>

---

# 🚀 **Featured Projects (Animated Cards)**

<div class="card-grid">

  <div class="card glow">
    <h3>📱 iOS Utility Hub</h3>
    <p>Powerful iOS-style tools built with TypeScript & clean UI.</p>
  </div>

  <div class="card glow">
    <h3>🛒 Gather Grocer</h3>
    <p>Modern grocery ordering experience with animations.</p>
  </div>

  <div class="card glow">
    <h3>🌐 Usman Ali Portfolio</h3>
    <p>My official animated personal portfolio in React.</p>
  </div>

  <div class="card glow">
    <h3>🍗 KFC Website</h3>
    <p>Beautiful UI clone of KFC website using HTML/CSS.</p>
  </div>

</div>

---

# 🛠️ **Skills & Tools**
<p align="center" class="fade">
  <img class="glow"
       src="https://skillicons.dev/icons?i=html,css,js,react,tailwind,bootstrap,typescript,nodejs,php,python,java,mysql,c,cpp,cs" />
</p>

---

# 📊 **GitHub Stats**
<p align="center" class="fade">
  <img class="glow" width="48%" 
       src="https://github-readme-stats.vercel.app/api?username=usmanali330&show_icons=true&theme=tokyonight"/>
  <img class="glow" width="48%"
       src="https://github-readme-stats.vercel.app/api/top-langs/?username=usmanali330&layout=compact&theme=tokyonight"/>
</p>

<p align="center" class="fade">
  <img class="glow"
       src="https://github-readme-streak-stats.herokuapp.com/?user=usmanali330&theme=tokyonight"/>
</p>

---

# 🐍 **Snake Animation**
<div align="center" class="fade">
  <img class="glow"
       src="https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg" width="100%"/>
</div>

---

# 🎉 **Thanks for Visiting My Profile!**
<div align="center" class="fade">
  <img class="glow"
       src="https://readme-typing-svg.herokuapp.com?font=Montserrat&size=24&duration=2000&color=ff6f61&center=true&vCenter=true&lines=Keep+Coding+💻;Stay+Creative+🎨;Have+Fun+😄" />
</div>
