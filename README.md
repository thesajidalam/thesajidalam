<div class="cyber-container">
  <!-- Holographic Header -->
  <header class="neon-header">
    <h1 class="glitch" data-text="SAJID ALAM">SAJID ALAM</h1>
    <div class="particles" id="particles-js"></div>
    <h2 class="typewriter">Creative Technologist | IoT Enthusiast | Linux Explorer</h2>
    <div class="pulse-ring"></div>
  </header>

  <!-- Bio Section with Animated Grid -->
  <section class="quantum-bio">
    <div class="bio-grid">
      <div class="grid-cell" style="--delay: 0.1s">
        <div class="hologram-card">
          <h3>🧑‍💻 Digital Architect</h3>
          <p>Building bridges between silicon and human experience since 2015</p>
        </div>
      </div>
      <div class="grid-cell" style="--delay: 0.3s">
        <div class="hologram-card">
          <h3>🌐 Network Nomad</h3>
          <p>Navigating the data streams from embedded systems to cloud clusters</p>
        </div>
      </div>
      <div class="grid-cell" style="--delay: 0.5s">
        <div class="hologram-card">
          <h3>🔮 Interface Alchemist</h3>
          <p>Transforming raw code into golden user experiences</p>
        </div>
      </div>
    </div>
    
    <div class="dna-helix">
      <div class="node"></div>
      <div class="node"></div>
      <div class="node"></div>
      <!-- More nodes generated via JS -->
    </div>
  </section>

  <!-- Cyber Projects Matrix -->
  <section class="matrix-projects">
    <div class="terminal-window">
      <div class="terminal-header">
        <div class="terminal-buttons">
          <span class="terminal-btn red"></span>
          <span class="terminal-btn yellow"></span>
          <span class="terminal-btn green"></span>
        </div>
        <span class="terminal-title">projects@sajid:~</span>
      </div>
      <div class="terminal-body">
        <div class="command-line">
          <span class="prompt">$</span>
          <span class="command">ls -la /cyber-projects</span>
        </div>
        <div class="project-grid">
          <!-- Project entries will be dynamically loaded -->
        </div>
      </div>
    </div>
  </section>

  <!-- Neural Network Stats -->
  <section class="neural-stats">
    <div class="brain-js-container">
      <canvas id="brain-js"></canvas>
    </div>
    <div class="stats-container">
      <div class="stat-node">
        <div class="stat-value" data-target="142">0</div>
        <div class="stat-label">Contributions</div>
      </div>
      <div class="stat-node">
        <div class="stat-value" data-target="27">0</div>
        <div class="stat-label">Repositories</div>
      </div>
      <div class="stat-node">
        <div class="stat-value" data-target="19">0</div>
        <div class="stat-label">Technologies</div>
      </div>
    </div>
  </section>

  <!-- Quantum Contact Links -->
  <section class="quantum-contact">
    <div class="qr-portal">
      <div class="qr-code" id="contact-qr"></div>
      <div class="portal-beams"></div>
    </div>
    <div class="contact-links">
      <a href="https://github.com/isajidalam" class="quantum-link">
        <span class="link-icon">⎔</span>
        <span class="link-text">/isajidalam</span>
      </a>
      <a href="https://linkedin.com/in/isajidalam" class="quantum-link">
        <span class="link-icon">⎔</span>
        <span class="link-text">/isajidalam</span>
      </a>
      <a href="mailto:sajidalamhere@gmail.com" class="quantum-link">
        <span class="link-icon">⎔</span>
        <span class="link-text">sajidalamhere@gmail.com</span>
      </a>
    </div>
  </section>

  <!-- Cyber Footer -->
  <footer class="cyber-footer">
    <div class="scanline"></div>
    <div class="footer-grid">
      <div class="footer-cell">
        <div class="encrypted-text">[ENCRYPTED]</div>
      </div>
      <div class="footer-cell">
        <div class="crypto-address">0x7f...4a2d</div>
      </div>
      <div class="footer-cell">
        <div class="timecode">[SYSTEM TIME: 2099.07.25-14:32:11]</div>
      </div>
    </div>
  </footer>
</div>

