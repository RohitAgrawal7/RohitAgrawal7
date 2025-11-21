<!-- Header with 3D Animated Text -->
<div align="center">

<!-- Animated 3D Header -->
<div style="perspective: 1000px;">
  <h1 style="
    font-size: 4rem;
    background: linear-gradient(45deg, #ff6b6b, #4ecdc4, #45b7d1, #96ceb4, #ffeaa7);
    background-size: 400% 400%;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: gradientShift 3s ease infinite, float3D 6s ease-in-out infinite;
    text-shadow: 0 10px 20px rgba(0,0,0,0.1);
    transform-style: preserve-3d;
    margin-bottom: 0;
  ">Hi 👋, I'm Rohit M Agrawal</h1>
</div>

<!-- Animated Subtitle -->
<h3 style="
  font-size: 1.8rem;
  color: #58a6ff;
  animation: typewriter 4s steps(40) 1s both, blink 1s infinite;
  border-right: 3px solid #58a6ff;
  white-space: nowrap;
  overflow: hidden;
  margin: 1rem auto;
  width: fit-content;
">A passionate Frontend Developer from India</h3>

<!-- 3D Animated Profile Stats -->
<div style="
  display: flex;
  justify-content: center;
  gap: 2rem;
  margin: 2rem 0;
  flex-wrap: wrap;
">

<!-- Profile Views Counter -->
<div style="
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  padding: 1rem 2rem;
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  transform-style: preserve-3d;
  animation: floatCard 4s ease-in-out infinite;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='rotateY(10deg) scale(1.05)'" 
onmouseout="this.style.transform='rotateY(0deg) scale(1)'">
  <p style="margin: 0; color: white; font-weight: bold;">
    <img src="https://komarev.com/ghpvc/?username=rohitagrawal7&label=Profile%20Views&color=0e75b6&style=flat" alt="rohitagrawal7" />
  </p>
</div>

<!-- GitHub Stars -->
<div style="
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
  padding: 1rem 2rem;
  border-radius: 20px;
  box-shadow: 0 10px 30px rgba(0,0,0,0.2);
  transform-style: preserve-3d;
  animation: floatCard 4s ease-in-out infinite 0.5s;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='rotateY(-10deg) scale(1.05)'" 
onmouseout="this.style.transform='rotateY(0deg) scale(1)'">
  <p style="margin: 0; color: white; font-weight: bold;">
    ⭐ 50+ Projects
  </p>
</div>

</div>

</div>

<br />

<!-- 3D Animated Main Content -->
<div style="
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 2rem;
  perspective: 1000px;
">

<!-- Left Column -->
<div>

<!-- Current Focus with 3D Card -->
<div style="
  background: rgba(255,255,255,0.1);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 2rem;
  margin-bottom: 2rem;
  border: 1px solid rgba(255,255,255,0.2);
  transform-style: preserve-3d;
  animation: slideInLeft 1s ease-out;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='translateZ(20px) rotateX(5deg)'" 
onmouseout="this.style.transform='translateZ(0px) rotateX(0deg)'">

<h2 style="color: #58a6ff; margin-top: 0;">🚀 Current Focus</h2>
<div style="display: flex; align-items: center; gap: 1rem; margin-bottom: 1rem;">
  <div style="
    width: 50px;
    height: 50px;
    background: linear-gradient(45deg, #ff6b6b, #4ecdc4);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: rotate 4s linear infinite;
  ">⚡</div>
  <div>
    <p style="margin: 0; font-weight: bold; color: #c9d1d9;">Advanced JavaScript</p>
    <p style="margin: 0; font-size: 0.9rem; color: #8b949e;">Mastering Modern ES6+ Features</p>
  </div>
</div>

<div style="display: flex; align-items: center; gap: 1rem;">
  <div style="
    width: 50px;
    height: 50px;
    background: linear-gradient(45deg, #4ecdc4, #44a08d);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    animation: rotate 4s linear infinite reverse;
  ">🎨</div>
  <div>
    <p style="margin: 0; font-weight: bold; color: #c9d1d9;">React Ecosystem</p>
    <p style="margin: 0; font-size: 0.9rem; color: #8b949e;">Next.js, Redux, Testing</p>
  </div>
</div>

</div>

<!-- Tech Stack with Animated Icons -->
<div style="
  background: rgba(255,255,255,0.1);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 2rem;
  border: 1px solid rgba(255,255,255,0.2);
  animation: slideInLeft 1s ease-out 0.2s both;
">

<h2 style="color: #58a6ff; margin-top: 0;">🛠 Tech Stack</h2>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 1rem;">

<!-- Frontend -->
<div style="text-align: center;">
  <div style="
    width: 60px;
    height: 60px;
    background: linear-gradient(135deg, #667eea, #764ba2);
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 0.5rem;
    animation: bounce 2s infinite;
  ">🎨</div>
  <p style="margin: 0; font-size: 0.8rem; color: #c9d1d9;">Frontend</p>
</div>

<!-- Backend -->
<div style="text-align: center;">
  <div style="
    width: 60px;
    height: 60px;
    background: linear-gradient(135deg, #f093fb, #f5576c);
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 0.5rem;
    animation: bounce 2s infinite 0.2s;
  ">⚙️</div>
  <p style="margin: 0; font-size: 0.8rem; color: #c9d1d9;">Backend</p>
</div>

<!-- Database -->
<div style="text-align: center;">
  <div style="
    width: 60px;
    height: 60px;
    background: linear-gradient(135deg, #4facfe, #00f2fe);
    border-radius: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 auto 0.5rem;
    animation: bounce 2s infinite 0.4s;
  ">🗄️</div>
  <p style="margin: 0; font-size: 0.8rem; color: #c9d1d9;">Database</p>
</div>

</div>

</div>

</div>

<!-- Right Column -->
<div>

<!-- 3D Contact Card -->
<div style="
  background: rgba(255,255,255,0.1);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 2rem;
  margin-bottom: 2rem;
  border: 1px solid rgba(255,255,255,0.2);
  transform-style: preserve-3d;
  animation: slideInRight 1s ease-out;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='translateZ(20px) rotateX(-5deg)'" 
onmouseout="this.style.transform='translateZ(0px) rotateX(0deg)'">

<h2 style="color: #58a6ff; margin-top: 0;">📫 Connect With Me</h2>

<div style="display: flex; gap: 1rem; justify-content: center; flex-wrap: wrap;">

<!-- LinkedIn -->
<a href="https://www.linkedin.com/in/rohitagrawal07/" target="_blank" style="
  display: inline-block;
  padding: 0.8rem 1.5rem;
  background: linear-gradient(135deg, #0077b5, #00a0dc);
  color: white;
  text-decoration: none;
  border-radius: 25px;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
  animation: pulse 2s infinite;
" onmouseover="this.style.transform='translateZ(10px) scale(1.1)'" 
onmouseout="this.style.transform='translateZ(0px) scale(1)'">
  💼 LinkedIn
</a>

<!-- HackerRank -->
<a href="https://www.hackerrank.com/rohitmagrawal7" target="_blank" style="
  display: inline-block;
  padding: 0.8rem 1.5rem;
  background: linear-gradient(135deg, #2ec866, #1ba94c);
  color: white;
  text-decoration: none;
  border-radius: 25px;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
  animation: pulse 2s infinite 0.5s;
" onmouseover="this.style.transform='translateZ(10px) scale(1.1)'" 
onmouseout="this.style.transform='translateZ(0px) scale(1)'">
  ⚡ HackerRank
</a>

<!-- Email -->
<a href="mailto:rohitmagrawal7@gmail.com" style="
  display: inline-block;
  padding: 0.8rem 1.5rem;
  background: linear-gradient(135deg, #ea4335, #d14836);
  color: white;
  text-decoration: none;
  border-radius: 25px;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
  animation: pulse 2s infinite 1s;
" onmouseover="this.style.transform='translateZ(10px) scale(1.1)'" 
onmouseout="this.style.transform='translateZ(0px) scale(1)'">
  📧 Email
</a>

</div>

</div>

<!-- Skills Radar -->
<div style="
  background: rgba(255,255,255,0.1);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 2rem;
  border: 1px solid rgba(255,255,255,0.2);
  animation: slideInRight 1s ease-out 0.2s both;
">

<h2 style="color: #58a6ff; margin-top: 0;">📊 Skills Radar</h2>

<div style="display: grid; grid-template-columns: repeat(2, 1fr); gap: 1rem;">

<div>
  <p style="margin: 0.5rem 0; color: #c9d1d9;">JavaScript</p>
  <div style="background: rgba(255,255,255,0.1); border-radius: 10px; overflow: hidden;">
    <div style="width: 90%; background: linear-gradient(90deg, #f7df1e, #ffeb3b); height: 8px; border-radius: 10px; animation: fillBar 2s ease-out;"></div>
  </div>
</div>

<div>
  <p style="margin: 0.5rem 0; color: #c9d1d9;">React</p>
  <div style="background: rgba(255,255,255,0.1); border-radius: 10px; overflow: hidden;">
    <div style="width: 85%; background: linear-gradient(90deg, #61dafb, #21a9c7); height: 8px; border-radius: 10px; animation: fillBar 2s ease-out 0.2s both;"></div>
  </div>
</div>

<div>
  <p style="margin: 0.5rem 0; color: #c9d1d9;">CSS/SCSS</p>
  <div style="background: rgba(255,255,255,0.1); border-radius: 10px; overflow: hidden;">
    <div style="width: 88%; background: linear-gradient(90deg, #1572b6, #33a9dc); height: 8px; border-radius: 10px; animation: fillBar 2s ease-out 0.4s both;"></div>
  </div>
</div>

<div>
  <p style="margin: 0.5rem 0; color: #c9d1d9;">Node.js</p>
  <div style="background: rgba(255,255,255,0.1); border-radius: 10px; overflow: hidden;">
    <div style="width: 75%; background: linear-gradient(90deg, #339933, #66cc33); height: 8px; border-radius: 10px; animation: fillBar 2s ease-out 0.6s both;"></div>
  </div>
</div>

</div>

</div>

</div>

</div>

<br />

<!-- 3D Animated GitHub Stats -->
<div align="center" style="perspective: 1000px;">

<h2 style="color: #58a6ff; margin-bottom: 2rem;">📈 GitHub Analytics</h2>

<div style="display: flex; justify-content: center; gap: 2rem; flex-wrap: wrap;">

<!-- GitHub Stats -->
<div style="
  transform-style: preserve-3d;
  animation: float3D 6s ease-in-out infinite;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='rotateY(15deg) scale(1.05)'" 
onmouseout="this.style.transform='rotateY(0deg) scale(1)'">
  <img src="https://github-readme-stats.vercel.app/api?username=rohitagrawal7&show_icons=true&theme=radical&bg_color=0d1117&hide_border=true" alt="rohitagrawal7" />
</div>

<!-- Top Languages -->
<div style="
  transform-style: preserve-3d;
  animation: float3D 6s ease-in-out infinite 0.5s;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='rotateY(-15deg) scale(1.05)'" 
onmouseout="this.style.transform='rotateY(0deg) scale(1)'">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rohitagrawal7&layout=compact&theme=radical&bg_color=0d1117&hide_border=true" alt="rohitagrawal7" />
</div>

</div>

<!-- Streak Stats -->
<div style="
  margin-top: 2rem;
  transform-style: preserve-3d;
  animation: float3D 6s ease-in-out infinite 1s;
  transition: all 0.3s ease;
" onmouseover="this.style.transform='rotateX(10deg) scale(1.02)'" 
onmouseout="this.style.transform='rotateX(0deg) scale(1)'">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rohitagrawal7&theme=radical&background=0d1117&hide_border=true" alt="rohitagrawal7" />
</div>

</div>

<br />

<!-- Tools & Technologies Grid -->
<div align="center">

<h2 style="color: #58a6ff; margin-bottom: 2rem;">🛠 Languages & Tools</h2>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(80px, 1fr)); gap: 1.5rem; max-width: 800px; margin: 0 auto;">

<!-- Tool Items with 3D Hover -->
<a href="https://aws.amazon.com" target="_blank" style="
  display: flex;
  flex-direction: column;
  align-items: center;
  text-decoration: none;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
" onmouseover="this.style.transform='translateZ(20px) rotateY(10deg)'" 
onmouseout="this.style.transform='translateZ(0px) rotateY(0deg)'">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="50" height="50" style="filter: drop-shadow(0 5px 15px rgba(0,0,0,0.3));" />
  <span style="color: #c9d1d9; font-size: 0.8rem; margin-top: 0.5rem;">AWS</span>
</a>

<a href="https://reactjs.org/" target="_blank" style="
  display: flex;
  flex-direction: column;
  align-items: center;
  text-decoration: none;
  transition: all 0.3s ease;
  transform-style: preserve-3d;
" onmouseover="this.style.transform='translateZ(20px) rotateY(10deg)'" 
onmouseout="this.style.transform='translateZ(0px) rotateY(0deg)'">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="50" height="50" style="filter: drop-shadow(0 5px 15px rgba(0,0,0,0.3));" />
  <span style="color: #c9d1d9; font-size: 0.8rem; margin-top: 0.5rem;">React</span>
</a>

<!-- Add more tools with same structure -->

</div>

</div>

<br />

<!-- Footer with Animated Text -->
<div align="center" style="
  padding: 2rem;
  background: linear-gradient(135deg, rgba(88,166,255,0.1), rgba(255,107,107,0.1));
  border-radius: 20px;
  margin-top: 2rem;
">

<p style="
  color: #58a6ff;
  font-size: 1.2rem;
  animation: glow 2s ease-in-out infinite alternate;
">💻 Turning ideas into interactive experiences</p>

<p style="color: #8b949e;">
  ⚡ <strong>Fun Fact:</strong> I can center a div with my eyes closed! 😄
</p>

</div>

<!-- CSS Animations -->
<style>
@keyframes gradientShift {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

@keyframes float3D {
  0%, 100% { transform: translateY(0px) rotateX(0deg); }
  50% { transform: translateY(-10px) rotateX(5deg); }
}

@keyframes typewriter {
  from { width: 0; }
  to { width: 100%; }
}

@keyframes blink {
  0%, 50% { border-color: #58a6ff; }
  51%, 100% { border-color: transparent; }
}

@keyframes floatCard {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-5px); }
}

@keyframes slideInLeft {
  from { transform: translateX(-50px); opacity: 0; }
  to { transform: translateX(0); opacity: 1; }
}

@keyframes slideInRight {
  from { transform: translateX(50px); opacity: 0; }
  to { transform: translateX(0); opacity: 1; }
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}

@keyframes pulse {
  0%, 100% { transform: scale(1); }
  50% { transform: scale(1.05); }
}

@keyframes fillBar {
  from { width: 0%; }
}

@keyframes glow {
  from { text-shadow: 0 0 5px #58a6ff; }
  to { text-shadow: 0 0 20px #58a6ff, 0 0 30px #58a6ff; }
}

/* Smooth scrolling and better performance */
html {
  scroll-behavior: smooth;
}

* {
  box-sizing: border-box;
}

/* Responsive design */
@media (max-width: 768px) {
  .grid-container {
    grid-template-columns: 1fr;
  }
  
  h1 {
    font-size: 2.5rem !important;
  }
}
</style>

<!-- JavaScript for interactive elements (Note: GitHub doesn't execute JS in README) -->
<!-- This is just for demonstration purposes -->
<script>
// This script won't run on GitHub, but it shows the intended interactivity
document.addEventListener('DOMContentLoaded', function() {
  const elements = document.querySelectorAll('[data-animate]');
  elements.forEach(el => {
    el.style.opacity = '0';
    el.style.transform = 'translateY(30px)';
  });
});
</script>
