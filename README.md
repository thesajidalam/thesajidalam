<!-- ===== CINEMATIC IDENTITY HEADER ===== -->
<div align="center" style="position: relative; padding: 2.5rem 0 0.5rem 0; overflow: hidden; background: radial-gradient(ellipse at 50% 0%, rgba(0, 217, 255, 0.08) 0%, transparent 60%), radial-gradient(ellipse at 50% 100%, rgba(100, 80, 255, 0.05) 0%, transparent 50%);">
  
  <!-- Ambient floating orbs -->
  <div style="position: absolute; width: 40vw; height: 40vw; top: -15%; left: -10%; background: radial-gradient(circle, rgba(0, 217, 255, 0.06), transparent 70%); border-radius: 50%; filter: blur(60px); pointer-events: none; animation: floatOrb1 8s ease-in-out infinite alternate;"></div>
  <div style="position: absolute; width: 35vw; height: 35vw; bottom: -20%; right: -10%; background: radial-gradient(circle, rgba(150, 100, 255, 0.05), transparent 70%); border-radius: 50%; filter: blur(60px); pointer-events: none; animation: floatOrb2 10s ease-in-out infinite alternate;"></div>
  <div style="position: absolute; width: 25vw; height: 25vw; top: 30%; right: 20%; background: radial-gradient(circle, rgba(0, 200, 255, 0.04), transparent 70%); border-radius: 50%; filter: blur(50px); pointer-events: none; animation: floatOrb3 12s ease-in-out infinite alternate;"></div>
  
  <!-- Glowing ring behind name -->
  <div style="position: absolute; width: 55vw; height: 55vw; top: 50%; left: 50%; transform: translate(-50%, -50%); border-radius: 50%; border: 1px solid rgba(0, 217, 255, 0.04); box-shadow: 0 0 80px rgba(0, 217, 255, 0.02), inset 0 0 80px rgba(0, 217, 255, 0.01); pointer-events: none; animation: ringPulse 6s ease-in-out infinite alternate;"></div>
  <div style="position: absolute; width: 40vw; height: 40vw; top: 50%; left: 50%; transform: translate(-50%, -50%); border-radius: 50%; border: 1px solid rgba(150, 100, 255, 0.03); box-shadow: 0 0 60px rgba(150, 100, 255, 0.01); pointer-events: none; animation: ringPulse 8s ease-in-out infinite alternate-reverse;"></div>
  
  <!-- Main Name -->
  <h1 style="
    position: relative;
    z-index: 2;
    font-size: clamp(3.8rem, 16vw, 8.5rem);
    font-weight: 800;
    font-family: 'Inter', 'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif;
    letter-spacing: -0.02em;
    line-height: 1.1;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #f0f8ff 0%, #b0d4ff 25%, #7ab8ff 50%, #a78bfa 75%, #c4b5fd 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
    filter: drop-shadow(0 8px 40px rgba(0, 150, 255, 0.15)) drop-shadow(0 2px 8px rgba(0, 0, 0, 0.2));
    text-shadow: 0 0 60px rgba(0, 180, 255, 0.1), 0 0 120px rgba(100, 80, 255, 0.05);
    transform: perspective(800px) rotateX(1deg);
    animation: textGlow 4s ease-in-out infinite alternate;
  ">
    Sajid Alam
  </h1>
  
  <!-- Subtitle / Status -->
  <div style="
    position: relative;
    z-index: 2;
    margin-top: 0.2rem;
    display: inline-flex;
    align-items: center;
    gap: 0.6rem;
    padding: 0.3rem 1.8rem;
    border-radius: 60px;
    background: rgba(255, 255, 255, 0.02);
    backdrop-filter: blur(8px);
    -webkit-backdrop-filter: blur(8px);
    border: 1px solid rgba(255, 255, 255, 0.04);
    box-shadow: 0 0 30px rgba(0, 150, 255, 0.02), inset 0 0 30px rgba(255, 255, 255, 0.01);
  ">
    <span style="display: inline-block; width: 8px; height: 8px; border-radius: 50%; background: #00D9FF; box-shadow: 0 0 20px #00D9FF, 0 0 60px rgba(0, 217, 255, 0.2); animation: pulseDot 2s ease-in-out infinite;"></span>
    <span style="font-size: clamp(0.65rem, 1.2vw, 0.95rem); font-weight: 400; letter-spacing: 0.15em; text-transform: uppercase; color: rgba(180, 210, 255, 0.5); font-family: 'Inter', monospace;">Full-Stack · IoT · Security</span>
    <span style="display: inline-block; width: 4px; height: 4px; border-radius: 50%; background: rgba(180, 210, 255, 0.15);"></span>
    <span style="font-size: clamp(0.55rem, 0.9vw, 0.75rem); letter-spacing: 0.1em; color: rgba(180, 210, 255, 0.25); font-family: 'Inter', monospace;">✦ BUILDING THE FUTURE ✦</span>
  </div>
  
  <!-- Decorative line -->
  <div style="
    position: relative;
    z-index: 2;
    margin-top: 1.2rem;
    width: clamp(120px, 30vw, 400px);
    height: 2px;
    background: linear-gradient(90deg, transparent, rgba(0, 217, 255, 0.15), rgba(150, 100, 255, 0.15), transparent);
    border-radius: 4px;
    filter: blur(1px);
  "></div>
  
</div>

<style>
  @keyframes floatOrb1 {
    0% { transform: translate(0, 0) scale(1); }
    100% { transform: translate(40px, -30px) scale(1.1); }
  }
  @keyframes floatOrb2 {
    0% { transform: translate(0, 0) scale(1); }
    100% { transform: translate(-30px, 40px) scale(1.15); }
  }
  @keyframes floatOrb3 {
    0% { transform: translate(0, 0) scale(1); }
    100% { transform: translate(20px, 20px) scale(0.9); }
  }
  @keyframes ringPulse {
    0% { transform: translate(-50%, -50%) scale(0.98); opacity: 0.6; }
    100% { transform: translate(-50%, -50%) scale(1.02); opacity: 1; }
  }
  @keyframes textGlow {
    0% { filter: drop-shadow(0 8px 40px rgba(0, 150, 255, 0.12)) drop-shadow(0 2px 8px rgba(0, 0, 0, 0.2)); }
    50% { filter: drop-shadow(0 8px 60px rgba(0, 180, 255, 0.25)) drop-shadow(0 2px 12px rgba(100, 80, 255, 0.15)); }
    100% { filter: drop-shadow(0 8px 40px rgba(0, 150, 255, 0.12)) drop-shadow(0 2px 8px rgba(0, 0, 0, 0.2)); }
  }
  @keyframes pulseDot {
    0%, 100% { opacity: 0.4; transform: scale(0.8); box-shadow: 0 0 10px #00D9FF, 0 0 30px rgba(0, 217, 255, 0.1); }
    50% { opacity: 1; transform: scale(1.2); box-shadow: 0 0 25px #00D9FF, 0 0 60px rgba(0, 217, 255, 0.25); }
  }
</style>

<!-- ===== ORIGINAL GIF ===== -->
<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif"/>
</div>