<style>
  /* Quantum CSS - Beyond Material Design */
  :root {
    --quantum-blue: #00f0ff;
    --neon-pink: #ff00f0;
    --cyber-purple: #7d00ff;
    --matrix-green: #00ff7f;
    --hologram-teal: #00ffcc;
    --dark-matter: #0a0a14;
    --terminal-black: #121212;
    --glow-intensity: 0.8;
  }
  
  @font-face {
    font-family: 'Quantum';
    src: url('https://fonts.cdnfonts.com/css/quantum');
  }
  
  @font-face {
    font-family: 'Cyber';
    src: url('https://fonts.cdnfonts.com/css/cyberpunk');
  }
  
  body {
    background: radial-gradient(ellipse at center, var(--dark-matter) 0%, #000 100%);
    color: var(--quantum-blue);
    font-family: 'Quantum', monospace;
    overflow-x: hidden;
    perspective: 1000px;
  }
  
  .cyber-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 2rem;
    position: relative;
  }
  
  /* Holographic Header */
  .neon-header {
    text-align: center;
    position: relative;
    padding: 4rem 0;
    margin-bottom: 5rem;
    border-bottom: 1px solid rgba(0, 240, 255, 0.2);
    overflow: hidden;
  }
  
  .glitch {
    font-size: 5rem;
    font-weight: 700;
    text-transform: uppercase;
    position: relative;
    text-shadow: 0 0 10px var(--quantum-blue), 
                 0 0 20px var(--quantum-blue), 
                 0 0 40px var(--quantum-blue);
    animation: glitch-effect 3s infinite alternate;
  }
  
  .glitch::before, .glitch::after {
    content: attr(data-text);
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
  }
  
  .glitch::before {
    left: 2px;
    text-shadow: -2px 0 var(--neon-pink);
    clip: rect(44px, 450px, 56px, 0);
    animation: glitch-anim 5s infinite linear alternate-reverse;
  }
  
  .glitch::after {
    left: -2px;
    text-shadow: -2px 0 var(--hologram-teal);
    clip: rect(44px, 450px, 56px, 0);
    animation: glitch-anim2 5s infinite linear alternate-reverse;
  }
  
  /* Quantum Bio Grid */
  .quantum-bio {
    display: grid;
    grid-template-columns: 1fr 300px;
    gap: 3rem;
    margin-bottom: 6rem;
    position: relative;
  }
  
  .bio-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
  }
  
  .grid-cell {
    opacity: 0;
    transform: translateY(20px);
    animation: quantum-enter 0.5s forwards;
  }
  
  .hologram-card {
    background: rgba(10, 10, 20, 0.7);
    border: 1px solid rgba(0, 240, 255, 0.3);
    border-radius: 8px;
    padding: 2rem;
    backdrop-filter: blur(10px);
    transition: all 0.3s ease;
    position: relative;
    overflow: hidden;
  }
  
  .hologram-card::before {
    content: '';
    position: absolute;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%;
    background: linear-gradient(
      to bottom right,
      transparent,
      transparent,
      transparent,
      var(--quantum-blue),
      transparent,
      transparent
    );
    transform: rotate(30deg);
    opacity: 0.3;
    animation: hologram-effect 6s linear infinite;
  }
  
  /* Terminal Projects */
  .matrix-projects {
    margin-bottom: 6rem;
  }
  
  .terminal-window {
    background: var(--terminal-black);
    border-radius: 8px;
    box-shadow: 0 0 30px rgba(0, 255, 127, 0.2);
    overflow: hidden;
  }
  
  .terminal-header {
    background: linear-gradient(to right, #121212, #222);
    padding: 0.5rem 1rem;
    display: flex;
    align-items: center;
  }
  
  .terminal-buttons {
    display: flex;
    gap: 0.5rem;
    margin-right: 1rem;
  }
  
  .terminal-btn {
    width: 12px;
    height: 12px;
    border-radius: 50%;
    display: inline-block;
  }
  
  .terminal-btn.red { background: #ff5f56; }
  .terminal-btn.yellow { background: #ffbd2e; }
  .terminal-btn.green { background: #27c93f; }
  
  .terminal-title {
    color: #aaa;
    font-size: 0.9rem;
  }
  
  .terminal-body {
    padding: 1.5rem;
    font-family: 'Cyber', monospace;
  }
  
  .command-line {
    color: var(--matrix-green);
    margin-bottom: 1.5rem;
  }
  
  .prompt {
    margin-right: 0.5rem;
  }
  
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1.5rem;
  }
  
  /* Neural Stats */
  .neural-stats {
    display: grid;
    grid-template-columns: 400px 1fr;
    gap: 3rem;
    margin-bottom: 6rem;
    align-items: center;
  }
  
  .brain-js-container {
    width: 100%;
    height: 300px;
    position: relative;
  }
  
  .stats-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
  }
  
  .stat-node {
    text-align: center;
    position: relative;
  }
  
  .stat-value {
    font-size: 3rem;
    font-weight: bold;
    color: var(--neon-pink);
    margin-bottom: 0.5rem;
  }
  
  .stat-label {
    font-size: 0.9rem;
    color: var(--quantum-blue);
    text-transform: uppercase;
    letter-spacing: 1px;
  }
  
  /* Quantum Contact */
  .quantum-contact {
    display: grid;
    grid-template-columns: 200px 1fr;
    gap: 3rem;
    align-items: center;
    margin-bottom: 6rem;
  }
  
  .qr-portal {
    position: relative;
    width: 200px;
    height: 200px;
  }
  
  .qr-code {
    width: 100%;
    height: 100%;
    background: #fff;
    position: relative;
    z-index: 2;
  }
  
  .portal-beams {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: radial-gradient(circle, transparent 40%, var(--cyber-purple) 100%);
    animation: portal-spin 8s linear infinite;
    z-index: 1;
  }
  
  .contact-links {
    display: flex;
    flex-direction: column;
    gap: 1.5rem;
  }
  
  .quantum-link {
    display: flex;
    align-items: center;
    color: var(--hologram-teal);
    text-decoration: none;
    font-size: 1.2rem;
    transition: all 0.3s ease;
    position: relative;
    padding-left: 2rem;
  }
  
  .quantum-link:hover {
    color: var(--quantum-blue);
    transform: translateX(10px);
  }
  
  .quantum-link:hover .link-icon {
    transform: rotate(45deg);
  }
  
  .link-icon {
    position: absolute;
    left: 0;
    transition: all 0.3s ease;
  }
  
  /* Cyber Footer */
  .cyber-footer {
    position: relative;
    padding: 2rem 0;
    border-top: 1px solid rgba(0, 240, 255, 0.2);
  }
  
  .scanline {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(
      to bottom,
      transparent,
      rgba(0, 240, 255, 0.05) 50%,
      transparent
    );
    animation: scanline 8s linear infinite;
    pointer-events: none;
  }
  
  .footer-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
  }
  
  .footer-cell {
    text-align: center;
    opacity: 0.7;
    font-size: 0.8rem;
  }
  
  /* Animations */
  @keyframes glitch-effect {
    0%, 100% { transform: translate(0); }
    20% { transform: translate(-2px, 2px); }
    40% { transform: translate(-2px, -2px); }
    60% { transform: translate(2px, 2px); }
    80% { transform: translate(2px, -2px); }
  }
  
  @keyframes glitch-anim {
    0% { clip: rect(31px, 9999px, 94px, 0); }
    10% { clip: rect(112px, 9999px, 76px, 0); }
    20% { clip: rect(85px, 9999px, 77px, 0); }
    30% { clip: rect(27px, 9999px, 97px, 0); }
    40% { clip: rect(64px, 9999px, 98px, 0); }
    50% { clip: rect(61px, 9999px, 85px, 0); }
    60% { clip: rect(99px, 9999px, 114px, 0); }
    70% { clip: rect(34px, 9999px, 115px, 0); }
    80% { clip: rect(98px, 9999px, 129px, 0); }
    90% { clip: rect(43px, 9999px, 96px, 0); }
    100% { clip: rect(82px, 9999px, 64px, 0); }
  }
  
  @keyframes glitch-anim2 {
    0% { clip: rect(65px, 9999px, 119px, 0); }
    10% { clip: rect(79px, 9999px, 66px, 0); }
    20% { clip: rect(101px, 9999px, 114px, 0); }
    30% { clip: rect(90px, 9999px, 91px, 0); }
    40% { clip: rect(92px, 9999px, 129px, 0); }
    50% { clip: rect(53px, 9999px, 96px, 0); }
    60% { clip: rect(111px, 9999px, 113px, 0); }
    70% { clip: rect(25px, 9999px, 120px, 0); }
    80% { clip: rect(91px, 9999px, 98px, 0); }
    90% { clip: rect(83px, 9999px, 73px, 0); }
    100% { clip: rect(110px, 9999px, 117px, 0); }
  }
  
  @keyframes quantum-enter {
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  
  @keyframes hologram-effect {
    0% { transform: rotate(30deg) translate(-10%, -10%); }
    100% { transform: rotate(30deg) translate(10%, 10%); }
  }
  
  @keyframes portal-spin {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  
  @keyframes scanline {
    from { transform: translateY(-100%); }
    to { transform: translateY(100%); }
  }
  
  /* Responsive Adjustments */
  @media (max-width: 1024px) {
    .quantum-bio, .neural-stats, .quantum-contact {
      grid-template-columns: 1fr;
    }
    
    .brain-js-container {
      height: 200px;
      margin-bottom: 2rem;
    }
  }
  
  @media (max-width: 768px) {
    .glitch {
      font-size: 3rem;
    }
    
    .stats-container {
      grid-template-columns: 1fr;
    }
    
    .footer-grid {
      grid-template-columns: 1fr;
      gap: 1rem;
    }
  }
</style>

<script>
  // Quantum JavaScript Enhancements
  document.addEventListener('DOMContentLoaded', function() {
    // Animate grid cells sequentially
    document.querySelectorAll('.grid-cell').forEach((cell, index) => {
      cell.style.animationDelay = cell.style.getPropertyValue('--delay') || `${index * 0.2}s`;
    });
    
    // Animate stats counting
    const statValues = document.querySelectorAll('.stat-value');
    statValues.forEach(stat => {
      const target = parseInt(stat.getAttribute('data-target'));
      const duration = 2000;
      const step = target / (duration / 16);
      let current = 0;
      
      const counter = setInterval(() => {
        current += step;
        if (current >= target) {
          clearInterval(counter);
          stat.textContent = target;
        } else {
          stat.textContent = Math.floor(current);
        }
      }, 16);
    });
    
    // Generate project entries
    const projects = [
      {
        name: "Base64 Encoder",
        description: "Quantum data transformation interface",
        link: "https://base64encodedecode.pages.dev/",
        tech: ["HTML", "JS", "CRYPTO"]
      },
      {
        name: "Modern Calculator",
        description: "Holographic computation device",
        link: "https://modern-calculator.pages.dev/",
        tech: ["HTML", "CSS", "JS"]
      },
      {
        name: "iOS Calculator UI",
        description: "Retro Apple interface simulation",
        link: "https://ioscalculator.pages.dev/",
        tech: ["HTML", "CSS", "UI/UX"]
      },
      {
        name: "Funny Greeting",
        description: "Emotional recognition module",
        link: "https://isajidalam.github.io/sajid",
        tech: ["HTML", "CSS", "AI"]
      }
    ];
    
    const projectGrid = document.querySelector('.project-grid');
    projects.forEach(project => {
      const projectEl = document.createElement('div');
      projectEl.className = 'project-entry';
      projectEl.innerHTML = `
        <div class="project-hologram">
          <h4>${project.name}</h4>
          <p>${project.description}</p>
          <div class="project-tech">${project.tech.map(t => `<span>${t}</span>`).join('')}</div>
          <a href="${project.link}" target="_blank" class="project-link">ACCESS</a>
        </div>
      `;
      projectGrid.appendChild(projectEl);
    });
    
    // Initialize Brain.js visualization
    if (typeof Brain !== 'undefined') {
      const brainCanvas = document.getElementById('brain-js');
      // Neural network visualization code would go here
    }
    
    // Generate DNA helix nodes
    const dnaHelix = document.querySelector('.dna-helix');
    for (let i = 0; i < 20; i++) {
      const node = document.createElement('div');
      node.className = 'node';
      node.style.setProperty('--angle', `${i * 18}deg`);
      node.style.animationDelay = `${i * 0.1}s`;
      dnaHelix.appendChild(node);
    }
  });
</script>
