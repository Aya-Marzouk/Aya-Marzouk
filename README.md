<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0B1B33">
        <animate attributeName="stop-color" values="#0B1B33;#0F2A4A;#0B1B33" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#123A5E">
        <animate attributeName="stop-color" values="#123A5E;#0B2540;#123A5E" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7FFFEA"/>
      <stop offset="50%" stop-color="#4FD8FF"/>
      <stop offset="100%" stop-color="#FFFFFF"/>
    </linearGradient>

    <linearGradient id="barGrad" x1="0%" y1="100%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#00C2CB" stop-opacity="0.15"/>
      <stop offset="100%" stop-color="#4FD8FF" stop-opacity="0.55"/>
    </linearGradient>

    <radialGradient id="glow" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#4FD8FF" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#4FD8FF" stop-opacity="0"/>
    </radialGradient>

    <clipPath id="revealName">
      <rect x="0" y="0" width="0" height="320">
        <animate attributeName="width" from="0" to="1200" begin="0.1s" dur="1.1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>

    <clipPath id="revealSub">
      <rect x="0" y="0" width="0" height="320">
        <animate attributeName="width" from="0" to="1200" begin="1.3s" dur="1.4s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>
  </defs>

  <!-- Background -->
  <rect width="1200" height="320" fill="url(#bg)"/>
  <circle cx="600" cy="150" r="260" fill="url(#glow)"/>

  <!-- Subtle dot grid -->
  <g opacity="0.18">
    <g id="dotsRow"></g>
  </g>
  <g fill="#9FE9FF">
    <circle cx="40" cy="40" r="1.6"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="3.5s" repeatCount="indefinite"/></circle>
    <circle cx="90" cy="60" r="1.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="4s" repeatCount="indefinite"/></circle>
    <circle cx="150" cy="35" r="1.6"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="3s" repeatCount="indefinite"/></circle>
    <circle cx="1080" cy="50" r="1.6"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="3.8s" repeatCount="indefinite"/></circle>
    <circle cx="1130" cy="80" r="1.6"><animate attributeName="opacity" values="0.6;0.1;0.6" dur="3.2s" repeatCount="indefinite"/></circle>
    <circle cx="1020" cy="30" r="1.6"><animate attributeName="opacity" values="0.4;0.9;0.4" dur="4.4s" repeatCount="indefinite"/></circle>
    <circle cx="60" cy="270" r="1.6"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3.6s" repeatCount="indefinite"/></circle>
    <circle cx="1140" cy="260" r="1.6"><animate attributeName="opacity" values="0.5;0.1;0.5" dur="3.1s" repeatCount="indefinite"/></circle>
  </g>

  <!-- Floating data points rising -->
  <g fill="#4FD8FF">
    <circle cx="120" cy="300" r="2.4">
      <animate attributeName="cy" values="300;20" dur="5s" begin="0s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.8;0" dur="5s" begin="0s" repeatCount="indefinite"/>
    </circle>
    <circle cx="220" cy="300" r="2" fill="#7FFFEA">
      <animate attributeName="cy" values="300;20" dur="6.2s" begin="1.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.7;0" dur="6.2s" begin="1.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="980" cy="300" r="2.4">
      <animate attributeName="cy" values="300;20" dur="5.6s" begin="0.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.8;0" dur="5.6s" begin="0.6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1080" cy="300" r="2" fill="#7FFFEA">
      <animate attributeName="cy" values="300;20" dur="4.8s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.7;0" dur="4.8s" begin="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Animated bar chart motif, left side -->
  <g transform="translate(60,0)">
    <rect x="0" y="240" width="14" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="55" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="240" to="185" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
    </rect>
    <rect x="22" y="240" width="14" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="85" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="240" to="155" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
    </rect>
    <rect x="44" y="240" width="14" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="40" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="240" to="200" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
    </rect>
  </g>

  <!-- Animated bar chart motif, right side (mirrored) -->
  <g transform="translate(1100,0)">
    <rect x="0" y="240" width="14" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="40" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="240" to="200" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
    </rect>
    <rect x="22" y="240" width="14" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="85" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="240" to="155" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
    </rect>
    <rect x="44" y="240" width="14" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="55" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="240" to="185" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
    </rect>
  </g>

  <!-- Animated line-chart squiggle drawing across -->
  <path d="M 80 240 L 250 200 L 400 220 L 560 150 L 700 175 L 850 120 L 1000 145 L 1120 95"
        fill="none" stroke="#7FFFEA" stroke-width="2.5" opacity="0.55" stroke-linecap="round"
        stroke-dasharray="1400" stroke-dashoffset="1400">
    <animate attributeName="stroke-dashoffset" from="1400" to="0" begin="0.2s" dur="2.2s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
  </path>

  <!-- Name -->
  <g clip-path="url(#revealName)">
    <text x="600" y="150" text-anchor="middle" font-family="Arial, Helvetica, sans-serif"
          font-size="64" font-weight="800" fill="url(#nameGrad)" letter-spacing="4">
      AYA AHMED
    </text>
  </g>

  <!-- Animated underline brush stroke -->
  <rect x="600" y="172" width="0" height="4" rx="2" fill="#4FD8FF" transform="translate(-130,0)">
    <animate attributeName="width" from="0" to="260" begin="1.15s" dur="0.5s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
  </rect>

  <!-- Subtitle with typewriter reveal -->
  <g clip-path="url(#revealSub)">
    <text x="600" y="215" text-anchor="middle" font-family="Consolas, 'Courier New', monospace"
          font-size="22" font-weight="500" fill="#CFEFFF" letter-spacing="3">
      DATA ANALYST &#160;|&#160; BUSINESS INTELLIGENCE &amp; DATA VISUALIZATION
    </text>
  </g>

  <!-- Blinking cursor at end of typewriter line -->
  <rect x="965" y="198" width="3" height="22" fill="#4FD8FF" opacity="0">
    <animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.46;0.47;0.85;0.86;1" dur="3s" begin="1.3s" repeatCount="indefinite"/>
  </rect>

  <!-- Tagline -->
  <g opacity="0">
    <text x="600" y="255" text-anchor="middle" font-family="Arial, Helvetica, sans-serif"
          font-size="15" fill="#7FAFD0" letter-spacing="1">
      Turning raw data into dashboards that drive decisions
    </text>
    <animate attributeName="opacity" from="0" to="1" begin="2.8s" dur="0.8s" fill="freeze"/>
  </g>
</svg>
