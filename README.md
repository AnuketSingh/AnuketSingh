<div align="center">

<!-- HERO BANNER (Inline Animated SVG) -->
<svg fill="none" width="100%" height="340" viewBox="0 0 800 340" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712" />
      <stop offset="50%" stop-color="#0b132b" />
      <stop offset="100%" stop-color="#030712" />
    </linearGradient>

    <linearGradient id="accent-grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00f2fe">
        <animate attributeName="stop-color" values="#00f2fe; #4facfe; #7f00ff; #00f2fe" dur="8s" repeatCount="indefinite" />
      </stop>
      <stop offset="100%" stop-color="#4facfe">
        <animate attributeName="stop-color" values="#4facfe; #7f00ff; #00f2fe; #4facfe" dur="8s" repeatCount="indefinite" />
      </stop>
    </linearGradient>

    <pattern id="grid" width="30" height="30" patternUnits="userSpaceOnUse">
      <path d="M 30 0 L 0 0 0 30" fill="none" stroke="#1e293b" stroke-width="0.5" opacity="0.4" />
    </pattern>

    <filter id="glow" x="-10%" y="-10%" width="120%" height="120%">
      <feGaussianBlur stdDeviation="6" result="blur" />
      <feComposite in="SourceGraphic" in2="blur" operator="over" />
    </filter>
  </defs>

  <rect width="800" height="340" rx="12" fill="url(#bg-grad)" stroke="#1e293b" stroke-width="2" />
  <rect width="800" height="340" rx="12" fill="url(#grid)" />

  <rect x="0" y="0" width="800" height="3" fill="url(#accent-grad)" />

  <!-- Terminal Frame -->
  <rect x="30" y="40" width="410" height="260" rx="8" fill="#090d16" stroke="#1e293b" stroke-width="1.5" />
  <path d="M 30 48 C 30 43.5 33.5 40 38 40 L 432 40 C 436.5 40 440 43.5 440 48 L 440 70 L 30 70 Z" fill="#0f172a" />
  <circle cx="50" cy="55" r="4.5" fill="#ef4444" />
  <circle cx="65" cy="55" r="4.5" fill="#f59e0b" />
  <circle cx="80" cy="55" r="4.5" fill="#10b981" />
  <text x="235" y="59" fill="#64748b" font-family="'Courier New', monospace" font-size="11" text-anchor="middle">system_core.sh</text>

  <!-- Terminal Content -->
  <g font-family="'Courier New', monospace" font-size="12">
    <text x="45" y="95" fill="#00f2fe">$ <tspan fill="#e2e8f0">whoami</tspan></text>
    <text x="45" y="115" fill="#94a3b8">  Anuket Singh</text>

    <text x="45" y="145" fill="#00f2fe">$ <tspan fill="#e2e8f0">focus</tspan></text>
    <text x="45" y="165" fill="#94a3b8">  AI/ML • Computer Vision • Data</text>

    <text x="45" y="195" fill="#00f2fe">$ <tspan fill="#e2e8f0">status</tspan></text>
    <text x="45" y="215" fill="#10b981">  ● Active <tspan fill="#94a3b8">| Building &amp; Learning</tspan></text>

    <text x="45" y="245" fill="#00f2fe">$ <tspan fill="#e2e8f0">sys_init --mode=build</tspan></text>
    <text x="45" y="268" fill="#38bdf8">&gt; System initialized.<tspan fill="#00f2fe">_</tspan>
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" />
    </text>
  </g>

  <!-- Hero Header -->
  <g font-family="system-ui, -apple-system, sans-serif">
    <text x="470" y="90" fill="#38bdf8" font-size="12" font-weight="600" letter-spacing="2">SYSTEM IDENTIFIER</text>
    <text x="470" y="125" fill="#ffffff" font-size="28" font-weight="800" letter-spacing="1">ANUKET SINGH</text>
    
    <text x="470" y="155" fill="#94a3b8" font-size="13">Computer Science Student</text>
    <text x="470" y="173" fill="#64748b" font-size="12">AI/ML, Computer Vision &amp; Web Dev</text>

    <!-- Tech Pills -->
    <g transform="translate(470, 205)">
      <rect x="0" y="0" width="60" height="22" rx="4" fill="#1e293b" stroke="#334155" />
      <text x="30" y="15" fill="#38bdf8" font-size="10" font-weight="600" text-anchor="middle">C++</text>

      <rect x="68" y="0" width="70" height="22" rx="4" fill="#1e293b" stroke="#334155" />
      <text x="103" y="15" fill="#38bdf8" font-size="10" font-weight="600" text-anchor="middle">Python</text>

      <rect x="146" y="0" width="60" height="22" rx="4" fill="#1e293b" stroke="#334155" />
      <text x="176" y="15" fill="#38bdf8" font-size="10" font-weight="600" text-anchor="middle">SQL</text>

      <rect x="0" y="30" width="90" height="22" rx="4" fill="#1e293b" stroke="#334155" />
      <text x="45" y="45" fill="#38bdf8" font-size="10" font-weight="600" text-anchor="middle">AI / Vision</text>

      <rect x="98" y="30" width="108" height="22" rx="4" fill="#1e293b" stroke="#334155" />
      <text x="152" y="45" fill="#38bdf8" font-size="10" font-weight="600" text-anchor="middle">Data Analytics</text>
    </g>

    <circle cx="740" cy="280" r="15" fill="none" stroke="url(#accent-grad)" stroke-width="1.5" filter="url(#glow)">
      <animate attributeName="r" values="12;18;12" dur="3s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite" />
    </circle>
  </g>
</svg>

<br/><br/>

<!-- Action Buttons -->
<a href="https://github.com/AnuketSingh">
  <img src="https://img.shields.io/badge/GITHUB-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=090D16&color=00F2FE" alt="GitHub" />
</a>
<a href="https://linkedin.com/in/">
  <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=090D16" alt="LinkedIn" />
</a>
<a href="mailto:anuketsingh@example.com">
  <img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=090D16" alt="Email" />
</a>

</div>

<br/>

```sys
================================================================================
                    01 / ABOUT ME
================================================================================
