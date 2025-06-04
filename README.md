👨‍💻 Full-Stack Software Engineer

<svg width="400" height="200" viewBox="0 0 400 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Blue to Pink Gradient -->
    <linearGradient id="mainGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#3B82F6;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#8B5CF6;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#EC4899;stop-opacity:1" />
    </linearGradient>
    
    <!-- Background Gradient -->
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#3B82F6;stop-opacity:0.8" />
      <stop offset="25%" style="stop-color:#6366F1;stop-opacity:0.7" />
      <stop offset="75%" style="stop-color:#8B5CF6;stop-opacity:0.7" />
      <stop offset="100%" style="stop-color:#EC4899;stop-opacity:0.8" />
    </linearGradient>
    
    <!-- Pink to Blue Gradient -->
    <linearGradient id="reverseGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#EC4899;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#8B5CF6;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#3B82F6;stop-opacity:1" />
    </linearGradient>
    
    <!-- Glow Filter -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge> 
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    
    <!-- Drop Shadow -->
    <filter id="dropshadow" x="-50%" y="-50%" width="200%" height="200%">
      <feDropShadow dx="2" dy="4" stdDeviation="3" flood-color="#000000" flood-opacity="0.3"/>
    </filter>
  </defs>
  
  <!-- Background -->
  <rect width="400" height="200" rx="20" fill="url(#bgGradient)" stroke="url(#mainGradient)" stroke-width="3" stroke-opacity="0.6"/>
  
  <!-- Decorative Background Elements -->
  <circle cx="80" cy="50" r="30" fill="#FFFFFF" opacity="0.15">
    <animate attributeName="r" values="30;40;30" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="320" cy="150" r="35" fill="#FFFFFF" opacity="0.12">
    <animate attributeName="r" values="35;25;35" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Floating Particles -->
  <circle cx="60" cy="160" r="3" fill="#FFFFFF" opacity="0.8">
    <animate attributeName="cy" values="160;140;160" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;1;0.8" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="340" cy="40" r="2" fill="#FFFFFF" opacity="0.9">
    <animate attributeName="cy" values="40;60;40" dur="1.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.9;0.5;0.9" dur="1.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="120" cy="30" r="2" fill="#FFFFFF" opacity="0.7">
    <animate attributeName="cy" values="30;50;30" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Main RS Letters Container -->
  <g transform="translate(200,100)">
    <!-- Background Circle for Letters -->
    <circle cx="0" cy="0" r="60" fill="#FFFFFF" opacity="0.25" filter="url(#glow)">
      <animate attributeName="r" values="60;65;60" dur="4s" repeatCount="indefinite"/>
    </circle>
    
    <!-- Letter R -->
    <g transform="translate(-35,0)" filter="url(#dropshadow)">
      <text x="0" y="15" text-anchor="middle" font-family="Arial, sans-serif" font-size="72" font-weight="bold" fill="#FFFFFF" filter="url(#glow)">R</text>
    </g>
    
    <!-- Letter S -->
    <g transform="translate(35,0)" filter="url(#dropshadow)">
      <text x="0" y="15" text-anchor="middle" font-family="Arial, sans-serif" font-size="72" font-weight="bold" fill="#FFFFFF" filter="url(#glow)">S</text>
    </g>
  </g>
  
  <!-- Decorative Lines -->
  <line x1="50" y1="100" x2="140" y2="100" stroke="#FFFFFF" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite"/>
  </line>
  <line x1="260" y1="100" x2="350" y2="100" stroke="#FFFFFF" stroke-width="2" opacity="0.7">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="3s" repeatCount="indefinite" begin="1.5s"/>
  </line>
  
  <!-- Bottom Text -->
  <text x="200" y="170" text-anchor="middle" font-family="Arial, sans-serif" font-size="14" font-weight="600" fill="#FFFFFF" opacity="0.9">
    Software Engineer
  </text>
  
  <!-- Corner Decorations -->
  <polygon points="20,20 40,20 20,40" fill="#FFFFFF" opacity="0.4"/>
  <polygon points="380,20 380,40 360,20" fill="#FFFFFF" opacity="0.4"/>
  <polygon points="20,180 40,180 20,160" fill="#FFFFFF" opacity="0.4"/>
  <polygon points="380,180 380,160 360,180" fill="#FFFFFF" opacity="0.4"/>
</svg>

```bash
const developer = {
  role: "Full-Stack Software Engineer",
  languages: ["JavaScript", "TypeScript", "Python", "PHP", "Ruby"],
  passions: ["Clean Code", "Problem Solving", "Innovation", "Coffee ☕"],
  currentFocus: "Building intelligent AI-driven solutions using modern frameworks and data pipelines",
  funFact: "I debug with console.log and I'm not ashamed! 🐛"
};
```
