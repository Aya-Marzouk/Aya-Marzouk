<svg width="1200" height="520" viewBox="0 0 1200 520" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#07111E"/>
      <stop offset="100%" stop-color="#0E2945"/>
    </linearGradient>

    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F2FE"/>
      <stop offset="50%" stop-color="#4FACFE"/>
      <stop offset="100%" stop-color="#FFFFFF"/>
    </linearGradient>

    <linearGradient id="barGrad" x1="0%" y1="100%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#00F2FE" stop-opacity="0.1"/>
      <stop offset="100%" stop-color="#4FACFE" stop-opacity="0.6"/>
    </linearGradient>

    <style>
      @keyframes floatAnimation {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-6px); }
        100% { transform: translateY(0px); }
      }
      
      @keyframes barPulse {
        0% { transform: scaleY(1); }
        50% { transform: scaleY(0.75); }
        100% { transform: scaleY(1); }
      }

      .skill-badge {
        transform-box: fill-box;
        transform-origin: center;
      }
      
      .sk-1 { animation: floatAnimation 3s infinite ease-in-out; }
      .sk-2 { animation: floatAnimation 3.4s infinite ease-in-out; animation-delay: 0.3s; }
      .sk-3 { animation: floatAnimation 3.1s infinite ease-in-out; animation-delay: 0.6s; }
      .sk-4 { animation: floatAnimation 3.6s infinite ease-in-out; animation-delay: 0.2s; }
      .sk-5 { animation: floatAnimation 3.2s infinite ease-in-out; animation-delay: 0.5s; }

      .bar-item {
        transform-box: fill-box;
        transform-origin: bottom;
        animation: barPulse 2.5s infinite ease-in-out;
      }
      .b-d1 { animation-delay: 0.2s; }
      .b-d2 { animation-delay: 0.5s; }
    </style>
  </defs>

  <rect width="1200" height="520" fill="url(#bg)"/>

  <g transform="translate(60, 40)">
    <rect x="0" y="180" width="14" height="120" fill="url(#barGrad)" rx="4" class="bar-item"/>
    <rect x="22" y="130" width="14" height="170" fill="url(#barGrad)" rx="4" class="bar-item b-d1"/>
    <rect x="44" y="210" width="14" height="90" fill="url(#barGrad)" rx="4" class="bar-item b-d2"/>
  </g>

  <g transform="translate(1080, 40)">
    <rect x="0" y="210" width="14" height="90" fill="url(#barGrad)" rx="4" class="bar-item b-d2"/>
    <rect x="22" y="130" width="14" height="170" fill="url(#barGrad)" rx="4" class="bar-item b-d1"/>
    <rect x="44" y="180" width="14" height="120" fill="url(#barGrad)" rx="4" class="bar-item"/>
  </g>

  <text x="600" y="110" text-anchor="middle" font-family="'Segoe UI', Roboto, sans-serif" font-size="64" font-weight="900" fill="url(#nameGrad)" letter-spacing="5">
    AYA AHMED
  </text>

  <rect x="450" y="132" width="300" height="4" rx="2" fill="#00F2FE" />

  <text x="600" y="175" text-anchor="middle" font-family="Consolas, 'Courier New', monospace" font-size="19" font-weight="600" fill="#E2F5FF" letter-spacing="2">
    DATA ANALYST &#160;|&#160; BUSINESS INTELLIGENCE &amp; DATA VISUALIZATION
  </text>

  <text x="600" y="210" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-style="italic" font-size="14" fill="#8AB4D4">
    "Turning raw data into dashboards that drive decisions"
  </text>

  <g class="skill-badge sk-1" transform="translate(360, 245)">
    <rect x="0" y="0" width="80" height="30" rx="15" fill="#11294A" stroke="#00F2FE" stroke-width="1.2" />
    <text x="40" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#00F2FE">SQL</text>
  </g>

  <g class="skill-badge sk-2" transform="translate(455, 245)">
    <rect x="0" y="0" width="110" height="30" rx="15" fill="#11294A" stroke="#FFD000" stroke-width="1.2" />
    <text x="55" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#FFD000">POWER BI</text>
  </g>

  <g class="skill-badge sk-3" transform="translate(580, 245)">
    <rect x="0" y="0" width="95" height="30" rx="15" fill="#11294A" stroke="#4FACFE" stroke-width="1.2" />
    <text x="47.5" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#4FACFE">PYTHON</text>
  </g>

  <g class="skill-badge sk-4" transform="translate(690, 245)">
    <rect x="0" y="0" width="100" height="30" rx="15" fill="#11294A" stroke="#E06666" stroke-width="1.2" />
    <text x="50" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#E06666">TABLEAU</text>
  </g>

  <g class="skill-badge sk-5" transform="translate(805, 245)">
    <rect x="0" y="0" width="85" height="30" rx="15" fill="#11294A" stroke="#21A366" stroke-width="1.2" />
    <text x="42.5" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#21A366">EXCEL</text>
  </g>


  <g transform="translate(0, 20)">
    <text x="600" y="325" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="16" font-weight="bold" fill="#4FACFE" letter-spacing="3">FEATURED PROJECTS</text>
    <line x1="550" y1="335" x2="650" y2="335" stroke="#4FACFE" stroke-width="1" opacity="0.5"/>

    <g transform="translate(240, 355)">
      <rect width="220" height="85" rx="8" fill="#0C1A2D" stroke="#1E3A5F" stroke-width="1"/>
      <text x="20" y="30" font-family="'Segoe UI', sans-serif" font-size="14" font-weight="bold" fill="#FFFFFF">E-Commerce Insights</text>
      <text x="20" y="52" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8AB4D4">Sales &amp; Cohort Analysis</text>
      <text x="20" y="68" font-family="Consolas, monospace" font-size="10" fill="#FFD000">Power BI • SQL</text>
    </g>

    <g transform="translate(490, 355)">
      <rect width="220" height="85" rx="8" fill="#0C1A2D" stroke="#1E3A5F" stroke-width="1"/>
      <text x="20" y="30" font-family="'Segoe UI', sans-serif" font-size="14" font-weight="bold" fill="#FFFFFF">Financial Dashboards</text>
      <text x="20" y="52" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8AB4D4">Profitability &amp; KPI Tracking</text>
      <text x="20" y="68" font-family="Consolas, monospace" font-size="10" fill="#E06666">Tableau • Excel</text>
    </g>

    <g transform="translate(740, 355)">
      <rect width="220" height="85" rx="8" fill="#0C1A2D" stroke="#1E3A5F" stroke-width="1"/>
      <text x="20" y="30" font-family="'Segoe UI', sans-serif" font-size="14" font-weight="bold" fill="#FFFFFF">Customer Churn Model</text>
      <text x="20" y="52" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8AB4D4">Predictive Data Pipeline</text>
      <text x="20" y="68" font-family="Consolas, monospace" font-size="10" fill="#4FACFE">Python • pandas</text>
    </g>
  </g>

  <g transform="translate(0, 15)">
    <g transform="translate(420, 475)">
      <circle cx="12" cy="12" r="12" fill="#11294A" stroke="#00F2FE" stroke-width="1"/>
      <text x="12" y="16" text-anchor="middle" font-family="Arial, sans-serif" font-size="12" font-weight="bold" fill="#00F2FE">in</text>
      <text x="30" y="16" font-family="'Segoe UI', sans-serif" font-size="12" fill="#CFEFFF">linkedin/in/AyaAhmed</text>
    </g>

    <g transform="translate(640, 475)">
      <circle cx="12" cy="12" r="12" fill="#11294A" stroke="#4FACFE" stroke-width="1"/>
      <path d="M7 8 h10 v8 h-10 z M7 8 l5 4.5 l5 -4.5" fill="none" stroke="#4FACFE" stroke-width="1"/>
      <text x="30" y="16" font-family="'Segoe UI', sans-serif" font-size="12" fill="#CFEFFF">aya.data@email.com</text>
    </g>
  </g>
</svg>
