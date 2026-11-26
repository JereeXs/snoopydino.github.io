<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Te quiero mucho Camitooo 🦕💖</title>

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Google Fonts: Pacifico (romántica manuscrita) y Fredoka (redondeada y cálida) -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&family=Pacifico&display=swap" rel="stylesheet" />

  <style>
    /* ==========================================================
       VARIABLES, TIPOGRAFÍA Y TEMA LUMINOSO PASTEL
       ========================================================== */
    :root {
      --font-display: 'Pacifico', cursive;
      --font-body: 'Fredoka', sans-serif;
      --ink: #1e1b18;
    }

    * {
      box-sizing: border-box;
      -webkit-tap-highlight-color: transparent;
    }

    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      min-height: 100vh;
      overflow-x: hidden;
      font-family: var(--font-body);
      color: #473c46;
      user-select: none;
    }

    /* Cielo romántico pastel */
    .romantic-sky {
      background: linear-gradient(
        180deg,
        #bfe6ff 0%,
        #d9f0ff 24%,
        #fff4db 54%,
        #ffdbe7 82%,
        #ffe4d6 100%
      );
      position: relative;
      overflow-x: hidden;
    }

    .font-handwritten {
      font-family: var(--font-display);
    }

    /* ==========================================================
       PANTALLA DE BIENVENIDA (SOLUCIONA AUTOPLAY DEL NAVEGADOR)
       ========================================================== */
    @keyframes welcomeBounce {
      0%, 100% { transform: translateY(0) scale(1); }
      45% { transform: translateY(-10px) scale(1.06); }
    }

    .welcome-badge-bounce {
      animation: welcomeBounce 2.2s ease-in-out infinite;
    }

    #welcomeOverlay {
      transition: opacity 0.65s ease, transform 0.65s ease;
    }

    #welcomeOverlay.overlay-closing {
      opacity: 0;
      transform: scale(1.03);
      pointer-events: none;
    }

    /* ==========================================================
       ANIMACIONES DEL ENCABEZADO Y DESTELLOS
       ========================================================== */
    @keyframes titleEntrance {
      0% {
        opacity: 0;
        transform: translateY(-16px) scale(0.96);
      }
      100% {
        opacity: 1;
        transform: translateY(0) scale(1);
      }
    }

    @keyframes warmTitleGlow {
      0%, 100% {
        filter: drop-shadow(0 3px 10px rgba(244, 114, 182, 0.28));
      }
      50% {
        filter: drop-shadow(0 5px 18px rgba(251, 113, 133, 0.48));
      }
    }

    @keyframes gentleBob {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-5px); }
    }

    .title-card {
      animation: titleEntrance 0.85s cubic-bezier(0.22, 1, 0.36, 1) both;
    }

    .title-glow {
      animation: warmTitleGlow 4s ease-in-out infinite;
    }

    .accent-heart {
      display: inline-block;
      animation: gentleBob 2.8s ease-in-out infinite;
    }

    /* ==========================================================
       SOL CON RAYOS GIRATORIOS, NUBES Y FLORES DEL PRADO
       ========================================================== */
    @keyframes spinSlow {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    @keyframes sunPulse {
      0%, 100% { transform: scale(1); opacity: 0.78; }
      50% { transform: scale(1.08); opacity: 0.96; }
    }

    @keyframes driftSlow {
      0% { transform: translateX(-22vw); }
      100% { transform: translateX(118vw); }
    }

    @keyframes driftMedium {
      0% { transform: translateX(-26vw); }
      100% { transform: translateX(120vw); }
    }

    @keyframes twinkle {
      0%, 100% { opacity: 0.28; transform: scale(0.8) rotate(0deg); }
      50% { opacity: 0.98; transform: scale(1.22) rotate(18deg); }
    }

    @keyframes daisySway {
      0%, 100% { transform: rotate(-5deg); }
      50% { transform: rotate(5deg); }
    }

    .sun-rays { animation: spinSlow 46s linear infinite; }
    .sun-halo { animation: sunPulse 6s ease-in-out infinite; }
    .cloud-1 { animation: driftSlow 64s linear infinite; animation-delay: -10s; }
    .cloud-2 { animation: driftMedium 48s linear infinite; animation-delay: -28s; }
    .cloud-3 { animation: driftSlow 74s linear infinite; animation-delay: -46s; }
    .cloud-4 { animation: driftMedium 54s linear infinite; animation-delay: -8s; }
    .sparkle-star { animation: twinkle 3.3s ease-in-out infinite; }

    .daisy {
      transform-box: fill-box;
      transform-origin: bottom center;
      animation: daisySway 4.1s ease-in-out infinite;
    }

    /* ==========================================================
       ANIMACIONES DE SNOOPY DINO, ENAMORADA DINO Y WOODSTOCK
       ========================================================== */
    @keyframes idleBreathe {
      0%, 100% { transform: translateY(0px) scaleY(1); }
      50% { transform: translateY(-2.5px) scaleY(1.012); }
    }

    @keyframes tailWagLeft {
      0%, 100% { transform: rotate(-7deg); }
      50% { transform: rotate(11deg); }
    }

    @keyframes tailWagRight {
      0%, 100% { transform: rotate(7deg); }
      50% { transform: rotate(-11deg); }
    }

    @keyframes naturalBlink {
      0%, 91%, 100% { transform: scaleY(1); }
      94%, 97% { transform: scaleY(0.1); }
    }

    @keyframes heartPulse {
      0%, 100% { transform: scale(1) translateY(0); }
      32% { transform: scale(1.16) translateY(-5px); }
      62% { transform: scale(0.96) translateY(-1px); }
    }

    @keyframes woodstockBob {
      0%, 100% { transform: translate(0px, 0px) rotate(-2deg); }
      50% { transform: translate(8px, -11px) rotate(3deg); }
    }

    @keyframes wingFlap {
      0%, 100% { transform: rotate(0deg); }
      50% { transform: rotate(-34deg); }
    }

    @keyframes noteFloat {
      0% { opacity: 0; transform: translate(0, 8px) scale(0.72) rotate(-8deg); }
      25% { opacity: 0.95; }
      80% { opacity: 0.78; }
      100% { opacity: 0; transform: translate(12px, -22px) scale(1.08) rotate(12deg); }
    }

    @keyframes joyfulHop {
      0% { transform: translateY(0) scale(1); }
      22% { transform: translateY(-22px) scale(1.04); }
      48% { transform: translateY(0) scale(0.96); }
      72% { transform: translateY(-11px) scale(1.02); }
      100% { transform: translateY(0) scale(1); }
    }

    @keyframes bubblePop {
      0% { opacity: 0; transform: translate(-50%, 12px) scale(0.75); }
      16% { opacity: 1; transform: translate(-50%, 0px) scale(1.04); }
      26% { opacity: 1; transform: translate(-50%, 0px) scale(1); }
      82% { opacity: 1; transform: translate(-50%, -4px) scale(1); }
      100% { opacity: 0; transform: translate(-50%, -14px) scale(0.92); }
    }

    .dino-breathe-snoopy {
      transform-box: fill-box;
      transform-origin: bottom center;
      animation: idleBreathe 3.4s ease-in-out infinite;
    }

    .dino-breathe-belle {
      transform-box: fill-box;
      transform-origin: bottom center;
      animation: idleBreathe 3.4s ease-in-out infinite 0.55s;
    }

    .dino-tail-left {
      transform-box: fill-box;
      transform-origin: 92% 72%;
      animation: tailWagLeft 1.25s ease-in-out infinite;
    }

    .dino-tail-right {
      transform-box: fill-box;
      transform-origin: 8% 72%;
      animation: tailWagRight 1.3s ease-in-out infinite;
    }

    .eye-blink {
      transform-box: fill-box;
      transform-origin: center;
      animation: naturalBlink 4.7s ease-in-out infinite;
    }

    .eye-blink-delayed {
      transform-box: fill-box;
      transform-origin: center;
      animation: naturalBlink 5.2s ease-in-out infinite 1.4s;
    }

    .floating-heart-center {
      transform-box: fill-box;
      transform-origin: center;
      animation: heartPulse 1.9s ease-in-out infinite;
    }

    .woodstock-float { animation: woodstockBob 3.1s ease-in-out infinite; }

    .woodstock-wing {
      transform-box: fill-box;
      transform-origin: 20% 50%;
      animation: wingFlap 0.2s ease-in-out infinite;
    }

    .music-note-1 { animation: noteFloat 2.8s ease-out infinite; }
    .music-note-2 { animation: noteFloat 2.8s ease-out infinite 1.35s; }

    /* Estado alegre al tocar a Snoopy o a su enamorada */
    .dino-happy {
      animation: joyfulHop 0.72s cubic-bezier(0.34, 1.56, 0.64, 1) !important;
    }

    .dino-happy .dino-tail-left,
    .dino-happy .dino-tail-right {
      animation-duration: 0.25s;
    }

    .cheek-blush {
      transition: opacity 0.28s ease, transform 0.28s ease;
      transform-box: fill-box;
      transform-origin: center;
    }

    .dino-happy .cheek-blush {
      opacity: 0.98 !important;
      transform: scale(1.3);
    }

    /* Burbuja cómic flotante */
    .speech-bubble {
      position: absolute;
      pointer-events: none;
      z-index: 35;
      background: #ffffff;
      border: 2.5px solid #1e1b18;
      border-radius: 9999px;
      padding: 6px 14px;
      font-size: 0.85rem;
      font-weight: 600;
      color: #3f2d38;
      white-space: nowrap;
      box-shadow: 0 6px 18px rgba(244, 114, 182, 0.26);
      animation: bubblePop 2.45s ease-out forwards;
    }

    .speech-bubble::after {
      content: '';
      position: absolute;
      bottom: -8px;
      left: 50%;
      transform: translateX(-50%) rotate(45deg);
      width: 12px;
      height: 12px;
      background: #ffffff;
      border-right: 2.5px solid #1e1b18;
      border-bottom: 2.5px solid #1e1b18;
    }

    /* ==========================================================
       PARTÍCULAS FLOTANTES (CORAZONES, PÉTALOS Y BRILLOS)
       ========================================================== */
    @keyframes floatUpFade {
      0% {
        opacity: 0;
        transform: translate(-50%, -50%) scale(0.42) rotate(var(--rot-start));
      }
      18% {
        opacity: 1;
        transform: translate(calc(-50% + var(--drift-x) * 0.22), -76%) scale(1.12) rotate(var(--rot-mid));
      }
      100% {
        opacity: 0;
        transform: translate(calc(-50% + var(--drift-x)), -235px) scale(0.75) rotate(var(--rot-end));
      }
    }

    .floating-particle {
      position: fixed;
      pointer-events: none;
      z-index: 45;
      animation: floatUpFade var(--dur) ease-out forwards;
      will-change: transform, opacity;
    }

    @keyframes ambientDrift {
      0% {
        transform: translateY(106vh) translateX(0) rotate(0deg) scale(0.75);
        opacity: 0;
      }
      15% { opacity: 0.58; }
      85% { opacity: 0.45; }
      100% {
        transform: translateY(-14vh) translateX(44px) rotate(130deg) scale(1.08);
        opacity: 0;
      }
    }

    .ambient-particle {
      position: fixed;
      pointer-events: none;
      z-index: 4;
      animation: ambientDrift linear infinite;
    }

    /* ==========================================================
       REPRODUCTOR FLOTANTE (VINILO GIRATORIO + ECUALIZADOR)
       ========================================================== */
    @keyframes vinylSpin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    .vinyl-disc {
      animation: vinylSpin 4.5s linear infinite;
      animation-play-state: paused;
    }

    .vinyl-playing {
      animation-play-state: running;
    }

    @keyframes eqBar {
      0%, 100% { height: 4px; }
      50% { height: 17px; }
    }

    .eq-bar {
      width: 3px;
      height: 4px;
      border-radius: 9999px;
      background: linear-gradient(180deg, #fb7185, #e11d48);
      transition: height 0.2s ease;
    }

    .eq-playing .eq-bar-1 { animation: eqBar 0.60s ease-in-out infinite 0.00s; }
    .eq-playing .eq-bar-2 { animation: eqBar 0.50s ease-in-out infinite 0.14s; }
    .eq-playing .eq-bar-3 { animation: eqBar 0.68s ease-in-out infinite 0.28s; }
    .eq-playing .eq-bar-4 { animation: eqBar 0.55s ease-in-out infinite 0.10s; }

    /* Slider de volumen pastel */
    .volume-slider {
      -webkit-appearance: none;
      appearance: none;
      height: 5px;
      border-radius: 9999px;
      background: linear-gradient(90deg, #fda4af 0%, #fecdd3 100%);
      outline: none;
      cursor: pointer;
    }

    .volume-slider::-webkit-slider-thumb {
      -webkit-appearance: none;
      appearance: none;
      width: 14px;
      height: 14px;
      border-radius: 9999px;
      background: #f43f5e;
      border: 2px solid #ffffff;
      box-shadow: 0 1px 4px rgba(244, 63, 94, 0.45);
      cursor: pointer;
      transition: transform 0.15s ease;
    }

    .volume-slider::-webkit-slider-thumb:hover {
      transform: scale(1.18);
    }

    .volume-slider::-moz-range-thumb {
      width: 14px;
      height: 14px;
      border-radius: 9999px;
      background: #f43f5e;
      border: 2px solid #ffffff;
      box-shadow: 0 1px 4px rgba(244, 63, 94, 0.45);
      cursor: pointer;
    }

    /* Animación de modales y panel */
    @keyframes popIn {
      0% { opacity: 0; transform: scale(0.92) translateY(16px); }
      100% { opacity: 1; transform: scale(1) translateY(0); }
    }

    .modal-pop {
      animation: popIn 0.34s cubic-bezier(0.22, 1, 0.36, 1) forwards;
    }
  </style>
</head>

<body class="romantic-sky min-h-screen flex flex-col justify-between relative">

  <!-- ==========================================================
       PANTALLA DE BIENVENIDA PASTEL (DESBLOQUEA AUTOPLAY DE AUDIO)
       ========================================================== -->
  <div
    id="welcomeOverlay"
    class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-gradient-to-br from-rose-100/92 via-amber-50/92 to-sky-100/92 backdrop-blur-md"
    role="dialog"
    aria-modal="true"
    aria-labelledby="welcomeTitle"
  >
    <div class="modal-pop bg-white/85 backdrop-blur-xl border-2 border-white rounded-3xl px-7 py-8 sm:px-10 sm:py-10 max-w-sm w-full text-center shadow-[0_22px_55px_rgba(244,114,182,0.26)]">
      <div class="welcome-badge-bounce inline-flex items-center justify-center w-20 h-20 rounded-full bg-gradient-to-br from-rose-100 to-pink-200 border-2 border-white shadow-inner text-4xl mb-4">
        💌
      </div>

      <p class="text-xs uppercase tracking-widest font-semibold text-rose-400 mb-1">
        Un detallito especial
      </p>

      <h2 id="welcomeTitle" class="font-handwritten text-3xl sm:text-4xl text-transparent bg-clip-text bg-gradient-to-r from-rose-500 via-pink-500 to-rose-400 mb-3 leading-snug">
        Para Camitooo 
      </h2>

      <p class="text-slate-600 text-sm sm:text-base font-medium mb-6 leading-relaxed">
        Dos dinosaurios escuchando Radio de Bershy
      </p>

      <button
        id="openSurpriseBtn"
        type="button"
        class="w-full py-3.5 px-6 rounded-full bg-gradient-to-r from-rose-400 via-pink-500 to-rose-500 text-white text-base font-semibold shadow-[0_10px_28px_rgba(244,63,94,0.35)] hover:shadow-xl hover:scale-[1.03] active:scale-95 transition-all cursor-pointer"
      >
        Abrir mi sorpresa 🎵
      </button>
    </div>
  </div>

  <!-- ==========================================================
       CIELO SOÑADOR: SOL CON RAYOS GIRATORIOS, NUBES Y DESTELLOS
       ========================================================== -->
  <div class="fixed inset-0 pointer-events-none overflow-hidden z-0" aria-hidden="true">
    <!-- Sol pastel con rayos giratorios -->
    <div class="absolute -top-10 -right-10 sm:top-2 sm:right-10 w-52 h-52 sm:w-68 sm:h-68 flex items-center justify-center">
      <div class="sun-halo absolute inset-4 rounded-full bg-amber-200/55 blur-2xl"></div>
      <svg class="sun-rays w-44 h-44 sm:w-56 sm:h-56 opacity-55" viewBox="0 0 200 200" fill="none">
        <g stroke="#fde68a" stroke-width="5" stroke-linecap="round">
          <line x1="100" y1="8" x2="100" y2="30" />
          <line x1="100" y1="170" x2="100" y2="192" />
          <line x1="8" y1="100" x2="30" y2="100" />
          <line x1="170" y1="100" x2="192" y2="100" />
          <line x1="35" y1="35" x2="50" y2="50" />
          <line x1="150" y1="150" x2="165" y2="165" />
          <line x1="165" y1="35" x2="150" y2="50" />
          <line x1="50" y1="150" x2="35" y2="165" />
          <line x1="65" y1="16" x2="73" y2="35" />
          <line x1="127" y1="165" x2="135" y2="184" />
          <line x1="184" y1="65" x2="165" y2="73" />
          <line x1="35" y1="127" x2="16" y2="135" />
        </g>
      </svg>
      <div class="absolute w-20 h-20 sm:w-26 sm:h-26 rounded-full bg-gradient-to-br from-amber-100 via-yellow-100 to-rose-100 shadow-[0_0_50px_rgba(255,228,168,0.95)]"></div>
    </div>

    <!-- Nubes esponjosas deslizándose -->
    <svg class="cloud-1 absolute top-8 sm:top-10 w-36 sm:w-52 opacity-90" viewBox="0 0 210 92" fill="none">
      <path d="M36 74 H170 C185 74 196 63 196 50 C196 38 186 28 172 28 C168 14 153 5 136 5 C119 5 105 14 99 28 C93 23 85 20 76 20 C59 20 46 33 45 50 C33 51 22 59 22 67 C22 71 27 74 36 74 Z" fill="#ffffff" fill-opacity="0.93" />
    </svg>

    <svg class="cloud-2 absolute top-24 sm:top-20 w-28 sm:w-44 opacity-80" viewBox="0 0 210 92" fill="none">
      <path d="M32 75 H172 C186 75 196 65 196 53 C196 41 186 33 174 32 C167 18 150 10 134 12 C119 4 99 8 89 22 C74 18 56 26 50 42 C36 42 22 52 22 64 C22 71 26 75 32 75 Z" fill="#fff9fb" fill-opacity="0.92" />
    </svg>

    <svg class="cloud-3 absolute top-40 sm:top-34 w-40 sm:w-56 opacity-72" viewBox="0 0 210 92" fill="none">
      <path d="M38 72 H166 C180 72 190 63 190 51 C190 40 181 31 169 30 C164 16 148 8 132 10 C117 10 104 19 98 30 C86 24 68 29 61 42 C46 43 32 52 32 63 C32 69 34 72 38 72 Z" fill="#ffffff" fill-opacity="0.82" />
    </svg>

    <svg class="cloud-4 absolute top-14 sm:top-44 w-24 sm:w-36 opacity-68" viewBox="0 0 210 92" fill="none">
      <path d="M35 70 H164 C177 70 187 60 187 48 C187 37 177 28 165 28 C158 15 142 10 126 14 C114 14 103 22 97 32 C85 28 70 34 63 46 C49 46 35 55 35 64 Z" fill="#fffaf3" fill-opacity="0.88" />
    </svg>

    <!-- Destellos suaves -->
    <svg class="sparkle-star absolute top-16 left-[11%] w-5 h-5 text-amber-200" style="animation-delay: 0.2s" viewBox="0 0 24 24" fill="currentColor">
      <path d="M12 2L14.5 9.5L22 12L14.5 14.5L12 22L9.5 14.5L2 12L9.5 9.5L12 2Z" />
    </svg>
    <svg class="sparkle-star absolute top-32 right-[17%] w-4 h-4 text-rose-200" style="animation-delay: 1.2s" viewBox="0 0 24 24" fill="currentColor">
      <path d="M12 2L14.5 9.5L22 12L14.5 14.5L12 22L9.5 14.5L2 12L9.5 9.5L12 2Z" />
    </svg>
    <svg class="sparkle-star absolute top-48 left-[22%] w-3.5 h-3.5 text-white" style="animation-delay: 2.1s" viewBox="0 0 24 24" fill="currentColor">
      <path d="M12 2L14.5 9.5L22 12L14.5 14.5L12 22L9.5 14.5L2 12L9.5 9.5L12 2Z" />
    </svg>
    <svg class="sparkle-star absolute top-24 right-[31%] w-4 h-4 text-amber-100" style="animation-delay: 0.8s" viewBox="0 0 24 24" fill="currentColor">
      <path d="M12 2L14.5 9.5L22 12L14.5 14.5L12 22L9.5 14.5L2 12L9.5 9.5L12 2Z" />
    </svg>
  </div>

  <!-- Capa de partículas ambientales (corazones y pétalos flotando) -->
  <div id="ambient-container" class="fixed inset-0 pointer-events-none z-0 overflow-hidden" aria-hidden="true"></div>

  <!-- ==========================================================
       ENCABEZADO ROMÁNTICO PRINCIPAL
       ========================================================== -->
  <header class="relative z-20 w-full flex flex-col items-center pt-4 sm:pt-6 px-4">
    <div class="title-card bg-white/72 backdrop-blur-md border border-white/95 rounded-3xl px-6 py-4 sm:px-10 sm:py-5 shadow-[0_12px_36px_rgba(244,114,182,0.18)] text-center max-w-xl w-full">
      <div class="inline-flex items-center gap-2 text-[11px] sm:text-xs font-semibold tracking-widest uppercase text-rose-400 mb-1">
        <span class="accent-heart">🦕</span>
        <span>Camila de dinosaurio jkaskjas</span>
        <span class="accent-heart" style="animation-delay: 0.7s">💕</span>
      </div>

      <h1 class="title-glow font-handwritten text-3xl sm:text-5xl text-transparent bg-clip-text bg-gradient-to-r from-rose-500 via-pink-500 to-rose-400 leading-tight py-1">
        Para Camitooo
      </h1>

      <p class="text-slate-600 text-xs sm:text-sm font-medium mt-1">
        Toca a Snoopy o toca el cielo ✨
      </p>
    </div>
  </header>

  <!-- ==========================================================
       ESCENA PRINCIPAL SVG ESTILO PEANUTS:
       SNOOPY DINO VERDE + ENAMORADA DINO ROSA + WOODSTOCK DINO
       ========================================================== -->
  <main class="relative z-10 flex-1 w-full flex flex-col justify-end items-center mt-1 pb-2">
    <div id="scene-wrapper" class="relative w-full max-w-4xl mx-auto flex justify-center items-end px-2">
      <!-- Capa donde brotan las burbujas de diálogo cómic -->
      <div id="speech-layer" class="absolute inset-0 pointer-events-none z-30"></div>

      <svg
        id="scene-svg"
        viewBox="0 0 880 465"
        class="w-full h-auto max-h-[54vh] sm:max-h-[58vh] overflow-visible"
        xmlns="http://www.w3.org/2000/svg"
        role="img"
        aria-label="Ilustración estilo clásico Peanuts de Snoopy en disfraz de dinosaurio verde y su enamorada en disfraz de dinosaurio rosa pastel sobre una manta de picnic en un prado soleado, con Woodstock volando con gorrito de dinosaurio"
      >
        <defs>
          <!-- Degradados de las colinas verde pastel -->
          <linearGradient id="hillBack" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#d2f5b0" />
            <stop offset="100%" stop-color="#a2df8f" />
          </linearGradient>
          <linearGradient id="hillMid" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#b6ec9e" />
            <stop offset="100%" stop-color="#84cd82" />
          </linearGradient>
          <linearGradient id="hillFront" x1="0" y1="0" x2="0" y2="1">
            <stop offset="0%" stop-color="#9fe48f" />
            <stop offset="100%" stop-color="#6dbb72" />
          </linearGradient>

          <!-- Patrón a cuadros rosa pastel para la manta de picnic -->
          <pattern id="ginghamBlanket" width="22" height="22" patternUnits="userSpaceOnUse" patternTransform="rotate(-3)">
            <rect width="22" height="22" fill="#fff9fb" />
            <rect width="11" height="22" fill="#ffd8e6" fill-opacity="0.58" />
            <rect width="22" height="11" fill="#ffc9dc" fill-opacity="0.55" />
          </pattern>

          <!-- Degradados de los disfraces de dinosaurio -->
          <linearGradient id="greenDinoGrad" x1="0" y1="0" x2="0.8" y2="1">
            <stop offset="0%" stop-color="#79cf35" />
            <stop offset="65%" stop-color="#6bbd2c" />
            <stop offset="100%" stop-color="#59a821" />
          </linearGradient>

          <linearGradient id="pinkDinoGrad" x1="1" y1="0" x2="0.2" y2="1">
            <stop offset="0%" stop-color="#ff9ab3" />
            <stop offset="62%" stop-color="#ff85a2" />
            <stop offset="100%" stop-color="#f46e91" />
          </linearGradient>

          <linearGradient id="heartGlowGrad" x1="0" y1="0" x2="1" y2="1">
            <stop offset="0%" stop-color="#ff6b8b" />
            <stop offset="100%" stop-color="#e11d48" />
          </linearGradient>

          <filter id="softMeadowShadow" x="-10%" y="-10%" width="120%" height="125%">
            <feDropShadow dx="0" dy="5" stdDeviation="4" flood-color="#4e8554" flood-opacity="0.18" />
          </filter>

          <filter id="pawHeartGlow" x="-35%" y="-35%" width="170%" height="170%">
            <feDropShadow dx="0" dy="0" stdDeviation="5" flood-color="#fb7185" flood-opacity="0.65" />
          </filter>
        </defs>

        <!-- ================================
             COLINAS VERDES PASTEL Y PRADO
             ================================ -->
        <path d="M-80 375 Q 175 268 450 344 T 960 332 L 960 500 L -80 500 Z" fill="url(#hillBack)" opacity="0.9" />
        <path d="M-80 398 Q 275 304 575 356 T 960 364 L 960 500 L -80 500 Z" fill="url(#hillMid)" opacity="0.95" />
        <path d="M-80 416 Q 440 296 960 416 L 960 510 L -80 510 Z" fill="url(#hillFront)" />

        <!-- Manta de picnic a cuadros rosa pastel -->
        <g filter="url(#softMeadowShadow)">
          <path
            d="M198 394 Q 315 344 440 342 Q 565 344 684 394 Q 565 434 440 436 Q 315 434 198 394 Z"
            fill="url(#ginghamBlanket)"
            stroke="#f9a8c4"
            stroke-width="3"
            stroke-linejoin="round"
          />
          <path
            d="M214 394 Q 322 352 440 350 Q 558 352 668 394 Q 558 424 440 426 Q 322 424 214 394 Z"
            fill="none"
            stroke="#ffffff"
            stroke-width="2"
            stroke-dasharray="6 5"
            opacity="0.88"
          />
        </g>

        <!-- Mechoncitos de pasto dibujados a mano -->
        <g stroke="#4f9956" stroke-width="2.3" stroke-linecap="round" fill="none" opacity="0.75">
          <path d="M108 408 Q 104 397 98 394 M108 408 Q 110 395 113 391 M108 408 Q 116 399 120 397" />
          <path d="M768 406 Q 763 395 758 392 M768 406 Q 770 394 774 390 M768 406 Q 777 398 781 395" />
          <path d="M276 442 Q 272 433 268 430 M276 442 Q 278 432 281 428" />
          <path d="M604 444 Q 600 435 596 432 M604 444 Q 607 434 611 430" />
        </g>

        <!-- Margaritas mecidas por la brisa -->
        <g class="daisy" style="animation-delay: 0s" transform="translate(132, 386)">
          <path d="M0 19 Q -2 8 0 0" stroke="#4f9a56" stroke-width="2.5" fill="none" stroke-linecap="round" />
          <circle cx="0" cy="-6" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="0" cy="0" r="3.6" fill="#fbbf24" stroke="#1e1b18" stroke-width="1" />
        </g>

        <g class="daisy" style="animation-delay: 1.1s" transform="translate(182, 364) scale(0.84)">
          <path d="M0 19 Q 2 8 0 0" stroke="#4f9a56" stroke-width="2.5" fill="none" stroke-linecap="round" />
          <circle cx="0" cy="-6" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="0" cy="0" r="3.6" fill="#fbbf24" stroke="#1e1b18" stroke-width="1" />
        </g>

        <g class="daisy" style="animation-delay: 0.7s" transform="translate(698, 366) scale(0.88)">
          <path d="M0 19 Q -2 8 0 0" stroke="#4f9a56" stroke-width="2.5" fill="none" stroke-linecap="round" />
          <circle cx="0" cy="-6" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="0" cy="0" r="3.6" fill="#fbbf24" stroke="#1e1b18" stroke-width="1" />
        </g>

        <g class="daisy" style="animation-delay: 1.7s" transform="translate(748, 390)">
          <path d="M0 19 Q 2 8 0 0" stroke="#4f9a56" stroke-width="2.5" fill="none" stroke-linecap="round" />
          <circle cx="0" cy="-6" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-3.5" cy="5.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="-6" cy="-1.5" r="4.3" fill="#ffffff" stroke="#1e1b18" stroke-width="1.1" />
          <circle cx="0" cy="0" r="3.6" fill="#fbbf24" stroke="#1e1b18" stroke-width="1" />
        </g>

        <!-- Florecitas silvestres -->
        <g transform="translate(222, 430)">
          <circle cx="0" cy="0" r="5.5" fill="#fbcfe8" stroke="#f472b6" stroke-width="1.2" />
          <circle cx="0" cy="0" r="2.2" fill="#f43f5e" />
        </g>
        <g transform="translate(658, 430)">
          <circle cx="0" cy="0" r="5.5" fill="#fbcfe8" stroke="#f472b6" stroke-width="1.2" />
          <circle cx="0" cy="0" r="2.2" fill="#f43f5e" />
        </g>
        <g transform="translate(440, 444)">
          <circle cx="0" cy="0" r="4.5" fill="#fef08a" stroke="#f59e0b" stroke-width="1.1" />
          <circle cx="0" cy="0" r="1.8" fill="#f59e0b" />
        </g>

        <!-- ================================
             WOODSTOCK CON MINI GORRITO DE DINOSAURIO
             ================================ -->
        <g class="woodstock-float" transform="translate(178, 128)">
          <!-- Notitas musicales flotantes -->
          <text class="music-note-1" x="30" y="-14" font-size="18" fill="#fb7185" font-weight="bold">♪</text>
          <text class="music-note-2" x="48" y="-26" font-size="15" fill="#f43f5e" font-weight="bold">♫</text>

          <!-- Patitas finas clásicas -->
          <path
            d="M-2 23 L-4 32 M-4 32 L-9 33 M-4 32 L0 34 M4 23 L6 32 M6 32 L2 34 M6 32 L11 33"
            stroke="#1e1b18"
            stroke-width="2.2"
            stroke-linecap="round"
            fill="none"
          />

          <!-- Colita amarilla -->
          <path d="M-11 16 L-21 12 L-14 20 Z" fill="#fde047" stroke="#1e1b18" stroke-width="2.3" stroke-linejoin="round" />

          <!-- Cuerpo redondeado amarillo -->
          <path
            d="M-10 8 C-14 16 -8 25 2 24 C10 23 14 15 10 7 C6 2 -6 2 -10 8 Z"
            fill="#fde047"
            stroke="#1e1b18"
            stroke-width="2.5"
            stroke-linejoin="round"
          />

          <!-- Alita aleteando -->
          <path
            class="woodstock-wing"
            d="M-5 11 C-16 6 -21 12 -14 17 C-9 20 -3 16 -5 11 Z"
            fill="#facc15"
            stroke="#1e1b18"
            stroke-width="2.2"
            stroke-linejoin="round"
          />

          <!-- Cabeza clásica de Woodstock -->
          <path
            d="M-9 2 C-12 -8 -3 -15 7 -13 C16 -11 26 -6 25 1 C24 7 14 8 6 7 C0 7 -7 6 -9 2 Z"
            fill="#fde047"
            stroke="#1e1b18"
            stroke-width="2.5"
            stroke-linejoin="round"
          />

          <!-- Mini gorrito verde de dinosaurio con 3 puítas amarillas -->
          <g transform="translate(0, -1)">
            <path d="M-11 -9 C-16 -13 -14 -20 -8 -18 Z" fill="#ffe033" stroke="#1e1b18" stroke-width="2" stroke-linejoin="round" />
            <path d="M-5 -15 C-7 -22 0 -25 3 -18 Z" fill="#ffe033" stroke="#1e1b18" stroke-width="2" stroke-linejoin="round" />
            <path d="M3 -16 C6 -22 13 -20 11 -14 Z" fill="#ffe033" stroke="#1e1b18" stroke-width="2" stroke-linejoin="round" />
            <path
              d="M-11 -3 C-12 -13 -2 -19 10 -15 C14 -13 15 -10 13 -9 C5 -11 -4 -8 -11 -3 Z"
              fill="#6bbd2c"
              stroke="#1e1b18"
              stroke-width="2.3"
              stroke-linejoin="round"
            />
          </g>

          <!-- Ojo tierno y sonrisita -->
          <circle cx="5" cy="-4" r="1.9" fill="#1e1b18" />
          <path d="M12 2 Q 17 4 22 1" stroke="#1e1b18" stroke-width="1.8" stroke-linecap="round" fill="none" />
        </g>

        <!-- Sombras sobre la manta de picnic -->
        <ellipse cx="332" cy="390" rx="68" ry="12" fill="#e89cb6" opacity="0.34" />
        <ellipse cx="548" cy="390" rx="68" ry="12" fill="#e89cb6" opacity="0.34" />

        <!-- Corazón latiendo entre sus caritas -->
        <g class="floating-heart-center" transform="translate(440, 152)">
          <path
            d="M0 11 C0 -7 -26 -13 -26 6 C-26 24 0 40 0 40 C0 40 26 24 26 6 C26 -13 0 -7 0 11 Z"
            fill="url(#heartGlowGrad)"
            stroke="#ffffff"
            stroke-width="2.8"
            stroke-linejoin="round"
          />
          <ellipse cx="-11" cy="5" rx="3.8" ry="6" transform="rotate(-24 -11 5)" fill="#ffffff" opacity="0.58" />
        </g>

        <path d="M402 126 C402 121 395 120 395 125 C395 130 402 135 402 135 C402 135 409 130 409 125 C409 120 402 121 402 126 Z" fill="#fda4af" opacity="0.92" />
        <path d="M478 130 C478 126 472 125 472 129 C472 133 478 137 478 137 C478 137 484 133 484 129 C484 125 478 126 478 130 Z" fill="#fb7185" opacity="0.88" />

        <!-- ================================================================
             PERSONAJE IZQUIERDO: SNOOPY EN DISFRAZ DE DINOSAURIO VERDE
             ================================================================ -->
        <g id="snoopy-dino" class="cursor-pointer" transform="translate(212, 156)">
          <g class="dino-breathe-snoopy">
            <!-- 1. Colita verde con placas amarillas -->
            <g class="dino-tail-left">
              <path d="M58 175 C54 162 67 156 76 167 Z" fill="#ffe033" stroke="#1e1b18" stroke-width="3.2" stroke-linejoin="round" />
              <path d="M38 177 C36 167 48 164 55 174 Z" fill="#ffe033" stroke="#1e1b18" stroke-width="3.2" stroke-linejoin="round" />
              <path d="M21 177 C21 170 30 169 35 176 Z" fill="#ffe033" stroke="#1e1b18" stroke-width="3.1" stroke-linejoin="round" />
              <path
                d="M84 176 C54 178 30 178 12 169 C6 166 5 173 10 180 C24 198 52 208 86 205 Z"
                fill="url(#greenDinoGrad)"
                stroke="#1e1b18"
                stroke-width="3.6"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </g>

            <!-- 2. Placas dorsales amarillas redondeadas -->
            <g fill="#ffe033" stroke="#1e1b18" stroke-width="3.5" stroke-linejoin="round">
              <path d="M40 62 C25 46 42 22 68 35 C74 38 75 45 70 50 Z" />
              <path d="M35 96 C15 88 18 59 42 62 C47 63 49 70 46 80 Z" />
              <path d="M51 129 C28 127 28 97 50 96 C57 96 59 108 57 122 Z" />
              <path d="M64 162 C44 159 46 132 64 132 C72 132 72 148 70 158 Z" />
            </g>

            <!-- 3. Pie trasero de dinosaurio -->
            <g>
              <path
                d="M116 206 C135 204 162 209 164 220 C165 227 146 229 124 227 C109 226 104 218 110 210 Z"
                fill="#58a620"
                stroke="#1e1b18"
                stroke-width="3.5"
                stroke-linejoin="round"
              />
              <path d="M153 219 C157 219 161 221 162 224 C158 226 153 226 150 224 Z" fill="#e8ddb5" stroke="#1e1b18" stroke-width="2.1" />
            </g>

            <!-- 4. Cuerpo regordete verde + pancita crema + parche cosido -->
            <path
              d="M66 130 C54 148 56 184 74 202 C91 218 134 218 150 198 C164 180 162 146 144 134 Z"
              fill="url(#greenDinoGrad)"
              stroke="#1e1b18"
              stroke-width="3.7"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <path
              d="M142 144 C128 148 123 166 127 185 C130 198 139 205 147 201 C159 189 161 158 142 144 Z"
              fill="#f2f6a8"
              stroke="#1e1b18"
              stroke-width="3.2"
              stroke-linejoin="round"
            />
            <g>
              <path
                d="M72 174 L80 168 L85 173 L94 170 L92 179 L98 186 L89 188 L85 195 L77 189 L68 190 L73 182 Z"
                fill="#4f941f"
                stroke="#366b12"
                stroke-width="1.8"
                stroke-linejoin="round"
              />
              <path d="M77 167 L79 172 M92 168 L90 173 M97 183 L92 183 M74 191 L76 186" stroke="#2d5a0e" stroke-width="2" stroke-linecap="round" />
            </g>

            <!-- 5. Pie delantero verde con costura y uñitas -->
            <g>
              <path
                d="M100 209 C119 206 150 212 155 224 C158 232 142 235 113 234 C91 233 82 228 84 221 C86 214 92 211 100 209 Z"
                fill="url(#greenDinoGrad)"
                stroke="#1e1b18"
                stroke-width="3.6"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path d="M106 211 L104 231" stroke="#356614" stroke-width="2.5" stroke-dasharray="4 4" stroke-linecap="round" />
              <path d="M141 224 C146 223 151 226 152 230 C147 232 142 232 139 229 Z" fill="#e8ddb5" stroke="#1e1b18" stroke-width="2.1" />
              <path d="M149 222 C153 222 156 225 156 228 C153 229 150 228 148 226 Z" fill="#e8ddb5" stroke="#1e1b18" stroke-width="1.9" />
            </g>

            <!-- 6. Interior borgoña oscuro de la boca abierta del dinosaurio -->
            <path
              d="M72 78 C96 60 144 56 180 58 L178 134 C140 138 92 134 72 122 Z"
              fill="#783232"
              stroke="#1e1b18"
              stroke-width="3.2"
              stroke-linejoin="round"
            />

            <!-- 7. Cabecita blanca clásica de Snoopy asomándose -->
            <g>
              <path
                d="M66 96 C66 72 86 58 114 60 C127 61 136 67 142 74 C153 74 176 78 184 93 C191 106 182 124 162 129 C142 134 102 134 80 124 C69 119 66 109 66 96 Z"
                fill="#ffffff"
                stroke="#1e1b18"
                stroke-width="3.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <!-- Oreja negra en forma de gota -->
              <path
                d="M76 80 C67 80 61 93 62 108 C63 121 72 127 81 124 C90 120 92 106 89 93 C87 84 82 80 76 80 Z"
                fill="#1e1b18"
              />
              <path
                d="M72 88 C67 95 67 108 71 116 C75 121 81 119 83 112"
                fill="none"
                stroke="#ffffff"
                stroke-width="2"
                stroke-linecap="round"
                opacity="0.9"
              />

              <!-- Ojitos verticales ovalados clásicos -->
              <g class="eye-blink">
                <ellipse cx="122" cy="83" rx="2.7" ry="5.5" fill="#1e1b18" />
                <ellipse cx="134" cy="83" rx="2.7" ry="5.5" fill="#1e1b18" />
                <circle cx="122.8" cy="81" r="0.9" fill="#ffffff" />
                <circle cx="134.8" cy="81" r="0.9" fill="#ffffff" />
              </g>

              <!-- Naricita negra brillante -->
              <ellipse cx="158" cy="98" rx="9.8" ry="6.8" transform="rotate(6 158 98)" fill="#1e1b18" />
              <ellipse cx="155.5" cy="95.4" rx="2.7" ry="1.4" transform="rotate(-12 155.5 95.4)" fill="#ffffff" opacity="0.82" />

              <!-- Rubor rosado -->
              <ellipse class="cheek-blush" cx="117" cy="100" rx="9.5" ry="5.2" fill="#fda4af" opacity="0.62" />

              <!-- Sonrisa cálida estilo Peanuts -->
              <path d="M107 109 C114 126 144 127 162 117" fill="none" stroke="#1e1b18" stroke-width="3" stroke-linecap="round" />
              <path d="M104 107 C106 109 108 110 110 110" fill="none" stroke="#1e1b18" stroke-width="2.4" stroke-linecap="round" />
            </g>

            <!-- 8. Dientecitos blancos cuadrados -->
            <g fill="#ffffff" stroke="#1e1b18" stroke-width="2.9" stroke-linejoin="round">
              <path d="M116 62 L117 70 C117 72 128 72 130 69 L131 60 Z" />
              <path d="M159 57 L160 65 C161 67 172 67 174 64 L175 56 Z" />
              <path d="M102 133 L103 126 C104 123 116 123 117 126 L118 134 Z" />
              <path d="M152 134 L153 126 C154 123 165 124 166 127 L167 135 Z" />
            </g>

            <!-- 9. Capucha verde de T-Rex -->
            <path
              d="M66 131 C54 121 44 103 44 82 C44 58 64 41 88 29 C116 15 148 12 169 24 C185 33 191 49 187 58 C156 59 114 62 84 74 C65 81 59 99 66 116 C74 132 106 134 146 135 C164 135 178 133 188 131 C192 130 192 138 184 144 C166 151 124 150 92 144 C79 141 71 136 66 131 Z"
              fill="url(#greenDinoGrad)"
              stroke="#1e1b18"
              stroke-width="3.7"
              stroke-linecap="round"
              stroke-linejoin="round"
            />

            <!-- Ojo dormilón con línea horizontal -->
            <g>
              <circle cx="67" cy="69" r="12.5" fill="none" stroke="#1e1b18" stroke-width="3.2" />
              <path d="M53.5 69.5 L80.5 68.5" stroke="#1e1b18" stroke-width="3.2" stroke-linecap="round" />
            </g>

            <!-- Cicatriz cosida verde oscuro en el hocico -->
            <g stroke="#366b12" stroke-width="3.1" stroke-linecap="round">
              <path d="M104 24 C109 36 115 48 124 60" fill="none" />
              <path d="M100 32 L113 28" />
              <path d="M104 40 L118 36" />
              <path d="M109 49 L123 44" />
              <path d="M115 57 L128 52" />
            </g>

            <!-- Fosas nasales -->
            <ellipse cx="151" cy="36" rx="4.4" ry="2.7" transform="rotate(24 151 36)" fill="#366b12" />
            <ellipse cx="164" cy="36" rx="3.4" ry="2.3" transform="rotate(-14 164 36)" fill="#366b12" />

            <!-- 10. Bracito verde con costuras punteadas y garritas amarillas -->
            <g>
              <path d="M140 176 L147 180 L141 183 Z" fill="#f6e59c" stroke="#1e1b18" stroke-width="2.1" stroke-linejoin="round" />
              <path d="M137 182 L144 187 L137 189 Z" fill="#f6e59c" stroke="#1e1b18" stroke-width="2.1" stroke-linejoin="round" />
              <path d="M131 185 L136 192 L130 191 Z" fill="#f6e59c" stroke="#1e1b18" stroke-width="2.1" stroke-linejoin="round" />
              <path
                d="M105 148 C100 162 104 184 118 190 C128 194 142 188 143 177 C144 167 132 162 124 150"
                fill="url(#greenDinoGrad)"
                stroke="#1e1b18"
                stroke-width="3.6"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path d="M117 151 C116 164 118 175 123 185" fill="none" stroke="#356614" stroke-width="2.5" stroke-dasharray="4.5 4.5" stroke-linecap="round" />
            </g>
          </g>
        </g>

        <!-- ================================================================
             PERSONAJE DERECHO: ENAMORADA DE SNOOPY EN DISFRAZ DE DINO ROSA
             ================================================================ -->
        <g id="belle-dino" class="cursor-pointer" transform="translate(462, 158)">
          <g class="dino-breathe-belle">
            <!-- 1. Colita rosa con placas amarillo mantequilla -->
            <g class="dino-tail-right">
              <path d="M148 173 C152 160 139 154 130 165 Z" fill="#fff07c" stroke="#1e1b18" stroke-width="3.2" stroke-linejoin="round" />
              <path d="M168 175 C170 165 158 162 151 172 Z" fill="#fff07c" stroke="#1e1b18" stroke-width="3.2" stroke-linejoin="round" />
              <path d="M185 175 C185 168 176 167 171 174 Z" fill="#fff07c" stroke="#1e1b18" stroke-width="3.1" stroke-linejoin="round" />
              <path
                d="M122 174 C152 176 176 176 194 167 C200 164 201 171 196 178 C182 196 154 206 120 203 Z"
                fill="url(#pinkDinoGrad)"
                stroke="#1e1b18"
                stroke-width="3.6"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
            </g>

            <!-- 2. Placas dorsales amarillo mantequilla -->
            <g fill="#fff07c" stroke="#1e1b18" stroke-width="3.5" stroke-linejoin="round">
              <path d="M166 60 C181 44 164 20 138 33 C132 36 131 43 136 48 Z" />
              <path d="M171 94 C191 86 188 57 164 60 C159 61 157 68 160 78 Z" />
              <path d="M155 127 C178 125 178 95 156 94 C149 94 147 106 149 120 Z" />
              <path d="M142 160 C162 157 160 130 142 130 C134 130 134 146 136 156 Z" />
            </g>

            <!-- 3. Pie trasero rosa -->
            <g>
              <path
                d="M90 204 C71 202 44 207 42 218 C41 225 60 227 82 225 C97 224 102 216 96 208 Z"
                fill="#ec6a8d"
                stroke="#1e1b18"
                stroke-width="3.5"
                stroke-linejoin="round"
              />
              <path d="M53 217 C49 217 45 219 44 222 C48 224 53 224 56 222 Z" fill="#fff3d1" stroke="#1e1b18" stroke-width="2.1" />
            </g>

            <!-- 4. Cuerpo rosa + pancita crema + parche de corazón cosido -->
            <path
              d="M140 128 C152 146 150 182 132 200 C115 216 72 216 56 196 C42 178 44 144 62 132 Z"
              fill="url(#pinkDinoGrad)"
              stroke="#1e1b18"
              stroke-width="3.7"
              stroke-linecap="round"
              stroke-linejoin="round"
            />
            <path
              d="M64 142 C78 146 83 164 79 183 C76 196 67 203 59 199 C47 187 45 156 64 142 Z"
              fill="#fff5cc"
              stroke="#1e1b18"
              stroke-width="3.2"
              stroke-linejoin="round"
            />
            <g transform="translate(124, 178) rotate(12)">
              <path
                d="M0 3 C0 -4 -10 -7 -10 1 C-10 9 0 15 0 15 C0 15 10 9 10 1 C10 -7 0 -4 0 3 Z"
                fill="#e0557c"
                stroke="#b03056"
                stroke-width="2"
                stroke-linejoin="round"
              />
              <path d="M-9 -2 L-12 -4 M9 -2 L12 -4 M-6 11 L-9 13 M6 11 L9 13" stroke="#9e2449" stroke-width="1.9" stroke-linecap="round" />
            </g>

            <!-- 5. Pie delantero rosa con costura y uñitas -->
            <g>
              <path
                d="M106 207 C87 204 56 210 51 222 C48 230 64 233 93 232 C115 231 124 226 122 219 C120 212 114 209 106 207 Z"
                fill="url(#pinkDinoGrad)"
                stroke="#1e1b18"
                stroke-width="3.6"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path d="M100 209 L102 229" stroke="#b8325a" stroke-width="2.5" stroke-dasharray="4 4" stroke-linecap="round" />
              <path d="M65 222 C60 221 55 224 54 228 C59 230 64 230 67 227 Z" fill="#fff3d1" stroke="#1e1b18" stroke-width="2.1" />
              <path d="M57 220 C53 220 50 223 50 226 C53 227 56 226 58 224 Z" fill="#fff3d1" stroke="#1e1b18" stroke-width="1.9" />
            </g>

            <!-- 6. Interior berry oscuro de la boca -->
            <path
              d="M134 76 C110 58 62 54 26 56 L28 132 C66 136 114 132 134 120 Z"
              fill="#8a2b46"
              stroke="#1e1b18"
              stroke-width="3.2"
              stroke-linejoin="round"
            />

            <!-- 7. Carita Peanuts de su enamorada con pestañas, rubor y lacito rojo -->
            <g>
              <path
                d="M140 94 C140 70 120 56 92 58 C79 59 70 65 64 72 C53 72 30 76 22 91 C15 104 24 122 44 127 C64 132 104 132 126 122 C137 117 140 107 140 94 Z"
                fill="#ffffff"
                stroke="#1e1b18"
                stroke-width="3.5"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path
                d="M130 78 C139 78 145 91 144 106 C143 119 134 125 125 122 C116 118 114 104 117 91 C119 82 124 78 130 78 Z"
                fill="#1e1b18"
              />
              <path
                d="M134 86 C139 93 139 106 135 114 C131 119 125 117 123 110"
                fill="none"
                stroke="#ffffff"
                stroke-width="2"
                stroke-linecap="round"
                opacity="0.9"
              />

              <!-- Lacito rojo junto a su orejita -->
              <g transform="translate(120, 81) rotate(14)">
                <path d="M0 0 C-7 -8 -16 -6 -15 2 C-14 8 -5 7 0 2 Z" fill="#ff4d79" stroke="#1e1b18" stroke-width="2.2" stroke-linejoin="round" />
                <path d="M0 0 C7 -8 16 -6 15 2 C14 8 5 7 0 2 Z" fill="#ff4d79" stroke="#1e1b18" stroke-width="2.2" stroke-linejoin="round" />
                <circle cx="0" cy="1" r="3.6" fill="#ff85a2" stroke="#1e1b18" stroke-width="2" />
              </g>

              <!-- Ojitos dulces con pestañas -->
              <g class="eye-blink-delayed">
                <ellipse cx="84" cy="81" rx="2.6" ry="5.3" fill="#1e1b18" />
                <ellipse cx="72" cy="81" rx="2.6" ry="5.3" fill="#1e1b18" />
                <circle cx="83.2" cy="79" r="0.9" fill="#ffffff" />
                <circle cx="71.2" cy="79" r="0.9" fill="#ffffff" />
                <path d="M87 78 C91 75 94 74 96 74 M87 81 C91 80 94 80 96 81" fill="none" stroke="#1e1b18" stroke-width="2.1" stroke-linecap="round" />
                <path d="M74 77 C77 75 79 74 80 74" fill="none" stroke="#1e1b18" stroke-width="1.8" stroke-linecap="round" />
              </g>

              <!-- Naricita negra -->
              <ellipse cx="48" cy="96" rx="9.2" ry="6.4" transform="rotate(-6 48 96)" fill="#1e1b18" />
              <ellipse cx="50.5" cy="93.5" rx="2.5" ry="1.3" transform="rotate(12 50.5 93.5)" fill="#ffffff" opacity="0.82" />

              <!-- Rubor sonrosado -->
              <ellipse class="cheek-blush" cx="89" cy="99" rx="10" ry="5.5" fill="#ff8fab" opacity="0.72" />

              <!-- Sonrisita dulce -->
              <path d="M97 108 C90 123 64 124 47 115" fill="none" stroke="#1e1b18" stroke-width="2.9" stroke-linecap="round" />
              <path d="M100 106 C98 108 96 109 94 109" fill="none" stroke="#1e1b18" stroke-width="2.3" stroke-linecap="round" />
            </g>

            <!-- 8. Dientecitos blancos cuadrados -->
            <g fill="#ffffff" stroke="#1e1b18" stroke-width="2.9" stroke-linejoin="round">
              <path d="M90 60 L89 68 C89 70 78 70 76 67 L75 58 Z" />
              <path d="M47 55 L46 63 C45 65 34 65 32 62 L31 54 Z" />
              <path d="M104 131 L103 124 C102 121 90 121 89 124 L88 132 Z" />
              <path d="M54 132 L53 124 C52 121 41 122 40 125 L39 133 Z" />
            </g>

            <!-- 9. Capucha rosa pastel del dinosaurio -->
            <path
              d="M140 129 C152 119 162 101 162 80 C162 56 142 39 118 27 C90 13 58 10 37 22 C21 31 15 47 19 56 C50 57 92 60 122 72 C141 79 147 97 140 114 C132 130 100 132 60 133 C42 133 28 131 18 129 C14 128 14 136 22 142 C40 149 82 148 114 142 C127 139 135 134 140 129 Z"
              fill="url(#pinkDinoGrad)"
              stroke="#1e1b18"
              stroke-width="3.7"
              stroke-linecap="round"
              stroke-linejoin="round"
            />

            <!-- Ojo dormilón del dinosaurio con pestañitas -->
            <g>
              <circle cx="139" cy="67" r="12.5" fill="none" stroke="#1e1b18" stroke-width="3.2" />
              <path d="M125.5 66.5 L152.5 67.5" stroke="#1e1b18" stroke-width="3.2" stroke-linecap="round" />
              <path d="M149 58 L156 54 M152 64 L159 62" stroke="#1e1b18" stroke-width="2.5" stroke-linecap="round" />
            </g>

            <!-- Costura diagonal en el hocico -->
            <g stroke="#b8325a" stroke-width="3.1" stroke-linecap="round">
              <path d="M102 22 C97 34 91 46 82 58" fill="none" />
              <path d="M106 30 L93 26" />
              <path d="M102 38 L88 34" />
              <path d="M97 47 L83 42" />
              <path d="M91 55 L78 50" />
            </g>

            <!-- Fosas nasales -->
            <ellipse cx="55" cy="34" rx="4.4" ry="2.7" transform="rotate(-24 55 34)" fill="#b8325a" />
            <ellipse cx="42" cy="34" rx="3.4" ry="2.3" transform="rotate(14 42 34)" fill="#b8325a" />

            <!-- 10. Bracito rosa con costuras y garritas -->
            <g>
              <path d="M66 174 L59 178 L65 181 Z" fill="#fff5cc" stroke="#1e1b18" stroke-width="2.1" stroke-linejoin="round" />
              <path d="M69 180 L62 185 L69 187 Z" fill="#fff5cc" stroke="#1e1b18" stroke-width="2.1" stroke-linejoin="round" />
              <path d="M75 183 L70 190 L76 189 Z" fill="#fff5cc" stroke="#1e1b18" stroke-width="2.1" stroke-linejoin="round" />
              <path
                d="M101 146 C106 160 102 182 88 188 C78 192 64 186 63 175 C62 165 74 160 82 148"
                fill="url(#pinkDinoGrad)"
                stroke="#1e1b18"
                stroke-width="3.6"
                stroke-linecap="round"
                stroke-linejoin="round"
              />
              <path d="M89 149 C90 162 88 173 83 183" fill="none" stroke="#b8325a" stroke-width="2.5" stroke-dasharray="4.5 4.5" stroke-linecap="round" />
            </g>
          </g>
        </g>

        <!-- Corazoncito brillante entre sus patitas -->
        <g class="floating-heart-center" style="animation-delay: 0.45s" transform="translate(440, 326)" filter="url(#pawHeartGlow)">
          <path
            d="M0 5 C0 -6 -16 -9 -16 3 C-16 14 0 24 0 24 C0 24 16 14 16 3 C16 -9 0 -6 0 5 Z"
            fill="url(#heartGlowGrad)"
            stroke="#ffffff"
            stroke-width="2.2"
            stroke-linejoin="round"
          />
          <ellipse cx="-6.5" cy="2" rx="2.4" ry="3.8" transform="rotate(-22 -6.5 2)" fill="#ffffff" opacity="0.62" />
        </g>
      </svg>
    </div>

    <!-- ==========================================================
         BOTONES DE ACCIÓN PRINCIPALES
         ========================================================== -->
    <div class="relative z-20 flex flex-wrap items-center justify-center gap-3 px-4 mt-3 mb-2">
      <button
        id="open-letter-btn"
        type="button"
        class="inline-flex items-center gap-2 px-5 py-3 rounded-full bg-white/80 backdrop-blur-md border border-white text-rose-500 text-sm sm:text-base font-semibold shadow-[0_8px_24px_rgba(244,114,182,0.22)] hover:bg-white hover:scale-105 active:scale-95 transition-all cursor-pointer"
      >
        <span>💌</span>
        <span>Cartita para Camitooo</span>
      </button>

      <button
        id="confetti-hearts-btn"
        type="button"
        class="inline-flex items-center gap-2 px-5 py-3 rounded-full bg-gradient-to-r from-rose-400 to-pink-500 text-white text-sm sm:text-base font-semibold shadow-[0_8px_24px_rgba(244,63,94,0.32)] hover:shadow-lg hover:scale-105 active:scale-95 transition-all cursor-pointer"
      >
        <span>💖</span>
        <span>Lluvia de Corazones</span>
      </button>
    </div>
  </main>

  <!-- ==========================================================
       PANEL DE CONFIGURACIÓN PARA FIJAR EL MP3 PERMANENTEMENTE
       (Se elimina automáticamente en el HTML descargado para Camitooo)
       ========================================================== -->
  <div
    id="creatorPanel"
    class="hidden fixed bottom-24 right-3 left-3 sm:left-auto sm:right-5 sm:bottom-24 z-40 max-w-sm sm:w-96 mx-auto sm:mx-0"
    role="dialog"
    aria-label="Configurar MP3 fijo"
  >
    <div class="modal-pop bg-white/95 backdrop-blur-xl border-2 border-rose-100 rounded-3xl p-4 sm:p-5 shadow-[0_18px_48px_rgba(244,63,94,0.24)] text-left">
      <div class="flex items-center justify-between gap-2 mb-2.5">
        <div class="flex items-center gap-2">
          <span class="text-lg">🎵</span>
          <h3 class="font-bold text-slate-800 text-sm sm:text-base">Dejar tu MP3 fijo</h3>
        </div>
        <button
          id="closeCreatorPanelBtn"
          type="button"
          aria-label="Cerrar panel de MP3"
          class="w-7 h-7 rounded-full bg-rose-50 hover:bg-rose-100 text-rose-500 flex items-center justify-center text-xs font-bold cursor-pointer transition-colors"
        >
          ✕
        </button>
      </div>

      <!-- Indicador del estado actual del audio -->
      <div id="mp3StatusBadge" class="text-xs font-semibold px-3 py-2 rounded-2xl bg-rose-50 text-rose-600 border border-rose-100 mb-3 leading-snug">
        ✨ Buscando radio.mp3 o MP3 guardado...
      </div>

      <!-- Acciones principales -->
      <div class="flex flex-col gap-2">
        <button
          id="selectMp3Btn"
          type="button"
          class="w-full inline-flex items-center justify-center gap-2 px-4 py-2.5 rounded-2xl bg-rose-500 hover:bg-rose-600 text-white text-xs sm:text-sm font-semibold shadow-sm transition-all active:scale-95 cursor-pointer"
        >
          <span>📁</span>
          <span>Seleccionar mi MP3 (se guarda aquí)</span>
        </button>

        <button
          id="exportStandaloneBtn"
          type="button"
          class="w-full inline-flex items-center justify-center gap-2 px-4 py-2.5 rounded-2xl bg-gradient-to-r from-emerald-500 to-teal-500 hover:from-emerald-600 hover:to-teal-600 text-white text-xs sm:text-sm font-semibold shadow-sm transition-all active:scale-95 cursor-pointer"
        >
          <span>📥</span>
          <span>Descargar HTML con MP3 fijo</span>
        </button>

        <button
          id="clearSavedMp3Btn"
          type="button"
          class="hidden w-full inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-2xl bg-slate-100 hover:bg-slate-200 text-slate-600 text-xs font-semibold transition-colors cursor-pointer"
        >
          <span>🗑️</span>
          <span>Quitar MP3 guardado</span>
        </button>
      </div>

      <!-- Ayuda breve de las 3 formas permanentes -->
      <p class="text-[11px] text-slate-500 mt-3 leading-relaxed">
        <strong>Tip:</strong> Al subir tu MP3 queda guardado automáticamente en este navegador. Si quieres enviárselo a Camitooo en un solo archivo ya listo, usa <strong>Descargar HTML con MP3 fijo</strong> (o pon <code class="bg-rose-50 px-1 rounded text-rose-600">Radio.mp3</code> en la misma carpeta).
      </p>

      <input id="mp3-file-input" type="file" accept="audio/*" class="hidden" />
    </div>
  </div>

  <!-- ==========================================================
       REPRODUCTOR DE MÚSICA FLOTANTE ("Radio — HER'S")
       ========================================================== -->
  <footer class="relative z-30 w-full flex justify-center px-3 pb-4 pt-2 md:fixed md:bottom-5 md:right-5 md:w-auto md:p-0">
    <div class="bg-white/84 backdrop-blur-lg border border-white/95 rounded-3xl sm:rounded-full px-3.5 py-2.5 sm:px-4 sm:py-2.5 shadow-[0_12px_34px_rgba(244,63,94,0.2)] flex flex-wrap sm:flex-nowrap items-center justify-center gap-2.5 sm:gap-3 max-w-full">
      <!-- Disco de vinilo giratorio -->
      <div
        id="vinyl-icon"
        class="vinyl-disc w-10 h-10 rounded-full bg-gradient-to-br from-slate-800 via-slate-700 to-slate-900 border-2 border-rose-200 flex items-center justify-center shadow-sm shrink-0 relative"
        aria-hidden="true"
      >
        <div class="w-4 h-4 rounded-full bg-gradient-to-br from-rose-400 to-pink-500 flex items-center justify-center text-[9px] text-white">
          ♥
        </div>
      </div>

      <!-- Botón Play / Pause -->
      <button
        id="music-toggle-btn"
        type="button"
        aria-label="Reproducir o pausar Radio de Bershy"
        class="w-10 h-10 rounded-full bg-gradient-to-br from-rose-400 to-pink-500 text-white flex items-center justify-center shadow-md shadow-rose-300/60 hover:scale-105 active:scale-95 transition-transform shrink-0 cursor-pointer"
      >
        <svg id="icon-play" class="w-5 h-5 ml-0.5" viewBox="0 0 24 24" fill="currentColor">
          <path d="M8 5.14v14l11-7-11-7z" />
        </svg>
        <svg id="icon-pause" class="w-5 h-5 hidden" viewBox="0 0 24 24" fill="currentColor">
          <path d="M6 5h4v14H6V5zm8 0h4v14h-4V5z" />
        </svg>
      </button>

      <!-- Info de pista + ecualizador -->
      <div class="flex items-center gap-2.5 min-w-0">
        <div id="equalizer" class="flex items-end gap-0.5 h-4 shrink-0" aria-hidden="true">
          <span class="eq-bar eq-bar-1"></span>
          <span class="eq-bar eq-bar-2"></span>
          <span class="eq-bar eq-bar-3"></span>
          <span class="eq-bar eq-bar-4"></span>
        </div>

        <div class="min-w-0 max-w-[130px] sm:max-w-[155px]">
          <p id="track-title" class="text-xs sm:text-sm font-bold text-slate-800 truncate leading-tight">
            Radio - Bershy
          </p>
          <p id="track-subtitle" class="text-[11px] font-medium text-rose-400 truncate">
            Lista para sonar 💕
          </p>
        </div>
      </div>

      <!-- Control de volumen -->
      <div class="flex items-center gap-1.5 pl-2 border-l border-rose-100 shrink-0">
        <svg class="w-4 h-4 text-rose-400 shrink-0" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
          <polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5" />
          <path d="M15.54 8.46a5 5 0 0 1 0 7.07" />
        </svg>
        <input
          id="volume-slider"
          type="range"
          min="0"
          max="1"
          step="0.02"
          value="0.72"
          aria-label="Volumen de la música"
          class="volume-slider w-14 sm:w-16"
        />
      </div>

      <!-- Botón sutil para abrir panel de MP3 fijo (se remueve en el archivo exportado) -->
      <div id="creatorToggleWrapper" class="pl-2 border-l border-rose-100 shrink-0">
        <button
          id="toggleCreatorBtn"
          type="button"
          title="Fijar tu MP3 permanentemente"
          class="inline-flex items-center gap-1 px-3 py-2 rounded-full bg-rose-50 hover:bg-rose-100 text-rose-500 text-xs font-semibold transition-colors cursor-pointer"
        >
          <span>⚙️</span>
          <span>Fijar MP3</span>
        </button>
      </div>
    </div>
  </footer>

  <!-- Reproductor HTML5 principal: carga automáticamente Radio.mp3 si está en la misma carpeta -->
  <audio id="bgMusic" src="Radio.mp3" loop preload="auto"></audio>

  <!-- ==========================================================
       MODAL PASTEL: CARTITA DEDICADA PARA CAMITOOO
       ========================================================== -->
  <div
    id="letter-modal"
    class="fixed inset-0 z-50 hidden items-center justify-center p-4 bg-rose-950/20 backdrop-blur-sm"
    role="dialog"
    aria-modal="true"
    aria-labelledby="letter-title"
  >
    <div class="modal-pop relative bg-gradient-to-b from-white/95 to-rose-50/95 backdrop-blur-xl border-2 border-white rounded-3xl max-w-md w-full p-6 sm:p-8 shadow-[0_22px_60px_rgba(244,63,94,0.24)] text-center">
      <button
        id="close-letter-btn"
        type="button"
        aria-label="Cerrar cartita"
        class="absolute top-3.5 right-3.5 w-9 h-9 rounded-full bg-rose-100/80 text-rose-500 hover:bg-rose-200/80 flex items-center justify-center font-bold transition-colors cursor-pointer"
      >
        ✕
      </button>

      <div class="text-4xl mb-2">🦕💌🦕</div>
      <h2 id="letter-title" class="font-handwritten text-3xl sm:text-4xl text-rose-500 mb-3">
        Para mi Camitooo
      </h2>

      <p class="text-slate-600 text-sm sm:text-base leading-relaxed font-medium mb-3">
        Quise hacerte este detallito con nuestros dos dinosaurios favoritos para recordarte lo muchísimo que te quiero. Cada momento contigo se siente cálido, divertido y mágico.
      </p>

      <p class="text-slate-600 text-sm sm:text-base leading-relaxed font-medium mb-4">
        Así como estos dos dinos chiquitos con sus disfraces a juego, me encanta caminar a tu lado, reírme contigo y cuidarte siempre. ¡Mi corazoncito hace <em>rawr</em> cada vez que te veo! xdddd. En persona me vuelvo timido xd💚🩷
      </p>

      <p class="text-rose-500 font-bold text-base mb-5">
        Te quiero muchísimo, hoy y siempre, Camitooo ✨
      </p>

      <button
        id="send-hug-btn"
        type="button"
        class="w-full py-3 px-5 rounded-2xl bg-gradient-to-r from-rose-400 to-pink-500 text-white font-semibold shadow-md shadow-rose-300/50 hover:shadow-lg hover:scale-[1.02] active:scale-95 transition-all cursor-pointer"
      >
        Mandar un abrazo de dinosaurio 🤗🦕💖
      </button>
    </div>
  </div>

  <!-- Notificación Toast limpia (sin alert()) -->
  <div
    id="toast-msg"
    class="fixed top-5 left-1/2 -translate-x-1/2 z-50 pointer-events-none opacity-0 -translate-y-2 transition-all duration-300 bg-white/95 text-rose-600 border border-rose-200 px-5 py-2.5 rounded-full shadow-lg text-xs sm:text-sm font-semibold text-center max-w-[90vw]"
  >
    ¡Abrazo enviado! 💕
  </div>

  <!-- ==========================================================
       LÓGICA JAVASCRIPT:
       - PANTALLA DE BIENVENIDA + AUTOPLAY SEGURO
       - INTERACTIVIDAD DE DINOS, BURBUJAS Y PARTÍCULAS
       - SISTEMA MP3 PERMANENTE (Radio.mp3 + IndexedDB + Export HTML Standalone)
       - RESPALDO AUTOMÁTICO INDIE-POP CON WEB AUDIO API
       ========================================================== -->
  <script>
    (() => {
      // =====================================================
      // 1. REFERENCIAS DEL DOM
      // =====================================================
      const welcomeOverlay = document.getElementById('welcomeOverlay');
      const openSurpriseBtn = document.getElementById('openSurpriseBtn');

      const snoopyDino = document.getElementById('snoopy-dino');
      const belleDino = document.getElementById('belle-dino');
      const sceneWrapper = document.getElementById('scene-wrapper');
      const speechLayer = document.getElementById('speech-layer');
      const ambientContainer = document.getElementById('ambient-container');

      const openLetterBtn = document.getElementById('open-letter-btn');
      const closeLetterBtn = document.getElementById('close-letter-btn');
      const letterModal = document.getElementById('letter-modal');
      const sendHugBtn = document.getElementById('send-hug-btn');
      const confettiBtn = document.getElementById('confetti-hearts-btn');
      const toastMsg = document.getElementById('toast-msg');

      // Reproductor y panel de MP3 fijo
      const bgMusic = document.getElementById('bgMusic');
      const vinylIcon = document.getElementById('vinyl-icon');
      const musicToggleBtn = document.getElementById('music-toggle-btn');
      const iconPlay = document.getElementById('icon-play');
      const iconPause = document.getElementById('icon-pause');
      const equalizer = document.getElementById('equalizer');
      const trackTitle = document.getElementById('track-title');
      const trackSubtitle = document.getElementById('track-subtitle');
      const volumeSlider = document.getElementById('volume-slider');

      const creatorPanel = document.getElementById('creatorPanel');
      const creatorToggleWrapper = document.getElementById('creatorToggleWrapper');
      const toggleCreatorBtn = document.getElementById('toggleCreatorBtn');
      const closeCreatorPanelBtn = document.getElementById('closeCreatorPanelBtn');
      const mp3StatusBadge = document.getElementById('mp3StatusBadge');
      const selectMp3Btn = document.getElementById('selectMp3Btn');
      const exportStandaloneBtn = document.getElementById('exportStandaloneBtn');
      const clearSavedMp3Btn = document.getElementById('clearSavedMp3Btn');
      const mp3FileInput = document.getElementById('mp3-file-input');

      // =====================================================
      // 2. SISTEMA TOAST (MENSAJES SUAVES SIN ALERT)
      // =====================================================
      let toastTimer = null;
      function showToast(text, duration = 3200) {
        if (!toastMsg) return;
        toastMsg.textContent = text;
        toastMsg.classList.remove('opacity-0', '-translate-y-2');
        toastMsg.classList.add('opacity-100', 'translate-y-0');
        clearTimeout(toastTimer);
        toastTimer = setTimeout(() => {
          toastMsg.classList.remove('opacity-100', 'translate-y-0');
          toastMsg.classList.add('opacity-0', '-translate-y-2');
        }, duration);
      }

      // =====================================================
      // 3. PARTÍCULAS ROMÁNTICAS (CORAZONES, PÉTALOS, BRILLOS)
      // =====================================================
      const particleSymbols = ['❤️', '💖', '💕', '💗', '✨', '🌸', '💛'];

      function spawnParticle(x, y, count = 1) {
        for (let i = 0; i < count; i++) {
          const el = document.createElement('span');
          el.className = 'floating-particle';
          el.textContent = particleSymbols[Math.floor(Math.random() * particleSymbols.length)];

          const spreadX = count > 1 ? 88 : 18;
          const spreadY = count > 1 ? 56 : 14;
          const offsetX = (Math.random() - 0.5) * spreadX;
          const offsetY = (Math.random() - 0.5) * spreadY;
          const size = 16 + Math.random() * 14;
          const driftX = (Math.random() - 0.5) * 96;
          const dur = 1.45 + Math.random() * 1.15;

          el.style.left = `${x + offsetX}px`;
          el.style.top = `${y + offsetY}px`;
          el.style.fontSize = `${size}px`;
          el.style.setProperty('--drift-x', `${driftX}px`);
          el.style.setProperty('--dur', `${dur}s`);
          el.style.setProperty('--rot-start', `${(Math.random() - 0.5) * 32}deg`);
          el.style.setProperty('--rot-mid', `${(Math.random() - 0.5) * 22}deg`);
          el.style.setProperty('--rot-end', `${(Math.random() - 0.5) * 48}deg`);

          document.body.appendChild(el);
          setTimeout(() => el.remove(), dur * 1000 + 80);
        }
      }

      function launchHeartShower(total = 32) {
        const vw = window.innerWidth;
        const vh = window.innerHeight;
        for (let i = 0; i < total; i++) {
          setTimeout(() => {
            const x = Math.random() * vw;
            const y = vh * (0.4 + Math.random() * 0.5);
            spawnParticle(x, y, 1);
          }, i * 48);
        }
      }

      function initAmbientParticles() {
        ambientContainer.innerHTML = '';
        const items = ['💗', '💕', '🌸', '🤍', '✨'];
        for (let i = 0; i < 15; i++) {
          const span = document.createElement('span');
          span.className = 'ambient-particle';
          span.textContent = items[i % items.length];
          span.style.left = `${4 + Math.random() * 92}%`;
          span.style.fontSize = `${12 + Math.random() * 11}px`;
          span.style.animationDuration = `${15 + Math.random() * 15}s`;
          span.style.animationDelay = `${-Math.random() * 22}s`;
          ambientContainer.appendChild(span);
        }
      }

      // =====================================================
      // 4. INTERACCIÓN CON SNOOPY DINO Y SU ENAMORADA DINO
      // =====================================================
      const snoopyPhrases = [
        '¡Rawr! Te amo 💕',
        'Te quiero mucho Camitooo ✨',
        'Eres mi persona favorita 🦖💖',
        '¡Mi dino favorita! 💚🩷'
      ];

      const bellePhrases = [
        '¡Mi dino favorito! 💚🩷',
        '¡Rawr! Te amo 💕',
        'Eres mi persona favorita 🦖💖',
        'Te quiero mucho Camitooo ✨'
      ];

      let snoopyPhraseIdx = 0;
      let bellePhraseIdx = 0;
      const happyTimers = new WeakMap();

      function showSpeechBubble(targetEl, phrase) {
        const wrapperRect = sceneWrapper.getBoundingClientRect();
        const charRect = targetEl.getBoundingClientRect();

        const relX = charRect.left - wrapperRect.left + charRect.width * 0.5;
        const relY = Math.max(8, charRect.top - wrapperRect.top - 12);

        const bubble = document.createElement('div');
        bubble.className = 'speech-bubble';
        bubble.textContent = phrase;
        bubble.style.left = `${relX}px`;
        bubble.style.top = `${relY}px`;

        speechLayer.appendChild(bubble);
        setTimeout(() => bubble.remove(), 2500);
      }

      function triggerDinoJoy(charEl, phrase) {
        const partner = charEl === snoopyDino ? belleDino : snoopyDino;
        [charEl, partner].forEach((el) => {
          el.classList.remove('dino-happy');
          void el.offsetWidth;
          el.classList.add('dino-happy');

          clearTimeout(happyTimers.get(el));
          happyTimers.set(
            el,
            setTimeout(() => el.classList.remove('dino-happy'), 1250)
          );
        });

        const rect = charEl.getBoundingClientRect();
        spawnParticle(rect.left + rect.width * 0.5, rect.top + rect.height * 0.35, 11);
        showSpeechBubble(charEl, phrase);
        playCuteChime();
      }

      snoopyDino.addEventListener('click', (e) => {
        e.stopPropagation();
        const phrase = snoopyPhrases[snoopyPhraseIdx % snoopyPhrases.length];
        snoopyPhraseIdx++;
        triggerDinoJoy(snoopyDino, phrase);
      });

      belleDino.addEventListener('click', (e) => {
        e.stopPropagation();
        const phrase = bellePhrases[bellePhraseIdx % bellePhrases.length];
        bellePhraseIdx++;
        triggerDinoJoy(belleDino, phrase);
      });

      // Clic en cualquier lugar del cielo o fondo genera corazones y brillos
      document.addEventListener('click', (e) => {
        if (
          e.target.closest('button') ||
          e.target.closest('input') ||
          e.target.closest('#letter-modal') ||
          e.target.closest('#creatorPanel') ||
          e.target.closest('#welcomeOverlay') ||
          e.target.closest('footer')
        ) {
          return;
        }
        spawnParticle(e.clientX, e.clientY, 2);
      });

      confettiBtn.addEventListener('click', () => {
        launchHeartShower(34);
        playCuteChime();
      });

      // =====================================================
      // 5. MODAL DE LA CARTITA PARA CAMITOOO
      // =====================================================
      function openLetter() {
        letterModal.classList.remove('hidden');
        letterModal.classList.add('flex');
      }

      function closeLetter() {
        letterModal.classList.add('hidden');
        letterModal.classList.remove('flex');
      }

      openLetterBtn.addEventListener('click', openLetter);
      closeLetterBtn.addEventListener('click', closeLetter);
      letterModal.addEventListener('click', (e) => {
        if (e.target === letterModal) closeLetter();
      });
      document.addEventListener('keydown', (e) => {
        if (e.key === 'Escape') {
          if (!letterModal.classList.contains('hidden')) closeLetter();
          if (creatorPanel && !creatorPanel.classList.contains('hidden')) {
            creatorPanel.classList.add('hidden');
          }
        }
      });

      sendHugBtn.addEventListener('click', () => {
        closeLetter();
        launchHeartShower(38);
        playCuteChime();
        showToast('¡Un abrazo gigante de dinosaurio para ti, Camitooo! 🦕🤗💖');
      });

      // =====================================================
      // 6. PERSISTENCIA EN INDEXEDDB (SnoopyCamitoooAudioDB)
      // =====================================================
      const DB_NAME = 'SnoopyCamitoooAudioDB';
      const DB_VERSION = 1;
      const STORE_NAME = 'audioFiles';
      const AUDIO_KEY = 'Radio_mp3';

      function openAudioDB() {
        return new Promise((resolve, reject) => {
          if (!window.indexedDB) {
            reject(new Error('IndexedDB no disponible'));
            return;
          }
          const req = indexedDB.open(DB_NAME, DB_VERSION);
          req.onupgradeneeded = (e) => {
            const db = e.target.result;
            if (!db.objectStoreNames.contains(STORE_NAME)) {
              db.createObjectStore(STORE_NAME);
            }
          };
          req.onsuccess = () => resolve(req.result);
          req.onerror = () => reject(req.error);
        });
      }

      async function saveMp3ToDB(blob, fileName) {
        const db = await openAudioDB();
        return new Promise((resolve, reject) => {
          const tx = db.transaction(STORE_NAME, 'readwrite');
          tx.objectStore(STORE_NAME).put({ blob, fileName, savedAt: Date.now() }, AUDIO_KEY);
          tx.oncomplete = () => {
            db.close();
            resolve();
          };
          tx.onerror = () => {
            db.close();
            reject(tx.error);
          };
        });
      }

      async function loadMp3FromDB() {
        const db = await openAudioDB();
        return new Promise((resolve, reject) => {
          const tx = db.transaction(STORE_NAME, 'readonly');
          const req = tx.objectStore(STORE_NAME).get(AUDIO_KEY);
          req.onsuccess = () => {
            db.close();
            resolve(req.result || null);
          };
          req.onerror = () => {
            db.close();
            reject(req.error);
          };
        });
      }

      async function deleteMp3FromDB() {
        const db = await openAudioDB();
        return new Promise((resolve, reject) => {
          const tx = db.transaction(STORE_NAME, 'readwrite');
          tx.objectStore(STORE_NAME).delete(AUDIO_KEY);
          tx.oncomplete = () => {
            db.close();
            resolve();
          };
          tx.onerror = () => {
            db.close();
            reject(tx.error);
          };
        });
      }

      // =====================================================
      // 7. MOTOR DE AUDIO: MP3 FIJO (3 MODOS) + SYNTH INDIE-POP
      // =====================================================
      const isBakedMode = document.body.getAttribute('data-baked') === 'true';

      let audioCtx = null;
      let masterGain = null;
      let isPlaying = false;
      let synthInterval = null;
      let stepIndex = 0;

      // Modos posibles: 'baked' | 'indexeddb' | 'localfile' | 'synth'
      let audioMode = isBakedMode ? 'baked' : 'localfile';
      let currentAudioBlob = null;
      let currentObjectUrl = null;
      let localFileFailed = false;

      bgMusic.volume = parseFloat(volumeSlider.value);

      function ensureAudioContext() {
        if (!audioCtx) {
          const AudioContextClass = window.AudioContext || window.webkitAudioContext;
          audioCtx = new AudioContextClass();
          masterGain = audioCtx.createGain();
          masterGain.gain.setValueAtTime(parseFloat(volumeSlider.value), audioCtx.currentTime);
          masterGain.connect(audioCtx.destination);
        }
        if (audioCtx.state === 'suspended') {
          audioCtx.resume();
        }
      }

      volumeSlider.addEventListener('input', () => {
        const vol = parseFloat(volumeSlider.value);
        bgMusic.volume = vol;
        if (masterGain && audioCtx) {
          masterGain.gain.setTargetAtTime(vol, audioCtx.currentTime, 0.03);
        }
      });

      // Campanita dulce al tocar a los dinosaurios
      function playCuteChime() {
        try {
          ensureAudioContext();
          const now = audioCtx.currentTime;
          [659.25, 880.0].forEach((freq, idx) => {
            const osc = audioCtx.createOscillator();
            const gain = audioCtx.createGain();
            osc.type = 'sine';
            osc.frequency.setValueAtTime(freq, now + idx * 0.075);

            gain.gain.setValueAtTime(0.001, now + idx * 0.075);
            gain.gain.exponentialRampToValueAtTime(0.085, now + idx * 0.075 + 0.02);
            gain.gain.exponentialRampToValueAtTime(0.001, now + idx * 0.075 + 0.34);

            osc.connect(gain);
            gain.connect(masterGain);
            osc.start(now + idx * 0.075);
            osc.stop(now + idx * 0.075 + 0.36);
          });
        } catch (err) {
          // Ignorar si el navegador aún no habilita AudioContext
        }
      }

      // Melodía indie-pop / dream-pop de respaldo inspirada en "Radio — Her's"
      const chordProgression = [
        { bass: 174.61, bassFifth: 261.63, bassWalk: 196.0,  notes: [349.23, 440.0, 523.25, 659.25] }, // Fmaj7
        { bass: 164.81, bassFifth: 246.94, bassWalk: 174.61, notes: [329.63, 392.0, 493.88, 587.33] }, // Em7
        { bass: 146.83, bassFifth: 220.0,  bassWalk: 164.81, notes: [293.66, 349.23, 440.0, 523.25] }, // Dm7
        { bass: 130.81, bassFifth: 196.0,  bassWalk: 146.83, notes: [261.63, 329.63, 392.0, 493.88] }  // Cmaj7
      ];

      const leadMelody = [
        659.25, null, 783.99, 659.25,
        587.33, null, 659.25, 493.88,
        523.25, null, 659.25, 587.33,
        493.88, 523.25, 659.25, null
      ];

      function playRhodesChorus(freqs, startTime, duration) {
        freqs.forEach((freq) => {
          [-6, 6].forEach((detuneCents) => {
            const osc = audioCtx.createOscillator();
            const filter = audioCtx.createBiquadFilter();
            const gain = audioCtx.createGain();
            osc.type = 'triangle';
            osc.frequency.setValueAtTime(freq, startTime);
            osc.detune.setValueAtTime(detuneCents, startTime);
            filter.type = 'lowpass';
            filter.frequency.setValueAtTime(1600, startTime);
            gain.gain.setValueAtTime(0.001, startTime);
            gain.gain.linearRampToValueAtTime(0.022, startTime + 0.06);
            gain.gain.exponentialRampToValueAtTime(0.001, startTime + duration);
            osc.connect(filter);
            filter.connect(gain);
            gain.connect(masterGain);
            osc.start(startTime);
            osc.stop(startTime + duration + 0.05);
          });
        });
      }

      function playIndieBass(freq, startTime, duration) {
        [-3, 3].forEach((detuneCents) => {
          const osc = audioCtx.createOscillator();
          const filter = audioCtx.createBiquadFilter();
          const gain = audioCtx.createGain();
          osc.type = 'triangle';
          osc.frequency.setValueAtTime(freq, startTime);
          osc.detune.setValueAtTime(detuneCents, startTime);
          filter.type = 'lowpass';
          filter.frequency.setValueAtTime(460, startTime);
          gain.gain.setValueAtTime(0.001, startTime);
          gain.gain.linearRampToValueAtTime(0.08, startTime + 0.02);
          gain.gain.exponentialRampToValueAtTime(0.001, startTime + duration);
          osc.connect(filter);
          filter.connect(gain);
          gain.connect(masterGain);
          osc.start(startTime);
          osc.stop(startTime + duration + 0.04);
        });
      }

      function playBellLead(freq, startTime, duration) {
        [-4, 4].forEach((detuneCents) => {
          const osc = audioCtx.createOscillator();
          const gain = audioCtx.createGain();
          osc.type = 'sine';
          osc.frequency.setValueAtTime(freq, startTime);
          osc.detune.setValueAtTime(detuneCents, startTime);
          gain.gain.setValueAtTime(0.001, startTime);
          gain.gain.linearRampToValueAtTime(0.036, startTime + 0.025);
          gain.gain.exponentialRampToValueAtTime(0.001, startTime + duration);
          osc.connect(gain);
          gain.connect(masterGain);
          osc.start(startTime);
          osc.stop(startTime + duration + 0.05);
        });
      }

      function startSynthMelody() {
        ensureAudioContext();
        stopSynthMelody();

        const stepDurationMs = 435;
        const triggerStep = () => {
          if (!audioCtx) return;
          const now = audioCtx.currentTime;
          const chordIdx = Math.floor(stepIndex / 4) % chordProgression.length;
          const chord = chordProgression[chordIdx];

          if (stepIndex % 4 === 0) {
            playRhodesChorus(chord.notes, now, 1.8);
            playIndieBass(chord.bass, now, 0.78);
          } else if (stepIndex % 4 === 2) {
            playIndieBass(chord.bassFifth, now, 0.44);
          } else if (stepIndex % 4 === 3) {
            playIndieBass(chord.bassWalk, now, 0.34);
          }

          const leadFreq = leadMelody[stepIndex % leadMelody.length];
          if (leadFreq) {
            playBellLead(leadFreq, now, 0.62);
          }

          stepIndex = (stepIndex + 1) % 16;
        };

        triggerStep();
        synthInterval = setInterval(triggerStep, stepDurationMs);
      }

      function stopSynthMelody() {
        if (synthInterval) {
          clearInterval(synthInterval);
          synthInterval = null;
        }
      }

      // Actualiza etiquetas del reproductor y del panel de configuración
      function updateStatusUI(playing = isPlaying) {
        isPlaying = playing;

        if (playing) {
          iconPlay.classList.add('hidden');
          iconPause.classList.remove('hidden');
          equalizer.classList.add('eq-playing');
          vinylIcon.classList.add('vinyl-playing');
        } else {
          iconPlay.classList.remove('hidden');
          iconPause.classList.add('hidden');
          equalizer.classList.remove('eq-playing');
          vinylIcon.classList.remove('vinyl-playing');
        }

        // Subtítulo del reproductor flotante
        if (playing) {
          if (audioMode === 'baked') {
            trackSubtitle.textContent = 'Sonando para Camitooo 💖';
          } else if (audioMode === 'indexeddb') {
            trackSubtitle.textContent = 'Sonando tu MP3 guardado 🎵';
          } else if (audioMode === 'localfile') {
            trackSubtitle.textContent = 'Sonando Radio.mp3 🎵';
          } else {
            trackSubtitle.textContent = 'Melodía indie-pop soñadora ✨';
          }
        } else {
          if (audioMode === 'baked') {
            trackSubtitle.textContent = 'Pausado 💖';
          } else if (audioMode === 'indexeddb') {
            trackSubtitle.textContent = 'MP3 guardado listo 🎵';
          } else if (audioMode === 'localfile') {
            trackSubtitle.textContent = 'Radio.mp3 listo 🎵';
          } else {
            trackSubtitle.textContent = 'Toca Play para música ✨';
          }
        }

        // Estado en #creatorPanel (si existe)
        if (mp3StatusBadge) {
          if (audioMode === 'indexeddb') {
            mp3StatusBadge.textContent = '💾 MP3 guardado en este navegador (se carga solo al recargar).';
            mp3StatusBadge.className = 'text-xs font-semibold px-3 py-2 rounded-2xl bg-emerald-50 text-emerald-700 border border-emerald-200 mb-3 leading-snug';
            if (clearSavedMp3Btn) clearSavedMp3Btn.classList.remove('hidden');
          } else if (audioMode === 'localfile') {
            mp3StatusBadge.textContent = '📂 Archivo local Radio.mp3 detectado en la carpeta.';
            mp3StatusBadge.className = 'text-xs font-semibold px-3 py-2 rounded-2xl bg-sky-50 text-sky-700 border border-sky-200 mb-3 leading-snug';
            if (clearSavedMp3Btn) clearSavedMp3Btn.classList.add('hidden');
          } else {
            mp3StatusBadge.textContent = '✨ Usando melodía de respaldo. Selecciona tu MP3 para dejarlo fijo.';
            mp3StatusBadge.className = 'text-xs font-semibold px-3 py-2 rounded-2xl bg-rose-50 text-rose-600 border border-rose-100 mb-3 leading-snug';
            if (clearSavedMp3Btn) clearSavedMp3Btn.classList.add('hidden');
          }
        }
      }

      // Inicia reproducción (intenta MP3 real y cae a melodía suave si no existe)
      async function startPlayback() {
        stopSynthMelody();

        if (audioMode === 'synth') {
          startSynthMelody();
          updateStatusUI(true);
          return;
        }

        try {
          bgMusic.volume = parseFloat(volumeSlider.value);
          await bgMusic.play();
          updateStatusUI(true);
        } catch (err) {
          // Si Radio.mp3 no está en la carpeta o falla la carga, usar melodía indie-pop sin romper nada
          if (audioMode === 'localfile') {
            localFileFailed = true;
            audioMode = 'synth';
            startSynthMelody();
            updateStatusUI(true);
          } else if (audioMode === 'baked' || audioMode === 'indexeddb') {
            // Si el navegador bloqueó momentáneamente, avisar con suavidad
            updateStatusUI(false);
            showToast('Toca el botón Play para activar la canción 🎵');
          } else {
            audioMode = 'synth';
            startSynthMelody();
            updateStatusUI(true);
          }
        }
      }

      function pausePlayback() {
        bgMusic.pause();
        stopSynthMelody();
        updateStatusUI(false);
      }

      // Detectar si Radio.mp3 de la carpeta local existe o falla al cargar
      bgMusic.addEventListener('error', () => {
        if (audioMode === 'localfile') {
          localFileFailed = true;
          audioMode = 'synth';
          updateStatusUI(isPlaying);
        }
      });

      bgMusic.addEventListener('canplay', () => {
        if (audioMode === 'localfile' && !localFileFailed) {
          updateStatusUI(isPlaying);
        }
      });

      // Inicializar sistema de audio (Baked -> IndexedDB -> Radio.mp3 -> Synth)
      async function initAudioSystem() {
        if (isBakedMode) {
          // Modo exportado limpio para Camitooo: ocultar controles del creador si existieran
          if (creatorPanel) creatorPanel.remove();
          if (creatorToggleWrapper) creatorToggleWrapper.remove();
          audioMode = 'baked';
          updateStatusUI(false);
          return;
        }

        // Intentar recuperar el MP3 guardado previamente en IndexedDB
        try {
          const saved = await loadMp3FromDB();
          if (saved && saved.blob) {
            currentAudioBlob = saved.blob;
            if (currentObjectUrl) URL.revokeObjectURL(currentObjectUrl);
            currentObjectUrl = URL.createObjectURL(saved.blob);
            bgMusic.src = currentObjectUrl;
            bgMusic.load();
            audioMode = 'indexeddb';
            updateStatusUI(false);
            return;
          }
        } catch (err) {
          // Si IndexedDB no está disponible, continuar con Radio.mp3 / synth
        }

        // Si no había MP3 en IndexedDB, mantener src="Radio.mp3"
        // Si ya falló antes de terminar init, pasar a synth
        if (localFileFailed) {
          audioMode = 'synth';
        }
        updateStatusUI(false);
      }

      // =====================================================
      // 8. EVENTOS DE BIENVENIDA Y CONTROLES DEL REPRODUCTOR
      // =====================================================
      if (openSurpriseBtn && welcomeOverlay) {
        openSurpriseBtn.addEventListener('click', async () => {
          welcomeOverlay.classList.add('overlay-closing');
          setTimeout(() => {
            welcomeOverlay.classList.add('hidden');
          }, 650);

          await startPlayback();
          launchHeartShower(22);
        });
      }

      musicToggleBtn.addEventListener('click', async () => {
        if (isPlaying) {
          pausePlayback();
        } else {
          await startPlayback();
        }
      });

      // =====================================================
      // 9. PANEL DE CONFIGURACIÓN: SUBIR, GUARDAR Y EXPORTAR HTML FIJO
      // =====================================================
      if (toggleCreatorBtn && creatorPanel) {
        toggleCreatorBtn.addEventListener('click', (e) => {
          e.stopPropagation();
          creatorPanel.classList.toggle('hidden');
        });
      }

      if (closeCreatorPanelBtn && creatorPanel) {
        closeCreatorPanelBtn.addEventListener('click', () => {
          creatorPanel.classList.add('hidden');
        });
      }

      if (selectMp3Btn && mp3FileInput) {
        selectMp3Btn.addEventListener('click', () => {
          mp3FileInput.click();
        });
      }

      if (mp3FileInput) {
        mp3FileInput.addEventListener('change', async (e) => {
          const file = e.target.files && e.target.files[0];
          if (!file) return;

          try {
            currentAudioBlob = file;
            if (currentObjectUrl) URL.revokeObjectURL(currentObjectUrl);
            currentObjectUrl = URL.createObjectURL(file);

            bgMusic.src = currentObjectUrl;
            bgMusic.load();
            audioMode = 'indexeddb';

            // Guardar permanentemente en IndexedDB del navegador
            try {
              await saveMp3ToDB(file, file.name);
              showToast('¡MP3 guardado en tu navegador! Ya no tendrás que subirlo de nuevo 💖', 3600);
            } catch (dbErr) {
              showToast('MP3 cargado. Usa "Descargar HTML con MP3 fijo" para guardarlo para siempre 📥', 3800);
            }

            await startPlayback();
          } catch (err) {
            showToast('No se pudo cargar ese archivo de audio.');
          } finally {
            mp3FileInput.value = '';
          }
        });
      }

      // Quitar MP3 guardado de IndexedDB
      if (clearSavedMp3Btn) {
        clearSavedMp3Btn.addEventListener('click', async () => {
          try {
            await deleteMp3FromDB();
          } catch (err) {
            // Ignorar error de borrado
          }

          if (currentObjectUrl) {
            URL.revokeObjectURL(currentObjectUrl);
            currentObjectUrl = null;
          }
          currentAudioBlob = null;
          pausePlayback();

          localFileFailed = false;
          audioMode = 'localfile';
          bgMusic.setAttribute('src', 'Radio.mp3');
          bgMusic.load();

          // Verificar rápido si Radio.mp3 falla para pasar a respaldo suave
          setTimeout(() => {
            if (bgMusic.error || bgMusic.networkState === 3) {
              localFileFailed = true;
              audioMode = 'synth';
            }
            updateStatusUI(false);
          }, 300);

          updateStatusUI(false);
          showToast('Se quitó el MP3 guardado del navegador 🗑️');
        });
      }

      // Exportar un solo archivo HTML autónomo con el MP3 incrustado en Base64
      if (exportStandaloneBtn) {
        exportStandaloneBtn.addEventListener('click', async () => {
          let blobToEmbed = currentAudioBlob;

          // Si no lo subió manualmente pero tiene Radio.mp3 en servidor local, intentar leerlo
          if (!blobToEmbed && audioMode === 'localfile' && !localFileFailed) {
            try {
              const resp = await fetch('Radio.mp3');
              if (resp.ok) {
                blobToEmbed = await resp.blob();
              }
            } catch (fetchErr) {
              // No se pudo leer por file://
            }
          }

          if (!blobToEmbed) {
            showToast('Primero selecciona tu archivo MP3 arriba 📁', 3200);
            return;
          }

          const originalBtnHtml = exportStandaloneBtn.innerHTML;
          exportStandaloneBtn.disabled = true;
          exportStandaloneBtn.innerHTML = '<span>⏳</span><span>Empaquetando MP3...</span>';

          try {
            const base64DataUrl = await new Promise((resolve, reject) => {
              const reader = new FileReader();
              reader.onload = () => resolve(reader.result);
              reader.onerror = () => reject(reader.error);
              reader.readAsDataURL(blobToEmbed);
            });

            // Clonar todo el documento HTML actual
            const docClone = document.documentElement.cloneNode(true);
            const clonedBody = docClone.querySelector('body');
            const clonedAudio = docClone.querySelector('#bgMusic');

            // 1. Incrustar el MP3 en Base64 y marcar data-baked="true"
            if (clonedAudio) {
              clonedAudio.setAttribute('src', base64DataUrl);
            }
            if (clonedBody) {
              clonedBody.setAttribute('data-baked', 'true');
            }

            // 2. Remover el panel del creador y el botón "Fijar MP3" para que Camitooo reciba una sorpresa limpia
            const clonedCreatorPanel = docClone.querySelector('#creatorPanel');
            if (clonedCreatorPanel) clonedCreatorPanel.remove();

            const clonedToggleWrapper = docClone.querySelector('#creatorToggleWrapper');
            if (clonedToggleWrapper) clonedToggleWrapper.remove();

            // 3. Restablecer la pantalla de bienvenida visible para cuando Camitooo abra el archivo
            const clonedWelcome = docClone.querySelector('#welcomeOverlay');
            if (clonedWelcome) {
              clonedWelcome.classList.remove('hidden', 'overlay-closing');
              clonedWelcome.removeAttribute('style');
            }

            // 4. Restablecer modales, toast y limpiar partículas/burbujas transitorias
            const clonedModal = docClone.querySelector('#letter-modal');
            if (clonedModal) {
              clonedModal.classList.add('hidden');
              clonedModal.classList.remove('flex');
            }

            const clonedAmbient = docClone.querySelector('#ambient-container');
            if (clonedAmbient) clonedAmbient.innerHTML = '';

            const clonedSpeech = docClone.querySelector('#speech-layer');
            if (clonedSpeech) clonedSpeech.innerHTML = '';

            docClone.querySelectorAll('.floating-particle').forEach((node) => node.remove());

            const clonedToast = docClone.querySelector('#toast-msg');
            if (clonedToast) {
              clonedToast.classList.remove('opacity-100', 'translate-y-0');
              clonedToast.classList.add('opacity-0', '-translate-y-2');
            }

            // 5. Restablecer estado visual inicial del reproductor
            const cPlay = docClone.querySelector('#icon-play');
            const cPause = docClone.querySelector('#icon-pause');
            const cEq = docClone.querySelector('#equalizer');
            const cVinyl = docClone.querySelector('#vinyl-icon');
            const cTitle = docClone.querySelector('#track-title');
            const cSubtitle = docClone.querySelector('#track-subtitle');

            if (cPlay) cPlay.classList.remove('hidden');
            if (cPause) cPause.classList.add('hidden');
            if (cEq) cEq.classList.remove('eq-playing');
            if (cVinyl) cVinyl.classList.remove('vinyl-playing');
            if (cTitle) cTitle.textContent = "Radio — Bershy";
            if (cSubtitle) cSubtitle.textContent = 'Lista para sonar 💖';

            // 6. Generar y descargar el archivo standalone Te_quiero_mucho_Camitooo.html
            const finalHtml = '<!DOCTYPE html>\n' + docClone.outerHTML;
            const htmlBlob = new Blob([finalHtml], { type: 'text/html;charset=utf-8' });
            const downloadUrl = URL.createObjectURL(htmlBlob);

            const link = document.createElement('a');
            link.href = downloadUrl;
            link.download = 'Te_quiero_mucho_Camitooo.html';
            document.body.appendChild(link);
            link.click();
            document.body.removeChild(link);

            setTimeout(() => URL.revokeObjectURL(downloadUrl), 4000);
            showToast('¡Listo! Se descargó Te_quiero_mucho_Camitooo.html con tu MP3 fijo 🎉💖', 4200);
          } catch (err) {
            showToast('Ocurrió un error al empaquetar el MP3. Intenta de nuevo.');
          } finally {
            exportStandaloneBtn.disabled = false;
            exportStandaloneBtn.innerHTML = originalBtnHtml;
          }
        });
      }

      // =====================================================
      // 10. ARRANQUE INICIAL
      // =====================================================
      initAmbientParticles();
      initAudioSystem();
    })();
  </script>
</body>
</html>
