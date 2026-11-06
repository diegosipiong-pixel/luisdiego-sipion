
<svg xmlns="http://www.w3.org/2000/svg"
     xmlns:xlink="http://www.w3.org/1999/xlink"
     viewBox="0 0 1000 300"
     width="100%"
     role="img"
     aria-labelledby="title desc">

  <title id="title">Luis Diego Sipion Galvez</title>
  <desc id="desc">Ingeniería de Software, Inteligencia Artificial y Ciberseguridad</desc>

  <defs>
    <linearGradient id="bar" x1="0" x2="1">
      <stop offset="0" stop-color="#22D3EE"/>
      <stop offset=".5" stop-color="#3B82F6"/>
      <stop offset="1" stop-color="#8B5CF6"/>
    </linearGradient>

    <radialGradient id="purpleGlow">
      <stop offset="0" stop-color="#8B5CF6" stop-opacity=".35"/>
      <stop offset="1" stop-color="#8B5CF6" stop-opacity="0"/>
    </radialGradient>

    <radialGradient id="cyanGlow">
      <stop offset="0" stop-color="#22D3EE" stop-opacity=".22"/>
      <stop offset="1" stop-color="#22D3EE" stop-opacity="0"/>
    </radialGradient>

    <pattern id="dots" width="24" height="24" patternUnits="userSpaceOnUse">
      <circle cx="2" cy="2" r="1" fill="#30363D"/>
    </pattern>

    <clipPath id="frame">
      <rect width="1000" height="300" rx="18"/>
    </clipPath>
  </defs>

  <style>
    .sans {
      font-family: 'Segoe UI', Ubuntu, Arial, sans-serif;
    }

    .mono {
      font-family: ui-monospace, Consolas, monospace;
    }

    .typing {
      fill: #C9D1D9;
      font-size: 19px;
    }

    .logo-float {
      animation: float 4s ease-in-out infinite;
    }

    .cursor {
      animation: blink 1s steps(1,end) infinite;
    }

    .line {
      animation: grow 1.5s ease-out forwards;
      transform-origin: 64px 0;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-7px); }
    }

    @keyframes blink {
      50% { opacity: 0; }
    }

    @keyframes grow {
      from { transform: scaleX(0); }
      to { transform: scaleX(1); }
    }

    @media (prefers-reduced-motion: reduce) {
      * { animation: none !important; }
    }
  </style>

  <!-- FONDO -->
  <g clip-path="url(#frame)">
    <rect width="1000" height="300" fill="#0D1117"/>
    <rect width="1000" height="300" fill="url(#dots)"/>

    <circle cx="820" cy="60" r="240" fill="url(#purpleGlow)">
      <animate attributeName="cx"
               values="820;760;820"
               dur="14s"
               repeatCount="indefinite"/>
    </circle>

    <circle cx="120" cy="300" r="260" fill="url(#cyanGlow)">
      <animate attributeName="cy"
               values="300;250;300"
               dur="11s"
               repeatCount="indefinite"/>
    </circle>

    <rect x="1" y="1"
          width="998" height="298"
          rx="17"
          fill="none"
          stroke="#30363D"
          stroke-width="1.5"/>
  </g>

  <!-- TEXTO PRINCIPAL -->
  <text class="mono"
        x="64" y="72"
        font-size="18"
        fill="#8B949E">
    hola, soy
  </text>

  <text class="sans"
        x="62" y="134"
        font-size="48"
        font-weight="700"
        letter-spacing="-1"
        fill="#F0F6FC">
    Luis Diego Sipion Galvez
  </text>

  <!-- LINEA DEGRADADA -->
  <rect class="line"
        x="64" y="152"
        width="150" height="4"
        rx="2"
        fill="url(#bar)"/>

  <!-- DESCRIPCION -->
  <text class="mono"
        x="64" y="207"
        font-size="21"
        fill="#8B5CF6">❯</text>

  <text class="mono typing"
        x="100" y="207">
    Ingeniería de Software
  </text>

  <text class="mono"
        x="64" y="242"
        font-size="16"
        fill="#8B949E">
    Inteligencia Artificial · Ciberseguridad
  </text>

  <!-- LOGO A LA DERECHA -->
  <g class="logo-float">
    <image
      href="logovector.png"
      xlink:href="logovector.png"
      x="755"
      y="45"
      width="200"
      height="200"
      preserveAspectRatio="xMidYMid meet"/>
  </g>

  <!-- DETALLES DECORATIVOS -->
  <g stroke="#30363D" stroke-width="1.2" opacity=".8" fill="none">
    <path d="M730 95 L820 70 L910 120"/>
    <path d="M730 150 L820 125 L910 180"/>
    <path d="M730 205 L820 180 L910 120"/>
    <path d="M730 150 L820 235 L910 180"/>
  </g>

  <g fill="#0D1117" stroke-width="2.5">
    <circle cx="730" cy="95" r="8" stroke="#3B82F6"/>
    <circle cx="730" cy="150" r="8" stroke="#3B82F6"/>
    <circle cx="730" cy="205" r="8" stroke="#3B82F6"/>

    <circle cx="820" cy="70" r="8" stroke="#8B5CF6"/>
    <circle cx="820" cy="125" r="8" stroke="#8B5CF6"/>
    <circle cx="820" cy="180" r="8" stroke="#8B5CF6"/>
    <circle cx="820" cy="235" r="8" stroke="#8B5CF6"/>

    <circle cx="910" cy="120" r="8" stroke="#22D3EE"/>
    <circle cx="910" cy="180" r="8" stroke="#22D3EE"/>
  </g>

  <!-- PUNTOS LUMINOSOS -->
  <g>
    <circle cx="730" cy="95" r="3" fill="#3B82F6">
      <animate attributeName="opacity" values=".3;1;.3" dur="2s" repeatCount="indefinite"/>
    </circle>

    <circle cx="820" cy="125" r="3" fill="#8B5CF6">
      <animate attributeName="opacity" values=".3;1;.3" dur="2.5s" repeatCount="indefinite"/>
    </circle>

    <circle cx="910" cy="180" r="3" fill="#22D3EE">
      <animate attributeName="opacity" values=".3;1;.3" dur="3s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- UBICACION -->
  <text class="mono"
        x="64" y="276"
        font-size="14"
        fill="#6E7681">
    Lima, Perú
  </text>

  <text class="mono"
        x="935" y="276"
        font-size="12"
        text-anchor="end"
        fill="#6E7681">
    SOFTWARE DEVELOPER
  </text>

</svg>
