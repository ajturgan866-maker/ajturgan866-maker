<svg width="1200" height="520" viewBox="0 0 1200 520"
     xmlns="http://www.w3.org/2000/svg">

<defs>

  <!-- ================= BACKGROUND ================= -->

  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0" stop-color="#030712"/>
    <stop offset=".5" stop-color="#0b1026"/>
    <stop offset="1" stop-color="#160b29"/>
  </linearGradient>

  <linearGradient id="cyan" x1="0" x2="1">
    <stop stop-color="#67e8f9"/>
    <stop offset="1" stop-color="#22d3ee"/>
  </linearGradient>

  <linearGradient id="purple" x1="0" x2="1">
    <stop stop-color="#c084fc"/>
    <stop offset="1" stop-color="#818cf8"/>
  </linearGradient>


  <!-- ================= PLANET GRADIENTS ================= -->

  <radialGradient id="sun">
    <stop stop-color="#fff7ae"/>
    <stop offset=".45" stop-color="#fbbf24"/>
    <stop offset="1" stop-color="#ea580c"/>
  </radialGradient>

  <radialGradient id="bluePlanet">
    <stop stop-color="#a5f3fc"/>
    <stop offset=".5" stop-color="#2563eb"/>
    <stop offset="1" stop-color="#172554"/>
  </radialGradient>

  <radialGradient id="purplePlanet">
    <stop stop-color="#f3e8ff"/>
    <stop offset=".5" stop-color="#a855f7"/>
    <stop offset="1" stop-color="#4c1d95"/>
  </radialGradient>

  <radialGradient id="pinkPlanet">
    <stop stop-color="#fce7f3"/>
    <stop offset=".5" stop-color="#ec4899"/>
    <stop offset="1" stop-color="#831843"/>
  </radialGradient>

  <radialGradient id="cyanPlanet">
    <stop stop-color="#cffafe"/>
    <stop offset=".5" stop-color="#06b6d4"/>
    <stop offset="1" stop-color="#164e63"/>
  </radialGradient>


  <!-- ================= GLOW ================= -->

  <filter id="glow">
    <feGaussianBlur stdDeviation="4" result="b"/>
    <feMerge>
      <feMergeNode in="b"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>

  <filter id="bigGlow">
    <feGaussianBlur stdDeviation="16"/>
  </filter>


  <!-- ========================================================= -->
  <!-- TYPEWRITER CLIPS (40s loop, no dead intervals)            -->
  <!-- ========================================================= -->

  <!-- BLOCK 1: О себе -->
  <clipPath id="textClip1">
    <rect x="70" y="125" width="0" height="40">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;500;500;0;0" keyTimes="0;0.01;0.06;0.245;0.25;1"/>
    </rect>
    <rect x="70" y="210" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;220;220;0;0" keyTimes="0;0.065;0.10;0.245;0.25;1"/>
    </rect>
    <rect x="70" y="250" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;380;380;0;0" keyTimes="0;0.105;0.15;0.245;0.25;1"/>
    </rect>
    <rect x="70" y="305" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;540;540;0;0" keyTimes="0;0.155;0.22;0.245;0.25;1"/>
    </rect>
  </clipPath>

  <!-- BLOCK 2: Стек -->
  <clipPath id="textClip2">
    <rect x="70" y="125" width="0" height="40">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;450;450;0;0" keyTimes="0;0.25;0.255;0.495;0.50;1"/>
    </rect>
    <rect x="70" y="210" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;220;220;0;0" keyTimes="0;0.26;0.29;0.495;0.50;1"/>
    </rect>
    <rect x="70" y="250" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;260;260;0;0" keyTimes="0;0.295;0.33;0.495;0.50;1"/>
    </rect>
    <rect x="70" y="290" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;190;190;0;0" keyTimes="0;0.335;0.365;0.495;0.50;1"/>
    </rect>
    <rect x="70" y="330" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;180;180;0;0" keyTimes="0;0.37;0.40;0.495;0.50;1"/>
    </rect>
    <rect x="70" y="370" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;110;110;0;0" keyTimes="0;0.405;0.43;0.495;0.50;1"/>
    </rect>
  </clipPath>

  <!-- BLOCK 3: Направление -->
  <clipPath id="textClip3">
    <rect x="70" y="125" width="0" height="40">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;400;400;0;0" keyTimes="0;0.50;0.505;0.745;0.75;1"/>
    </rect>
    <rect x="70" y="210" width="0" height="30">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;330;330;0;0" keyTimes="0;0.51;0.55;0.745;0.75;1"/>
    </rect>
    <rect x="70" y="255" width="0" height="30">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;190;190;0;0" keyTimes="0;0.555;0.59;0.745;0.75;1"/>
    </rect>
    <rect x="70" y="300" width="0" height="30">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;340;340;0;0" keyTimes="0;0.595;0.64;0.745;0.75;1"/>
    </rect>
    <rect x="70" y="355" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;310;310;0;0" keyTimes="0;0.645;0.69;0.745;0.75;1"/>
    </rect>
  </clipPath>

  <!-- BLOCK 4: Проекты и цели -->
  <clipPath id="textClip4">
    <rect x="70" y="125" width="0" height="40">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;450;450;0;0" keyTimes="0;0.75;0.755;0.99;1;1"/>
    </rect>
    <rect x="70" y="210" width="0" height="28">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;150;150;0;0" keyTimes="0;0.76;0.79;0.99;1;1"/>
    </rect>
    <rect x="70" y="245" width="0" height="25">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;260;260;0;0" keyTimes="0;0.795;0.83;0.99;1;1"/>
    </rect>
    <rect x="70" y="275" width="0" height="25">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;210;210;0;0" keyTimes="0;0.835;0.865;0.99;1;1"/>
    </rect>
    <rect x="70" y="320" width="0" height="25">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;430;430;0;0" keyTimes="0;0.87;0.91;0.99;1;1"/>
    </rect>
    <rect x="70" y="350" width="0" height="25">
      <animate attributeName="width" dur="40s" repeatCount="indefinite" values="0;0;280;280;0;0" keyTimes="0;0.915;0.945;0.99;1;1"/>
    </rect>
  </clipPath>

