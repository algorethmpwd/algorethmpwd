<svg width="800" height="300" xmlns="http://www.w3.org/2000/svg">
  <style>
    @keyframes colorChange {
      0% { fill: #00ff00; }
      33% { fill: #00ffff; }
      66% { fill: #ff00ff; }
      100% { fill: #00ff00; }
    }
    
    @keyframes glitch {
      0% {
        transform: translate(0);
      }
      20% {
        transform: translate(-2px, 2px);
      }
      40% {
        transform: translate(-2px, -2px);
      }
      60% {
        transform: translate(2px, 2px);
      }
      80% {
        transform: translate(2px, -2px);
      }
      100% {
        transform: translate(0);
      }
    }
    
    .ascii-art {
      font-family: 'Courier New', monospace;
      font-size: 12px;
      animation: colorChange 6s infinite;
    }
    
    .glitch-text {
      font-family: 'Courier New', monospace;
      font-weight: bold;
      font-size: 40px;
      animation: glitch 0.5s infinite alternate-reverse;
    }
    
    .main-text {
      font-family: 'Arial', sans-serif;
      font-size: 14px;
      fill: #ccffcc;
    }
  </style>
  
  <!-- Title with glitch effect -->
  <text x="400" y="50" text-anchor="middle" class="glitch-text" fill="#00ff00">ALGORETHM</text>
  
  <!-- ASCII Art -->
  <text x="100" y="100" class="ascii-art">
    <tspan x="100" dy="0">    _    _                       _   _           </tspan>
    <tspan x="100" dy="15">   / \  | | __ _  ___  _ __ ___| |_| |__  _ __ ___</tspan>
    <tspan x="100" dy="15">  / _ \ | |/ _` |/ _ \| '__/ _ \ __| '_ \| '_ ` _ \</tspan>
    <tspan x="100" dy="15"> / ___ \| | (_| | (_) | | |  __/ |_| | | | | | | | |</tspan>
    <tspan x="100" dy="15">/_/   \_\_|\__, |\___/|_|  \___|\__|_| |_|_| |_| |_|</tspan>
    <tspan x="100" dy="15">           |___/                                    </tspan>
  </text>
  
  <!-- Hacker quote -->
  <text x="400" y="250" text-anchor="middle" class="main-text" font-style="italic">
    "I don't break into systems... I just find the doors they left open."
  </text>
</svg>
