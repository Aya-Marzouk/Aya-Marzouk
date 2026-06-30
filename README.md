<svg width="1200" height="520" viewBox="0 0 1200 520" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Background Gradient -->
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#07111E"/>
      <stop offset="100%" stop-color="#0E2945"/>
    </linearGradient>

    <!-- Name Gradient -->
    <linearGradient id="nameGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00F2FE"/>
      <stop offset="50%" stop-color="#4FACFE"/>
      <stop offset="100%" stop-color="#FFFFFF"/>
    </linearGradient>

    <!-- Bar Chart Gradient -->
    <linearGradient id="barGrad" x1="0%" y1="100%" x2="0%" y2="0%">
      <stop offset="0%" stop-color="#00F2FE" stop-opacity="0.05"/>
      <stop offset="100%" stop-color="#4FACFE" stop-opacity="0.5"/>
    </linearGradient>

    <!-- CSS Animation Styles -->
    <style>
      @keyframes pulseBars {
        0% { transform: scaleY(1); }
        50% { transform: scaleY(0.7); }
        100% { transform: scaleY(1); }
      }
      @keyframes floatSkill1 { 0%, 100% { transform: translate(360px, 245px); } 50% { transform: translate(360px, 238px); } }
      @keyframes floatSkill2 { 0%, 100% { transform: translate(455px, 245px); } 50% { transform: translate(455px, 252px); } }
      @keyframes floatSkill3 { 0%, 100% { transform: translate(580px, 245px); } 50% { transform: translate(580px, 239px); } }
      @keyframes floatSkill4 { 0%, 100% { transform: translate(690px, 245px); } 50% { transform: translate(690px, 251px); } }
      @keyframes floatSkill5 { 0%, 100% { transform: translate(805px, 245px); } 50% { transform: translate(805px, 240px); } }
      
      .bar-anim { transform-origin: bottom; animation: pulseBars 3s infinite ease-in-out; }
      .bar-delay1 { animation-delay: 0.3s; }
      .bar-delay2 { animation-delay: 0.6s; }
      
      .skill-1 { animation: floatSkill1 3s infinite ease-in-out; }
      .skill-2 { animation: floatSkill2 3.5s infinite ease-in-out; }
      .skill-3 { animation: floatSkill3 3.2s infinite ease-in-out; }
      .skill-4 { animation: floatSkill4 3.8s infinite ease-in-out; }
      .skill-5 { animation: floatSkill5 3.4s infinite ease-in-out; }
    </style>
  </defs>

  <!-- Background -->
  <rect width="1200" height="520" fill="url(#bg)"/>

  <!-- Left Side Animated Bars -->
  <g transform="translate(50, 40)">
    <rect x="0" y="180" width="12" height="120" fill="url(#barGrad)" rx="3" class="bar-anim"/>
    <rect x="18" y="130" width="12" height="170" fill="url(#barGrad)" rx="3" class="bar-anim bar-delay1"/>
    <rect x="36" y="210" width="12" height="90" fill="url(#barGrad)" rx="3" class="bar-anim bar-delay2"/>
  </g>

  <!-- Right Side Animated Bars -->
  <g transform="translate(1100, 40)">
    <rect x="0" y="210" width="12" height="90" fill="url(#barGrad)" rx="3" class="bar-anim bar-delay1"/>
    <rect x="18" y="130" width="12" height="170" fill="url(#barGrad)" rx="3" class="bar-anim"/>
    <rect x="36" y="190" width="12" height="110" fill="url(#barGrad)" rx="3" class="bar-anim bar-delay2"/>
  </g>

  <!-- Main Name Title -->
  <g>
    <text x="600" y="110" text-anchor="middle" font-family="'Segoe UI', Roboto, Helvetica, sans-serif"
          font-size="64" font-weight="900" fill="url(#nameGrad)" letter-spacing="5">
      AYA AHMED
    </text>
  </g>

  <!-- Underline Line -->
  <rect x="450" y="132" width="300" height="4" rx="2" fill="#00F2FE" />

  <!-- Subtitle -->
  <g>
    <text x="600" y="175" text-anchor="middle" font-family="Consolas, 'Courier New', monospace"
          font-size="19" font-weight="600" fill="#E2F5FF" letter-spacing="2">
      DATA ANALYST &#160;|&#160; BUSINESS INTELLIGENCE &amp; DATA VISUALIZATION
    </text>
  </g>

  <!-- Tagline -->
  <g>
    <text x="600" y="210" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-style="italic"
          font-size="14" fill="#8AB4D4">
      "Turning raw data into dashboards that drive decisions"
    </text>
  </g>

  <!-- ================= MOVING SKILLS SECTION ================= -->
  <g>
    <!-- Skill 1: SQL -->
    <g class="skill-1">
      <rect x="0" y="0" width="80" height="30" rx="15" fill="#11294A" stroke="#00F2FE" stroke-width="1.2" />
      <text x="40" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#00F2FE">SQL</text>
    </g>

    <!-- Skill 2: Power BI -->
    <g class="skill-2">
      <rect x="0" y="0" width="110" height="30" rx="15" fill="#11294A" stroke="#FFD000" stroke-width="1.2" />
      <text x="55" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#FFD000">POWER BI</text>
    </g>

    <!-- Skill 3: Python -->
    <g class="skill-3">
      <rect x="0" y="0" width="95" height="30" rx="15" fill="#11294A" stroke="#4FACFE" stroke-width="1.2" />
      <text x="47.5" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#4FACFE">PYTHON</text>
    </g>

    <!-- Skill 4: Tableau -->
    <g class="skill-4">
      <rect x="0" y="0" width="100" height="30" rx="15" fill="#11294A" stroke="#E06666" stroke-width="1.2" />
      <text x="50" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#E06666">TABLEAU</text>
    </g>

    <!-- Skill 5: Excel -->
    <g class="skill-5">
      <rect x="0" y="0" width="85" height="30" rx="15" fill="#11294A" stroke="#21A366" stroke-width="1.2" />
      <text x="42.5" y="19" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" font-weight="bold" fill="#21A366">EXCEL</text>
    </g>
  </g>

  <!-- ================= PROJECTS SECTION ================= -->
  <g transform="translate(0, 20)">
    <text x="600" y="325" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="16" font-weight="bold" fill="#4FACFE" letter-spacing="3">FEATURED PROJECTS</text>
    <line x1="550" y1="335" x2="650" y2="335" stroke="#4FACFE" stroke-width="1" opacity="0.5"/>

    <!-- Project 1 Card -->
    <g transform="translate(240, 355)">
      <rect width="220" height="85" rx="8" fill="#0C1A2D" stroke="#1E3A5F" stroke-width="1"/>
      <text x="20" y="30" font-family="'Segoe UI', sans-serif" font-size="14" font-weight="bold" fill="#FFFFFF">E-Commerce Insights</text>
      <text x="20" y="52" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8AB4D4">Sales &amp; Cohort Analysis</text>
      <text x="20" y="68" font-family="Consolas, monospace" font-size="10" fill="#FFD000">Power BI • SQL</text>
    </g>

    <!-- Project 2 Card -->
    <g transform="translate(490, 355)">
      <rect width="220" height="85" rx="8" fill="#0C1A2D" stroke="#1E3A5F" stroke-width="1"/>
      <text x="20" y="30" font-family="'Segoe UI', sans-serif" font-size="14" font-weight="bold" fill="#FFFFFF">Financial Dashboards</text>
      <text x="20" y="52" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8AB4D4">Profitability &amp; KPI Tracking</text>
      <text x="20" y="68" font-family="Consolas, monospace" font-size="10" fill="#E06666">Tableau • Excel</text>
    </g>

    <!-- Project 3 Card -->
    <g transform="translate(740, 355)">
      <rect width="220" height="85" rx="8" fill="#0C1A2D" stroke="#1E3A5F" stroke-width="1"/>
      <text x="20" y="30" font-family="'Segoe UI', sans-serif" font-size="14" font-weight="bold" fill="#FFFFFF">Customer Churn Model</text>
      <text x="20" y="52" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8AB4D4">Predictive Data Pipeline</text>
      <text x="20" y="68" font-family="Consolas, monospace" font-size="10" fill="#4FACFE">Python • pandas</text>
    </g>
  </g>

  <!-- ================= CONTACT / SOCIAL SECTION ================= -->
  <g transform="translate(0, 15)">
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
  </g>
</svg>
