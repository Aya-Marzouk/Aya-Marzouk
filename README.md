<svg width="1200" height="520" viewBox="0 0 1200 520" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#07111E">
        <animate attributeName="stop-color" values="#07111E;#0C1E36;#07111E" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0E2945">
        <animate attributeName="stop-color" values="#0E2945;#071626;#0E2945" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F2FE"/>
      <stop offset="50%" stop-color="#4FACFE"/>
      <stop offset="100%" stop-color="#FFFFFF"/>
    </linearGradient>

    <linearGradient id="barGrad" x1="0%" y1="100%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#00F2FE" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#4FACFE" stop-opacity="0.5"/>
    </linearGradient>

    <radialGradient id="glow" cx="50%" cy="30%" r="45%">
      <stop offset="0%" stop-color="#00F2FE" stop-opacity="0.2"/>
      <stop offset="100%" stop-color="#00F2FE" stop-opacity="0"/>
    </radialGradient>

    <clipPath id="revealName">
      <rect x="0" y="0" width="0" height="520">
        <animate attributeName="width" from="0" to="1200" begin="0.1s" dur="1.1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>

    <clipPath id="revealSub">
      <rect x="0" y="0" width="0" height="520">
        <animate attributeName="width" from="0" to="1200" begin="1.2s" dur="1.2s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      </rect>
    </clipPath>
  </defs>

  <rect width="1200" height="520" fill="url(#bg)"/>
  <circle cx="600" cy="140" r="280" fill="url(#glow)"/>

  <g fill="#00F2FE">
    <circle cx="150" cy="480" r="1.5" opacity="0.5">
      <animate attributeName="cy" values="480;20" dur="8s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.6;0" dur="8s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1050" cy="480" r="2" opacity="0.4">
      <animate attributeName="cy" values="480;50" dur="7s" begin="2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0;0.5;0" dur="7s" begin="2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <g transform="translate(50, 40)">
    <rect x="0" y="300" width="12" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="120" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="300" to="180" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="height" values="120;80;120" dur="4s" begin="1.3s" repeatCount="indefinite"/>
      <animate attributeName="y" values="180;220;180" dur="4s" begin="1.3s" repeatCount="indefinite"/>
    </rect>
    <rect x="18" y="300" width="12" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="170" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="300" to="130" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="height" values="170;130;170" dur="4s" begin="1.45s" repeatCount="indefinite"/>
      <animate attributeName="y" values="130;170;130" dur="4s" begin="1.45s" repeatCount="indefinite"/>
    </rect>
    <rect x="36" y="300" width="12" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="90" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="300" to="210" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="height" values="90;120;90" dur="4s" begin="1.6s" repeatCount="indefinite"/>
      <animate attributeName="y" values="210;180;210" dur="4s" begin="1.6s" repeatCount="indefinite"/>
    </rect>
  </g>

  <g transform="translate(1100, 40)">
    <rect x="0" y="300" width="12" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="90" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="300" to="210" begin="0.3s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="height" values="90;130;90" dur="4s" begin="1.3s" repeatCount="indefinite"/>
      <animate attributeName="y" values="210;170;210" dur="4s" begin="1.3s" repeatCount="indefinite"/>
    </rect>
    <rect x="18" y="300" width="12" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="170" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="300" to="130" begin="0.45s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="height" values="170;110;170" dur="4s" begin="1.45s" repeatCount="indefinite"/>
      <animate attributeName="y" values="130;190;130" dur="4s" begin="1.45s" repeatCount="indefinite"/>
    </rect>
    <rect x="36" y="300" width="12" height="0" fill="url(#barGrad)" rx="3">
      <animate attributeName="height" from="0" to="110" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="y" from="300" to="190" begin="0.6s" dur="1s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
      <animate attributeName="height" values="110;80;110" dur="4s" begin="1.6s" repeatCount="indefinite"/>
      <animate attributeName="y" values="190;220;190" dur="4s" begin="1.6s" repeatCount="indefinite"/>
    </rect>
  </g>

  <g clip-path="url(#revealName)">
    <text x="600" y="110" text-anchor="middle" font-family="'Segoe UI', Roboto, Helvetica, sans-serif"
          font-size="64" font-weight="900" fill="url(#nameGrad)" letter-spacing="5">
      AYA AHMED
    </text>
  </g>

  <rect x="600" y="132" width="0" height="4" rx="2" fill="#00F2FE" transform="translate(-150,0)">
    <animate attributeName="width" from="0" to="300" begin="1.1s" dur="0.6s" fill="freeze" calcMode="spline" keySplines="0.22 1 0.36 1"/>
  </rect>

  <g clip-path="url(#revealSub)">
    <text x="600" y="175" text-anchor="middle" font-family="Consolas, 'Courier New', monospace"
          font-size="19" font-weight="600" fill="#E2F5FF" letter-spacing="2">
      DATA ANALYST &#160;|&#160; BUSINESS INTELLIGENCE &amp; DATA VISUALIZATION
    </text>
  </g>

  <g opacity="0">
    <text x="600" y="210" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-style="italic"
          font-size="14" fill="#8AB4D4">
      "Turning raw data into dashboards that drive decisions"
    </text>
    <animate attributeName="opacity" from="0" to="1" begin="2.2s" dur="0.8s" fill="freeze"/>
  </g>

  <g opacity="0">
    <g transform="translate(360, 245)">
      <rect x="0" y="0" width="80" height="30" rx="15" fill="#11294A" stroke="#00F2FE" stroke-width="1.2" />
      <text x="40" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#00F2FE">SQL</text>
      <animateTransform attributeName="transform" type="translate" values="360,245; 360,240; 360,245" dur="3s" repeatCount="indefinite" begin="0s"/>
    </g>

    <g transform="translate(455, 245)">
      <rect x="0" y="0" width="110" height="30" rx="15" fill="#11294A" stroke="#FFD000" stroke-width="1.2" />
      <text x="55" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#FFD000">POWER BI</text>
      <animateTransform attributeName="transform" type="translate" values="455,245; 455,250; 455,245" dur="3.5s" repeatCount="indefinite" begin="0.5s"/>
    </g>

    <g transform="translate(580, 245)">
      <rect x="0" y="0" width="95" height="30" rx="15" fill="#11294A" stroke="#4FACFE" stroke-width="1.2" />
      <text x="47.5" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#4FACFE">PYTHON</text>
      <animateTransform attributeName="transform" type="translate" values="580,245; 580,239; 580,245" dur="3.2s" repeatCount="indefinite" begin="0.2s"/>
    </g>

    <g transform="translate(690, 245)">
      <rect x="0" y="0" width="100" height="30" rx="15" fill="#11294A" stroke="#E06666" stroke-width="1.2" />
      <text x="50" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#E06666">TABLEAU</text>
      <animateTransform attributeName="transform" type="translate" values="690,245; 690,249; 690,245" dur="3.8s" repeatCount="indefinite" begin="0.7s"/>
    </g>

    <g transform="translate(805, 245)">
      <rect x="0" y="0" width="85" height="30" rx="15" fill="#11294A" stroke="#21A366" stroke-width="1.2" />
      <text x="42.5" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#21A366">EXCEL</text>
      <animateTransform attributeName="transform" type="translate" values="805,245; 805,241; 805,245" dur="3.4s" repeatCount="indefinite" begin="0.4s"/>
    </g>
    <animate attributeName="opacity" from="0" to="1" begin="2.4s" dur="0.6s" fill="freeze"/>
  </g>


  <g opacity="0" transform="translate(0, 20)">
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

    <animate attributeName="opacity" from="0" to="1" begin="2.8s" dur="0.8s" fill="freeze"/>
  </g>


  <g opacity="0" transform="translate(0, 15)">
    <g transform="translate(440, 475)">
      <circle cx="12" cy="12" r="12" fill="#11294A" stroke="#00F2FE" stroke-width="1"/>
      <text x="12" y="16" text-anchor="middle" font-family="Arial, sans-serif" font-size="12" font-weight="bold" fill="#00F2FE">in</text>
      <text x="30" y="16" font-family="'Segoe UI', sans-serif" font-size="12" fill="#CFEFFF">linkedin/in/AyaAhmed</text>
    </g>

    <g transform="translate(620, 475)">
      <circle cx="12" cy="12" r="12" fill="#11294A" stroke="#4FACFE" stroke-width="1"/>
      <path d="M7 8 h10 v8 h-10 z M7 8 l5 4.5 l5 -4.5" fill="none" stroke="#4FACFE" stroke-width="1"/>
      <text x="30" y="16" font-family="'Segoe UI', sans-serif" font-size="12" fill="#CFEFFF">aya.data@email.com</text>
    </g>

    <animate attributeName="opacity" from="0" to="1" begin="3.2s" dur="0.8s" fill="freeze"/>
  </g>

</svg>