</defs>


<!-- ========================================================= -->
<!-- BACKGROUND -->
<!-- ========================================================= -->

<rect width="1200" height="520" rx="22" fill="url(#bg)"/>
<circle cx="925" cy="260" r="220" fill="#6366f1" opacity=".08" filter="url(#bigGlow)"/>


<!-- ========================================================= -->
<!-- STARS -->
<!-- ========================================================= -->

<g fill="#fff" opacity=".8">
  <circle cx="35" cy="35" r="1"/>
  <circle cx="80" cy="115" r="1.3"/>
  <circle cx="145" cy="55" r="1"/>
  <circle cx="210" cy="140" r="1.2"/>
  <circle cx="275" cy="45" r="1"/>
  <circle cx="335" cy="95" r="1.3"/>
  <circle cx="400" cy="40" r="1"/>
  <circle cx="470" cy="125" r="1.2"/>
  <circle cx="535" cy="55" r="1"/>
  <circle cx="600" cy="105" r="1.3"/>
  <circle cx="680" cy="45" r="1"/>
  <circle cx="745" cy="110" r="1.2"/>
  <circle cx="810" cy="35" r="1"/>
  <circle cx="875" cy="80" r="1.3"/>
  <circle cx="945" cy="35" r="1"/>
  <circle cx="1010" cy="90" r="1.2"/>
  <circle cx="1080" cy="45" r="1"/>
  <circle cx="1160" cy="105" r="1.2"/>
  <circle cx="35" cy="470" r="1.2"/>
  <circle cx="110" cy="425" r="1"/>
  <circle cx="180" cy="480" r="1.3"/>
  <circle cx="260" cy="440" r="1"/>
  <circle cx="335" cy="490" r="1.2"/>
  <circle cx="420" cy="445" r="1"/>
  <circle cx="500" cy="480" r="1.2"/>
  <circle cx="580" cy="435" r="1"/>
  <circle cx="710" cy="480" r="1.2"/>
  <circle cx="790" cy="430" r="1"/>
  <circle cx="860" cy="490" r="1.3"/>
  <circle cx="950" cy="445" r="1"/>
  <circle cx="1030" cy="480" r="1.2"/>
  <circle cx="1110" cy="425" r="1"/>
  <circle cx="1170" cy="470" r="1.3"/>
</g>


<!-- ========================================================= -->
<!-- LEFT PANEL -->
<!-- ========================================================= -->

<rect x="40" y="35" width="590" height="450" rx="18" fill="#050916" opacity=".88" stroke="#263247"/>


<!-- ========================================================= -->
<!-- TEXT BLOCK 1: О себе -->
<!-- ========================================================= -->

