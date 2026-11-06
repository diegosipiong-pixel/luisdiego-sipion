
<svg xmlns="http://www.w3.org/2000/svg"
     viewBox="0 0 1000 340"
     width="1000"
     height="340"
     role="img"
     aria-labelledby="title desc">

  <title id="title">Luis Diego Sipion Galvez | VS Code Portfolio</title>
  <desc id="desc">Portfolio de Ingeniería de Software, IA y Ciberseguridad con diseño inspirado en Visual Studio Code.</desc>

  <defs>
    <!-- COLORES DEL EDITOR -->
    <linearGradient id="cubeTop" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#45B7F5"/>
      <stop offset="100%" stop-color="#1765C5"/>
    </linearGradient>

    <linearGradient id="cubeLeft" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#2456D9"/>
      <stop offset="100%" stop-color="#272E9E"/>
    </linearGradient>

    <linearGradient id="cubeRight" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#29C6DC"/>
      <stop offset="100%" stop-color="#1689B5"/>
    </linearGradient>

    <linearGradient id="neon" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22D3EE"/>
      <stop offset="50%" stop-color="#3B82F6"/>
      <stop offset="100%" stop-color="#A855F7"/>
    </linearGradient>

    <linearGradient id="titleAccent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#A855F7"/>
    </linearGradient>

    <radialGradient id="ambient">
      <stop offset="0%" stop-color="#2563EB" stop-opacity=".18"/>
      <stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
    </radialGradient>

    <clipPath id="frame">
      <rect width="1000" height="340" rx="12"/>
    </clipPath>

    <clipPath id="cubeClip">
      <path d="M257 17 L490 145 L490 369 L257 495 L22 369 L22 145 Z"/>
    </clipPath>
  </defs>

  <style>
    .mono {
      font-family: Consolas, 'Courier New', monospace;
    }

    .sans {
      font-family: 'Segoe UI', Arial, sans-serif;
    }

    .float {
      animation: float 5s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-5px); }
    }

    .light {
      animation: travel 4s linear infinite;
    }

    @keyframes travel {
      to { stroke-dashoffset: -100; }
    }

    .cursor {
      animation: blink 1s steps(1) infinite;
    }

    @keyframes blink {
      50% { opacity: 0; }
    }

    .pulse {
      animation: pulse 2.5s ease-in-out infinite;
    }

    @keyframes pulse {
      0%, 100% { opacity: .5; }
      50% { opacity: 1; }
    }

    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; }
    }
  </style>

  <g clip-path="url(#frame)">

    <!-- FONDO DE LA VENTANA -->
    <rect width="1000" height="340" fill="#1E1E1E"/>

    <!-- BARRA SUPERIOR -->
    <rect width="1000" height="34" fill="#181818"/>

    <!-- LOGO VS CODE -->
    <g transform="translate(13 8)">
      <path d="M13 2 L2 12 L7 17 L18 7 L25 10 L25 22 L18 25 L7 15 L2 20 L13 30 L29 24 L29 8 Z"
            fill="#007ACC"
            transform="scale(.7)"/>
    </g>

    <text x="42" y="22"
          class="sans"
          font-size="12"
          fill="#CCCCCC">
      Luis Diego Sipion Galvez — Portfolio
    </text>

    <!-- CONTROLES DE VENTANA -->
    <g fill="#AAAAAA">
      <path d="M918 16 H930" stroke="#AAAAAA" stroke-width="1"/>
      <rect x="950" y="10" width="10" height="10"
            fill="none" stroke="#AAAAAA" stroke-width="1"/>
      <path d="M979 10 L989 20 M989 10 L979 20"
            stroke="#AAAAAA" stroke-width="1"/>
    </g>

    <!-- BARRA DE ACTIVIDAD -->
    <rect x="0" y="34" width="48" height="281" fill="#181818"/>

    <!-- EXPLORADOR -->
    <g stroke="#858585" fill="none" stroke-width="1.6">
      <rect x="15" y="51" width="17" height="14" rx="1"/>
      <path d="M15 55 H32"/>
      <circle cx="23.5" cy="91" r="8"/>
      <path d="M18 91 H29 M23.5 86 V96"/>
      <path d="M15 127 L23 119 L31 127 L23 135 Z"/>
      <path d="M15 162 H32 L23.5 176 Z"/>
      <circle cx="23" cy="210" r="8"/>
      <path d="M19 210 H27 M23 206 V214"/>
    </g>

    <rect x="0" y="43" width="2" height="29" fill="#007ACC"/>

    <!-- DIVISOR SIDEBAR -->
    <rect x="48" y="34" width="1" height="281" fill="#333333"/>

    <!-- PANEL EXPLORADOR -->
    <rect x="49" y="34" width="190" height="281" fill="#181818"/>

    <text x="64" y="57"
          class="sans"
          font-size="10"
          letter-spacing="1"
          fill="#BBBBBB">
      EXPLORER
    </text>

    <text x="65" y="82"
          class="mono"
          font-size="11"
          fill="#CCCCCC">
      ▼ PORTFOLIO
    </text>

    <!-- ARCHIVOS -->
    <g class="mono" font-size="10.5">
      <text x="82" y="108" fill="#E8AB53">◇</text>
      <text x="98" y="108" fill="#CCCCCC">index.ts</text>

      <text x="82" y="132" fill="#519ABA">◇</text>
      <text x="98" y="132" fill="#CCCCCC">about.md</text>

      <text x="82" y="156" fill="#C586C0">◇</text>
      <text x="98" y="156" fill="#CCCCCC">security.py</text>

      <text x="82" y="180" fill="#519ABA">◇</text>
      <text x="98" y="180" fill="#CCCCCC">projects.json</text>

      <text x="82" y="204" fill="#89CFF0">◇</text>
      <text x="98" y="204" fill="#CCCCCC">README.md</text>

      <text x="82" y="228" fill="#DCDCAA">◇</text>
      <text x="98" y="228" fill="#CCCCCC">contact.ts</text>
    </g>

    <!-- PANEL INFERIOR -->
    <path d="M49 251 H239" stroke="#333333"/>

    <text x="64" y="272"
          class="sans"
          font-size="10"
          fill="#BBBBBB">
      OUTLINE
    </text>

    <text x="64" y="294"
          class="sans"
          font-size="10"
          fill="#777777">
      TIMELINE
    </text>

    <!-- ÁREA DEL EDITOR -->
    <rect x="239" y="34" width="761" height="281" fill="#1E1E1E"/>

    <!-- PESTAÑA ACTIVA -->
    <rect x="239" y="34" width="145" height="32" fill="#1E1E1E"/>
    <rect x="239" y="34" width="145" height="2" fill="#007ACC"/>

    <text x="254" y="54"
          class="mono"
          font-size="11"
          fill="#E8AB53">
      ◇ index.ts
    </text>

    <path d="M384 34 V66" stroke="#333333"/>

    <!-- BREADCRUMB -->
    <text x="255" y="83"
          class="mono"
          font-size="9"
          fill="#858585">
      portfolio / src / index.ts
    </text>

    <!-- CÓDIGO -->
    <g class="mono" font-size="13">

      <g fill="#858585" text-anchor="end">
        <text x="272" y="117">1</text>
        <text x="272" y="143">2</text>
        <text x="272" y="169">3</text>
        <text x="272" y="195">4</text>
        <text x="272" y="221">5</text>
        <text x="272" y="247">6</text>
        <text x="272" y="273">7</text>
      </g>

      <text x="294" y="117" fill="#C586C0">const</text>
      <text x="339" y="117" fill="#9CDCFE">developer</text>
      <text x="413" y="117" fill="#D4D4D4">= {</text>

      <text x="311" y="143" fill="#9CDCFE">name:</text>
      <text x="367" y="143" fill="#CE9178">"Luis Diego Sipion Galvez"</text>

      <text x="311" y="169" fill="#9CDCFE">field:</text>
      <text x="367" y="169" fill="#CE9178">"Software Engineering"</text>

      <text x="311" y="195" fill="#9CDCFE">focus:</text>
      <text x="367" y="195" fill="#CE9178">"AI & Cybersecurity"</text>

      <text x="311" y="221" fill="#9CDCFE">location:</text>
      <text x="386" y="221" fill="#CE9178">"Lima, Peru"</text>

      <text x="294" y="247" fill="#D4D4D4">};</text>

      <text x="294" y="273" fill="#6A9955">// Building secure digital solutions.</text>
    </g>

    <!-- CURSOR -->
    <rect x="294" y="280" width="7" height="15"
          fill="#AEAFAD" class="cursor"/>

    <!-- PANEL DE IDENTIDAD VISUAL -->
    <g transform="translate(700 88)">

      <circle cx="115" cy="105" r="145"
              fill="url(#ambient)"
              class="pulse"/>

      <!-- CUBO -->
      <g transform="translate(0 0) scale(.43)">
        <g class="float">

          <path d="M257 17 L490 145 L257 273 L22 145 Z"
                fill="url(#cubeTop)"/>

          <path d="M22 145 L257 273 L257 495 L22 369 Z"
                fill="url(#cubeLeft)"/>

          <path d="M490 145 L257 273 L257 495 L490 369 Z"
                fill="url(#cubeRight)"/>

          <!-- SÍMBOLO BLANCO -->
          <g clip-path="url(#cubeClip)">

            <g fill="none"
               stroke="#FFFFFF"
               stroke-width="27"
               stroke-linecap="round"
               stroke-linejoin="round">
              <path d="M108 83 L219 145"/>
              <path d="M404 83 L294 145"/>
            </g>

            <ellipse cx="257" cy="163"
                     rx="59" ry="34"
                     fill="#FFFFFF"/>

            <ellipse cx="126" cy="313"
                     rx="32" ry="56"
                     transform="rotate(-28 126 313)"
                     fill="#FFFFFF"/>

            <path d="M145 334 L257 398"
                  fill="none"
                  stroke="#FFFFFF"
                  stroke-width="25"
                  stroke-linecap="round"/>

            <ellipse cx="387" cy="313"
                     rx="32" ry="56"
                     transform="rotate(28 387 313)"
                     fill="#FFFFFF"/>

            <path d="M367 334 L257 398"
                  fill="none"
                  stroke="#FFFFFF"
                  stroke-width="25"
                  stroke-linecap="round"/>
          </g>

          <!-- LUZ TRICOLOR -->
          <path
            d="M257 17 L490 145 L490 369 L257 495 L22 369 L22 145 Z"
            fill="none"
            stroke="#22D3EE"
            stroke-width="30"
            opacity=".2"
            pathLength="100"
            stroke-dasharray="22 78"
            class="light"/>

          <path
            d="M257 17 L490 145 L490 369 L257 495 L22 369 L22 145 Z"
            fill="none"
            stroke="url(#neon)"
            stroke-width="13"
            stroke-linecap="round"
            stroke-linejoin="round"
            pathLength="100"
            stroke-dasharray="22 78"
            class="light"/>

          <path
            d="M257 17 L490 145 L490 369 L257 495 L22 369 L22 145 Z"
            fill="none"
            stroke="#FFFFFF"
            stroke-width="3"
            pathLength="100"
            stroke-dasharray="8 92"
            class="light"/>
        </g>
      </g>

      <!-- TEXTO BAJO EL CUBO -->
      <text x="115" y="252"
            class="mono"
            font-size="10"
            letter-spacing="2"
            text-anchor="middle"
            fill="#858585">
        CODE · SECURE · INNOVATE
      </text>
    </g>

    <!-- STATUS BAR -->
    <rect x="0" y="315" width="1000" height="25" fill="#007ACC"/>

    <g class="sans" font-size="10" fill="#FFFFFF">
      <text x="12" y="332">⟨ ⟩</text>
      <text x="45" y="332">main*</text>
      <text x="105" y="332">✓ 0 errors</text>

      <text x="790" y="332">UTF-8</text>
      <text x="850" y="332">TypeScript</text>
      <text x="945" y="332" text-anchor="end">Ln 1, Col 1</text>
    </g>

  </g>
</svg>