<g>
  <animate attributeName="opacity" dur="40s" repeatCount="indefinite" values="0;1;1;0;0" keyTimes="0;0.01;0.245;0.25;1"/>

  <text x="70" y="95" font-family="monospace" font-size="13" fill="#64748b">
    aiturgan.profile / 01_about
  </text>

  <g clip-path="url(#textClip1)">
    <text x="70" y="155" font-family="monospace" font-size="32" font-weight="bold" fill="url(#cyan)">
      &gt; Белекова Айтурган
    </text>

    <line x1="70" y1="180" x2="590" y2="180" stroke="#334155"/>

    <text x="70" y="232" font-family="monospace" font-size="20" fill="#f8fafc">
      Student Developer
    </text>

    <text x="70" y="272" font-family="monospace" font-size="16" fill="#c084fc">
      Programming Technologies student
    </text>

    <text x="70" y="325" font-family="monospace" font-size="15" fill="#94a3b8">
      Kyrgyz-German Institute of Applied Informatics
    </text>
  </g>
</g>


<!-- ========================================================= -->
<!-- TEXT BLOCK 2: Чему учусь / стек -->
<!-- ========================================================= -->

<g>
  <animate attributeName="opacity" dur="40s" repeatCount="indefinite" values="0;0;1;1;0" keyTimes="0;0.25;0.255;0.495;0.50"/>

  <text x="70" y="95" font-family="monospace" font-size="13" fill="#64748b">
    aiturgan.profile / 02_stack
  </text>

  <g clip-path="url(#textClip2)">
    <text x="70" y="155" font-family="monospace" font-size="32" font-weight="bold" fill="url(#purple)">
      &gt; Tech Stack
    </text>

    <line x1="70" y1="180" x2="590" y2="180" stroke="#334155"/>

    <text x="70" y="232" font-family="monospace" font-size="18" fill="#67e8f9">
      Python Developer
    </text>

    <text x="70" y="272" font-family="monospace" font-size="18" fill="#cbd5e1">
      Java → currently learning
    </text>

    <text x="70" y="312" font-family="monospace" font-size="18" fill="#cbd5e1">
      PostgreSQL
    </text>

    <text x="70" y="352" font-family="monospace" font-size="18" fill="#cbd5e1">
      Git / GitHub
    </text>

    <text x="70" y="392" font-family="monospace" font-size="18" fill="#cbd5e1">
      HTML
    </text>
  </g>
</g>


<!-- ========================================================= -->
<!-- TEXT BLOCK 3: Направление -->
<!-- ========================================================= -->

<g>
  <animate attributeName="opacity" dur="40s" repeatCount="indefinite" values="0;0;1;1;0" keyTimes="0;0.50;0.505;0.745;0.75"/>

  <text x="70" y="95" font-family="monospace" font-size="13" fill="#64748b">
    aiturgan.profile / 03_focus
  </text>

  <g clip-path="url(#textClip3)">
    <text x="70" y="155" font-family="monospace" font-size="32" font-weight="bold" fill="url(#cyan)">
      &gt; Direction
    </text>

    <line x1="70" y1="180" x2="590" y2="180" stroke="#334155"/>

    <text x="70" y="235" font-family="monospace" font-size="20" fill="#67e8f9">
      Backend Development
    </text>

    <text x="70" y="280" font-family="monospace" font-size="20" fill="#cbd5e1">
      Databases
    </text>

    <text x="70" y="325" font-family="monospace" font-size="20" fill="#cbd5e1">
      Software Architecture
    </text>

    <text x="70" y="380" font-family="monospace" font-size="18" fill="#c084fc">
      Building real projects
    </text>
  </g>
</g>


<!-- ========================================================= -->
<!-- TEXT BLOCK 4: Проекты и цели -->
<!-- ========================================================= -->

<g>
  <animate attributeName="opacity" dur="40s" repeatCount="indefinite" values="0;0;1;1;0" keyTimes="0;0.75;0.755;0.99;1"/>

  <text x="70" y="95" font-family="monospace" font-size="13" fill="#64748b">
    aiturgan.profile / 04_goals
  </text>

  <g clip-path="url(#textClip4)">
    <text x="70" y="155" font-family="monospace" font-size="32" font-weight="bold" fill="url(#purple)">
      &gt; Projects &amp; Goals
    </text>

    <line x1="70" y1="180" x2="590" y2="180" stroke="#334155"/>

    <text x="70" y="232" font-family="monospace" font-size="18" fill="#67e8f9">
      MiniPOS
    </text>

    <text x="70" y="267" font-family="monospace" font-size="15" fill="#94a3b8">
      JavaFX + PostgreSQL
    </text>

    <text x="70" y="297" font-family="monospace" font-size="15" fill="#94a3b8">
      Desktop application
    </text>

    <text x="70" y="342" font-family="monospace" font-size="16" fill="#cbd5e1">
      Goal: Become a strong Backend Developer
    </text>

    <text x="70" y="372" font-family="monospace" font-size="16" fill="#cbd5e1">
      Build useful software
    </text>
  </g>
</g>


<!-- ========================================================= -->
<!-- PLANETARY SYSTEM (Правая часть)                           -->
<!-- ========================================================= -->

<ellipse cx="920" cy="260" rx="100" ry="62" fill="none" stroke="#38bdf8" opacity=".18"/>
<ellipse cx="920" cy="260" rx="145" ry="88" fill="none" stroke="#a855f7" opacity=".18"/>
<ellipse cx="920" cy="260" rx="190" ry="115" fill="none" stroke="#22d3ee" opacity=".18"/>
<ellipse cx="920" cy="260" rx="235" ry="145" fill="none" stroke="#6366f1" opacity=".18"/>

<circle cx="920" cy="260" r="70" fill="#f59e0b" opacity=".08" filter="url(#bigGlow)"/>
<circle cx="920" cy="260" r="40" fill="url(#sun)" filter="url(#glow)"/>

<circle cx="920" cy="260" r="50" fill="none" stroke="#fbbf24" opacity=".3">
  <animate attributeName="r" values="44;58;44" dur="4s" repeatCount="indefinite"/>
  <animate attributeName="opacity" values=".45;.05;.45" dur="4s" repeatCount="indefinite"/>
</circle>

<g>
  <animateTransform attributeName="transform" type="rotate" from="0 920 260" to="360 920 260" dur="8s" repeatCount="indefinite"/>
  <circle cx="1020" cy="260" r="12" fill="url(#bluePlanet)" filter="url(#glow)"/>
  <circle cx="1016" cy="256" r="3" fill="#cffafe"/>
</g>

<g>
  <animateTransform attributeName="transform" type="rotate" from="360 920 260" to="0 920 260" dur="13s" repeatCount="indefinite"/>
  <circle cx="1065" cy="260" r="21" fill="url(#purplePlanet)" filter="url(#glow)"/>
  <ellipse cx="1065" cy="260" rx="37" ry="10" fill="none" stroke="#c084fc" stroke-width="4" opacity=".55"/>
  <ellipse cx="1065" cy="260" rx="31" ry="8" fill="none" stroke="#f3e8ff" opacity=".6"/>
</g>

<g>
  <animateTransform attributeName="transform" type="rotate" from="0 920 260" to="360 920 260" dur="18s" repeatCount="indefinite"/>
  <circle cx="1110" cy="260" r="11" fill="url(#cyanPlanet)" filter="url(#glow)"/>
</g>

<g>
  <animateTransform attributeName="transform" type="rotate" from="360 920 260" to="0 920 260" dur="25s" repeatCount="indefinite"/>
  <circle cx="920" cy="405" r="24" fill="url(#pinkPlanet)" filter="url(#glow)"/>
  <ellipse cx="920" cy="405" rx="18" ry="5" fill="#fbcfe8" opacity=".2"/>
</g>

<g>
  <animateTransform attributeName="transform" type="rotate" from="0 1065 260" to="360 1065 260" dur="3s" repeatCount="indefinite"/>
  <circle cx="1090" cy="260" r="5" fill="#cbd5e1" filter="url(#glow)"/>
</g>

<g>
  <animateTransform attributeName="transform" type="rotate" from="0 920 260" to="360 920 260" dur="6s" repeatCount="indefinite"/>
  <circle cx="920" cy="360" r="6" fill="#818cf8" filter="url(#glow)"/>
</g>

<g fill="#67e8f9" filter="url(#glow)">
  <circle cx="745" cy="145" r="2"/>
  <circle cx="1115" cy="130" r="1.5"/>
  <circle cx="1150" cy="350" r="2"/>
  <circle cx="755" cy="390" r="1.5"/>
  <circle cx="1035" cy="435" r="1.5"/>
</g>


<!-- ========================================================= -->
<!-- FOOTER -->
<!-- ========================================================= -->

<text x="665" y="475" font-family="monospace" font-size="12" fill="#475569">SYSTEM.STATUS</text>
<text x="790" y="475" font-family="monospace" font-size="12" fill="#22c55e">● ONLINE</text>
<text x="895" y="475" font-family="monospace" font-size="12" fill="#22d3ee">● BUILDING</text>
<text x="1025" y="475" font-family="monospace" font-size="12" fill="#a78bfa">● BACKEND</text>

</svg>
