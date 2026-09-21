<html lang="pt-BR"><head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="theme-color" content="#0A0A0A">
<title>PREDPACK — Biblioteca de cenas prontas para editar | PREDEST1NADOS</title>
<meta name="description" content="PREDPACK: biblioteca de cenas de filmes e séries já selecionadas e cortadas para editores. Atualizado 3x por semana. Acesso imediato.">

<!-- Open Graph -->
<meta property="og:title" content="PREDPACK — Cenas prontas para editar">
<meta property="og:description" content="Biblioteca atualizada 3x por semana com cenas selecionadas e cortadas para editores.">
<meta property="og:type" content="website">

<!-- Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&amp;family=Inter:wght@400;500;600;700;800&amp;display=swap" rel="stylesheet">

<!-- Tailwind CDN -->
<script src="https://cdn.tailwindcss.com"></script>
<script>
tailwind.config = {
  theme: {
    extend: {
      colors: {
        brand: {
          red: '#E11D2E',
          darkred: '#B01523',
          black: '#0A0A0A',
          graphite: '#141414',
          gray: '#1E1E1E',
        },
      },
      fontFamily: {
        display: ['"Bebas Neue"', 'sans-serif'],
        sans: ['Inter', 'system-ui', 'sans-serif'],
      },
      keyframes: {
        fadeUp: {
          '0%': { opacity: '0', transform: 'translateY(20px)' },
          '100%': { opacity: '1', transform: 'translateY(0)' },
        },
      },
      animation: {
        'fade-up': 'fadeUp 0.6s ease-out forwards',
      },
    },
  },
};
</script>

<!-- Alpine.js -->
<script defer="" src="https://cdn.jsdelivr.net/npm/alpinejs@3.x.x/dist/cdn.min.js"></script>

<style>
  html { scroll-behavior: smooth; }
  body { background-color: #0A0A0A; -webkit-font-smoothing: antialiased; }
  [x-cloak] { display: none !important; }
  .scrollbar-hide::-webkit-scrollbar { display: none; }
  .scrollbar-hide { -ms-overflow-style: none; scrollbar-width: none; }
  .btn-cta {
    display: inline-flex; align-items: center; justify-content: center; gap: 0.5rem;
    background: #E11D2E; color: #fff; padding: 1rem 1.5rem; border-radius: 0.5rem;
    font-weight: 700; text-transform: uppercase; letter-spacing: 0.05em; font-size: 0.9rem;
    box-shadow: 0 10px 30px -10px rgba(225, 29, 46, 0.6);
    transition: all 0.2s ease;
  }
  .btn-cta:hover { background: #B01523; transform: scale(1.02); }
  .btn-cta:active { transform: scale(0.97); }
  .btn-ghost {
    display: inline-flex; align-items: center; justify-content: center; gap: 0.5rem;
    border: 1px solid rgba(255,255,255,0.15); background: rgba(255,255,255,0.05);
    color: #fff; padding: 1rem 1.5rem; border-radius: 0.5rem;
    font-weight: 600; font-size: 0.9rem; backdrop-filter: blur(8px);
    transition: all 0.2s ease;
  }
  .btn-ghost:hover { background: rgba(255,255,255,0.1); }
  .section-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 3rem; line-height: 1; letter-spacing: -0.01em;
    text-transform: uppercase; color: #fff;
  }
  @media (min-width: 640px) { .section-title { font-size: 3.75rem; } }
  @media (min-width: 1024px) { .section-title { font-size: 4.5rem; } }
  .eyebrow {
    display: inline-block; font-size: 0.7rem; font-weight: 700;
    text-transform: uppercase; letter-spacing: 0.25em; color: #E11D2E;
  }
</style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:Inter, system-ui, sans-serif;font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.fixed{position:fixed}.absolute{position:absolute}.relative{position:relative}.inset-0{inset:0px}.-right-12{right:-3rem}.-top-12{top:-3rem}.-top-3{top:-0.75rem}.bottom-0{bottom:0px}.bottom-3{bottom:0.75rem}.left-0{left:0px}.left-1\/2{left:50%}.left-3{left:0.75rem}.right-0{right:0px}.top-0{top:0px}.z-10{z-index:10}.z-40{z-index:40}.z-50{z-index:50}.mx-auto{margin-left:auto;margin-right:auto}.mb-4{margin-bottom:1rem}.mb-6{margin-bottom:1.5rem}.mb-8{margin-bottom:2rem}.ml-1{margin-left:0.25rem}.mt-0\.5{margin-top:0.125rem}.mt-1{margin-top:0.25rem}.mt-10{margin-top:2.5rem}.mt-12{margin-top:3rem}.mt-14{margin-top:3.5rem}.mt-16{margin-top:4rem}.mt-2{margin-top:0.5rem}.mt-3{margin-top:0.75rem}.mt-4{margin-top:1rem}.mt-6{margin-top:1.5rem}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.aspect-video{aspect-ratio:16 / 9}.h-10{height:2.5rem}.h-2{height:0.5rem}.h-40{height:10rem}.h-5{height:1.25rem}.h-6{height:1.5rem}.h-7{height:1.75rem}.h-full{height:100%}.min-h-screen{min-height:100vh}.w-10{width:2.5rem}.w-2{width:0.5rem}.w-40{width:10rem}.w-5{width:1.25rem}.w-6{width:1.5rem}.w-7{width:1.75rem}.w-72{width:18rem}.w-full{width:100%}.max-w-2xl{max-width:42rem}.max-w-3xl{max-width:48rem}.max-w-4xl{max-width:56rem}.max-w-5xl{max-width:64rem}.max-w-7xl{max-width:80rem}.max-w-md{max-width:28rem}.max-w-xl{max-width:36rem}.max-w-xs{max-width:20rem}.flex-1{flex:1 1 0%}.flex-shrink-0{flex-shrink:0}.-translate-x-1\/2{--tw-translate-x:-50%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.translate-y-full{--tw-translate-y:100%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.translate-y-0{--tw-translate-y:0px;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.rotate-180{--tw-rotate:180deg;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}@keyframes fadeUp{0%{opacity:0;transform:translateY(20px)}100%{opacity:1;transform:translateY(0)}}.animate-fade-up{animation:fadeUp 0.6s ease-out forwards}.snap-x{scroll-snap-type:x var(--tw-scroll-snap-strictness)}.snap-mandatory{--tw-scroll-snap-strictness:mandatory}.snap-start{scroll-snap-align:start}.grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.flex-col{flex-direction:column}.items-start{align-items:flex-start}.items-end{align-items:flex-end}.items-center{align-items:center}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-1{gap:0.25rem}.gap-10{gap:2.5rem}.gap-2{gap:0.5rem}.gap-3{gap:0.75rem}.gap-4{gap:1rem}.gap-6{gap:1.5rem}.gap-8{gap:2rem}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.space-y-4 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1rem * var(--tw-space-y-reverse))}.overflow-hidden{overflow:hidden}.overflow-x-auto{overflow-x:auto}.overflow-x-hidden{overflow-x:hidden}.rounded{border-radius:0.25rem}.rounded-2xl{border-radius:1rem}.rounded-3xl{border-radius:1.5rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-y{border-top-width:1px;border-bottom-width:1px}.border-b{border-bottom-width:1px}.border-t{border-top-width:1px}.border-white\/10{border-color:rgb(255 255 255 / 0.1)}.border-white\/5{border-color:rgb(255 255 255 / 0.05)}.bg-brand-black{--tw-bg-opacity:1;background-color:rgb(10 10 10 / var(--tw-bg-opacity, 1))}.bg-brand-black\/40{background-color:rgb(10 10 10 / 0.4)}.bg-brand-black\/50{background-color:rgb(10 10 10 / 0.5)}.bg-brand-black\/80{background-color:rgb(10 10 10 / 0.8)}.bg-brand-black\/95{background-color:rgb(10 10 10 / 0.95)}.bg-brand-graphite{--tw-bg-opacity:1;background-color:rgb(20 20 20 / var(--tw-bg-opacity, 1))}.bg-brand-graphite\/60{background-color:rgb(20 20 20 / 0.6)}.bg-brand-red{--tw-bg-opacity:1;background-color:rgb(225 29 46 / var(--tw-bg-opacity, 1))}.bg-brand-red\/90{background-color:rgb(225 29 46 / 0.9)}.bg-red-500{--tw-bg-opacity:1;background-color:rgb(239 68 68 / var(--tw-bg-opacity, 1))}.object-cover{object-fit:cover}.p-4{padding:1rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-2{padding-left:0.5rem;padding-right:0.5rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-4{padding-left:1rem;padding-right:1rem}.px-5{padding-left:1.25rem;padding-right:1.25rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.py-0\.5{padding-top:0.125rem;padding-bottom:0.125rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-14{padding-top:3.5rem;padding-bottom:3.5rem}.py-20{padding-top:5rem;padding-bottom:5rem}.py-24{padding-top:6rem;padding-bottom:6rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.py-4{padding-top:1rem;padding-bottom:1rem}.py-5{padding-top:1.25rem;padding-bottom:1.25rem}.pb-20{padding-bottom:5rem}.pb-28{padding-bottom:7rem}.pb-3{padding-bottom:0.75rem}.pb-4{padding-bottom:1rem}.pt-16{padding-top:4rem}.pt-24{padding-top:6rem}.pt-3{padding-top:0.75rem}.pt-6{padding-top:1.5rem}.text-left{text-align:left}.text-center{text-align:center}.font-display{font-family:"Bebas Neue", sans-serif}.font-mono{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace}.font-sans{font-family:Inter, system-ui, sans-serif}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-\[10px\]{font-size:10px}.text-\[11px\]{font-size:11px}.text-base{font-size:1rem;line-height:1.5rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-black{font-weight:900}.font-bold{font-weight:700}.font-medium{font-weight:500}.font-semibold{font-weight:600}.uppercase{text-transform:uppercase}.leading-none{line-height:1}.leading-relaxed{line-height:1.625}.tracking-\[0\.25em\]{letter-spacing:0.25em}.tracking-wide{letter-spacing:0.025em}.tracking-wider{letter-spacing:0.05em}.tracking-widest{letter-spacing:0.1em}.text-brand-red{--tw-text-opacity:1;color:rgb(225 29 46 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.text-white\/30{color:rgb(255 255 255 / 0.3)}.text-white\/40{color:rgb(255 255 255 / 0.4)}.text-white\/50{color:rgb(255 255 255 / 0.5)}.text-white\/60{color:rgb(255 255 255 / 0.6)}.text-white\/70{color:rgb(255 255 255 / 0.7)}.text-white\/80{color:rgb(255 255 255 / 0.8)}.opacity-40{opacity:0.4}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.blur-3xl{--tw-blur:blur(64px);filter:var(--tw-blur) var(--tw-brightness) var(--tw-contrast) var(--tw-grayscale) var(--tw-hue-rotate) var(--tw-invert) var(--tw-saturate) var(--tw-sepia) var(--tw-drop-shadow)}.backdrop-blur{--tw-backdrop-blur:blur(8px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.backdrop-blur-md{--tw-backdrop-blur:blur(12px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition{transition-property:color, background-color, border-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-transform{transition-property:transform;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.duration-200{transition-duration:200ms}.ease-out{transition-timing-function:cubic-bezier(0, 0, 0.2, 1)}.ease-in{transition-timing-function:cubic-bezier(0.4, 0, 1, 1)}.hover\:border-brand-red:hover{--tw-border-opacity:1;border-color:rgb(225 29 46 / var(--tw-border-opacity, 1))}.hover\:border-brand-red\/40:hover{border-color:rgb(225 29 46 / 0.4)}.hover\:bg-brand-graphite:hover{--tw-bg-opacity:1;background-color:rgb(20 20 20 / var(--tw-bg-opacity, 1))}.hover\:bg-white\/5:hover{background-color:rgb(255 255 255 / 0.05)}.hover\:bg-white\/\[0\.02\]:hover{background-color:rgb(255 255 255 / 0.02)}.hover\:text-brand-red:hover{--tw-text-opacity:1;color:rgb(225 29 46 / var(--tw-text-opacity, 1))}.hover\:text-white:hover{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}@media (min-width: 640px){.sm\:w-auto{width:auto}.sm\:flex-row{flex-direction:row}.sm\:p-8{padding:2rem}.sm\:px-6{padding-left:1.5rem;padding-right:1.5rem}.sm\:py-20{padding-top:5rem;padding-bottom:5rem}.sm\:py-28{padding-top:7rem;padding-bottom:7rem}.sm\:py-32{padding-top:8rem;padding-bottom:8rem}.sm\:text-base{font-size:1rem;line-height:1.5rem}.sm\:text-lg{font-size:1.125rem;line-height:1.75rem}.sm\:text-sm{font-size:0.875rem;line-height:1.25rem}}@media (min-width: 768px){.md\:flex{display:flex}.md\:hidden{display:none}.md\:-translate-y-2{--tw-translate-y:-0.5rem;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.md\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.md\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}.md\:grid-cols-4{grid-template-columns:repeat(4, minmax(0, 1fr))}.md\:items-stretch{align-items:stretch}.md\:gap-4{gap:1rem}.md\:pb-16{padding-bottom:4rem}}@media (min-width: 1024px){.lg\:px-8{padding-left:2rem;padding-right:2rem}}</style><meta id="dcngeagmmhegagicpcmpinaoklddcgon"></head>
<body class="font-sans text-white min-h-screen overflow-x-hidden">

<!-- ============ HEADER ============ -->
<header x-data="{ open: false }" class="fixed top-0 left-0 right-0 z-50 border-b border-white/5 bg-brand-black/80 backdrop-blur-md">
  <div class="mx-auto flex max-w-7xl items-center justify-between px-4 py-3 sm:px-6 lg:px-8">
    <a href="#" class="flex items-center gap-2">
      <span class="font-display text-2xl tracking-wider text-white">
        PREDEST<span class="text-brand-red">1</span>NADOS
      </span>
    </a>

    <nav class="hidden items-center gap-8 md:flex">
      <a href="#predpack" class="text-sm font-medium text-white/70 transition hover:text-white">O PREDPACK</a>
      <a href="#atualizacoes" class="text-sm font-medium text-white/70 transition hover:text-white">Atualizações</a>
      <a href="#planos" class="text-sm font-medium text-white/70 transition hover:text-white">Planos</a>
      <a href="#faq" class="text-sm font-medium text-white/70 transition hover:text-white">FAQ</a>
      <a href="#planos" class="btn-cta" style="padding: 0.6rem 1.25rem; font-size: 0.8rem;">Quero Acessar</a>
    </nav>

    <button @click="open = !open" class="md:hidden text-white" aria-label="Abrir menu">
      <svg x-show="!open" class="h-7 w-7" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
      </svg>
      <svg x-show="open" class="h-7 w-7" fill="none" stroke="currentColor" viewBox="0 0 24 24" style="display: none;">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path>
      </svg>
    </button>
  </div>

  <div x-show="open" x-transition="" class="border-t border-white/5 bg-brand-black md:hidden" style="display: none;">
    <div class="flex flex-col gap-1 px-4 py-4">
      <a @click="open=false" href="#predpack" class="rounded px-3 py-3 text-white/80 hover:bg-white/5">O PREDPACK</a>
      <a @click="open=false" href="#atualizacoes" class="rounded px-3 py-3 text-white/80 hover:bg-white/5">Atualizações</a>
      <a @click="open=false" href="#planos" class="rounded px-3 py-3 text-white/80 hover:bg-white/5">Planos</a>
      <a @click="open=false" href="#faq" class="rounded px-3 py-3 text-white/80 hover:bg-white/5">FAQ</a>
      <a @click="open=false" href="#planos" class="btn-cta mt-2 w-full">Quero Acessar o PREDPACK</a>
    </div>
  </div>
</header>

<main>

<!-- ============ HERO ============ -->
<section class="relative flex items-center justify-center overflow-hidden pt-24 pb-20" style="min-height: 100svh;">
  <!-- Vídeo de fundo (substitua a URL pela sua) -->
  <video class="absolute inset-0 h-full w-full object-cover opacity-40" autoplay="" muted="" loop="" playsinline="" preload="metadata">
    <source src="https://cdn.coverr.co/videos/coverr-a-cinematic-shot-of-a-city-1570/1080p.mp4" type="video/mp4">
  </video>

  <!-- Overlays cinematográficos -->
  <div class="absolute inset-0" style="background: linear-gradient(to bottom, rgba(10,10,10,.7) 0%, rgba(10,10,10,.6) 50%, #0A0A0A 100%);"></div>
  <div class="absolute inset-0" style="background: radial-gradient(ellipse at center, transparent 0%, rgba(0,0,0,.75) 100%);"></div>

  <div class="relative z-10 mx-auto max-w-5xl px-4 text-center sm:px-6 lg:px-8">
    <span class="eyebrow mb-4 animate-fade-up" style="opacity: 0;">Biblioteca para editores</span>

    <h1 class="section-title animate-fade-up" style="opacity: 0; animation-delay: .1s;">
      Cenas prontas<br>
      <span class="text-brand-red">pra baixar e editar</span>
    </h1>

    <p class="mx-auto mt-6 max-w-2xl animate-fade-up text-base text-white/70 sm:text-lg" style="opacity: 0; animation-delay: .2s;">
      O <strong class="text-white">PREDPACK</strong> é a biblioteca de cenas de filmes e séries
      já selecionadas e cortadas para você. Atualizada <strong class="text-white">3x por semana</strong>,
      pronta pra jogar direto na timeline.
    </p>

    <div class="mt-10 flex flex-col items-center justify-center gap-3 animate-fade-up sm:flex-row" style="opacity: 0; animation-delay: .3s;">
      <a href="#planos" class="btn-cta w-full sm:w-auto">
        QUERO ACESSAR O PREDPACK
        <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path>
        </svg>
      </a>
      <a href="#predpack" class="btn-ghost w-full sm:w-auto">Ver como funciona</a>
    </div>

    <p class="mt-6 text-xs uppercase tracking-widest text-white/40 animate-fade-up" style="opacity: 0; animation-delay: .4s;">
      Acesso imediato · Garantia de 7 dias
    </p>
  </div>
</section>

<!-- ============ AUTORIDADE ============ -->
<section class="border-y border-white/5 bg-brand-graphite py-14 sm:py-20">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="grid grid-cols-2 gap-6 md:grid-cols-4 md:gap-4">
      <div class="text-center">
        <div class="font-display text-white" style="font-size: 3rem; line-height: 1;">4<span class="text-brand-red">anos</span></div>
        <p class="mt-2 text-xs uppercase tracking-widest text-white/50 sm:text-sm">editando vídeos</p>
      </div>
      <div class="text-center">
        <div class="font-display text-white" style="font-size: 3rem; line-height: 1;">+250<span class="text-brand-red">mi</span></div>
        <p class="mt-2 text-xs uppercase tracking-widest text-white/50 sm:text-sm">de visualizações</p>
      </div>
      <div class="text-center">
        <div class="font-display text-white" style="font-size: 3rem; line-height: 1;">+140<span class="text-brand-red">mil</span></div>
        <p class="mt-2 text-xs uppercase tracking-widest text-white/50 sm:text-sm">seguidores</p>
      </div>
      <div class="text-center">
        <div class="font-display text-white" style="font-size: 3rem; line-height: 1;">+25<span class="text-brand-red">mi</span></div>
        <p class="mt-2 text-xs uppercase tracking-widest text-white/50 sm:text-sm">de curtidas</p>
      </div>
    </div>
  </div>
</section>

<!-- ============ O PREDPACK ============ -->
<section id="predpack" class="py-20 sm:py-28">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="mx-auto max-w-3xl text-center">
      <span class="eyebrow mb-4">O que é o PREDPACK</span>
      <h2 class="section-title">
        A biblioteca que <span class="text-brand-red">economiza horas</span> de edição
      </h2>
      <p class="mt-6 text-base text-white/70 sm:text-lg">
        Cenas selecionadas, cortadas e organizadas por categoria. Encontrou a cena?
        Baixou, jogou na timeline e editou. Sem procurar filme, sem caçar o momento exato.
      </p>
    </div>

    <!-- Comparativo -->
    <div class="mt-16 grid gap-4 md:grid-cols-2">
      <!-- SEM -->
      <div class="rounded-2xl border border-white/5 bg-brand-graphite/60 p-6 sm:p-8">
        <div class="mb-4 inline-flex items-center gap-2 rounded-full px-3 py-1 text-xs font-bold uppercase tracking-widest" style="background: rgba(239,68,68,.1); color: #f87171;">
          <span class="h-2 w-2 rounded-full bg-red-500"></span> Sem PREDPACK
        </div>
        <ul class="space-y-4">
          <li class="flex items-start gap-3 text-white/60">
            <svg class="mt-1 h-5 w-5 flex-shrink-0" style="color: rgba(239,68,68,.7);" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            <span>Procurar qual filme tem a cena</span>
          </li>
          <li class="flex items-start gap-3 text-white/60">
            <svg class="mt-1 h-5 w-5 flex-shrink-0" style="color: rgba(239,68,68,.7);" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            <span>Achar o momento exato</span>
          </li>
          <li class="flex items-start gap-3 text-white/60">
            <svg class="mt-1 h-5 w-5 flex-shrink-0" style="color: rgba(239,68,68,.7);" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            <span>Cortar manualmente</span>
          </li>
          <li class="flex items-start gap-3 text-white/60">
            <svg class="mt-1 h-5 w-5 flex-shrink-0" style="color: rgba(239,68,68,.7);" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            <span>Organizar por conta própria</span>
          </li>
          <li class="flex items-start gap-3 text-white/60">
            <svg class="mt-1 h-5 w-5 flex-shrink-0" style="color: rgba(239,68,68,.7);" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"></path></svg>
            <span>Perder horas por cena</span>
          </li>
        </ul>
      </div>

      <!-- COM -->
      <div class="relative overflow-hidden rounded-2xl border p-6 sm:p-8" style="border-color: rgba(225,29,46,.3); background: linear-gradient(135deg, rgba(225,29,46,.1) 0%, #141414 50%, #141414 100%);">
        <div class="absolute -right-12 -top-12 h-40 w-40 rounded-full blur-3xl" style="background: rgba(225,29,46,.2);"></div>
        <div class="relative">
          <div class="mb-4 inline-flex items-center gap-2 rounded-full px-3 py-1 text-xs font-bold uppercase tracking-widest" style="background: rgba(225,29,46,.2); color: #E11D2E;">
            <span class="h-2 w-2 rounded-full bg-brand-red"></span> Com PREDPACK
          </div>
          <ul class="space-y-4">
            <li class="flex items-start gap-3 text-white">
              <svg class="mt-1 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
              <span>Encontrar a cena pronta na biblioteca</span>
            </li>
            <li class="flex items-start gap-3 text-white">
              <svg class="mt-1 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
              <span>Baixar direto</span>
            </li>
            <li class="flex items-start gap-3 text-white">
              <svg class="mt-1 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
              <span>Jogar na timeline e editar</span>
            </li>
            <li class="flex items-start gap-3 text-white">
              <svg class="mt-1 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
              <span>Já vem organizada por categoria</span>
            </li>
            <li class="flex items-start gap-3 text-white">
              <svg class="mt-1 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
              <span>Minutos por cena</span>
            </li>
          </ul>
        </div>
      </div>
    </div>

    <!-- Canais do servidor -->
    <div class="mt-16">
      <p class="mb-6 text-center text-xs font-bold uppercase tracking-[0.25em] text-white/40">
        Dentro do servidor você encontra
      </p>
      <div class="grid grid-cols-2 gap-3 md:grid-cols-4">
        <div class="rounded-xl border border-white/5 bg-brand-graphite/60 p-4 transition hover:border-brand-red/40 hover:bg-brand-graphite">
          <div class="font-mono text-sm font-bold text-brand-red sm:text-base">#pack-de-cenas</div>
          <p class="mt-1 text-xs text-white/50">Biblioteca principal</p>
        </div>
        <div class="rounded-xl border border-white/5 bg-brand-graphite/60 p-4 transition hover:border-brand-red/40 hover:bg-brand-graphite">
          <div class="font-mono text-sm font-bold text-brand-red sm:text-base">#bate-papo</div>
          <p class="mt-1 text-xs text-white/50">Comunidade de editores</p>
        </div>
        <div class="rounded-xl border border-white/5 bg-brand-graphite/60 p-4 transition hover:border-brand-red/40 hover:bg-brand-graphite">
          <div class="font-mono text-sm font-bold text-brand-red sm:text-base">#dicas</div>
          <p class="mt-1 text-xs text-white/50">Técnicas de edição</p>
        </div>
        <div class="rounded-xl border border-white/5 bg-brand-graphite/60 p-4 transition hover:border-brand-red/40 hover:bg-brand-graphite">
          <div class="font-mono text-sm font-bold text-brand-red sm:text-base">#avaliacao</div>
          <p class="mt-1 text-xs text-white/50">Feedback nos seus cortes</p>
        </div>
      </div>
    </div>

    <!-- Carrossel -->
    <div class="mt-16">
      <p class="mb-6 text-center text-xs font-bold uppercase tracking-[0.25em] text-white/40">
        Amostra da biblioteca
      </p>
      <div class="flex snap-x snap-mandatory gap-4 overflow-x-auto pb-4 scrollbar-hide">
        <!-- Cards de exemplo com gradientes (substitua por <img loading="lazy"> reais) -->
        <div class="relative aspect-video w-72 flex-shrink-0 snap-start overflow-hidden rounded-xl border border-white/5" style="background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);">
          <div class="absolute inset-0" style="background: linear-gradient(to top, rgba(0,0,0,.8), transparent);"></div>
          <div class="absolute bottom-3 left-3"><span class="rounded bg-brand-red/90 px-2 py-0.5 text-[10px] font-bold uppercase tracking-widest">Pack</span></div>
        </div>
        <div class="relative aspect-video w-72 flex-shrink-0 snap-start overflow-hidden rounded-xl border border-white/5" style="background: linear-gradient(135deg, #2d1b1b 0%, #4a1e1e 50%, #6b2020 100%);">
          <div class="absolute inset-0" style="background: linear-gradient(to top, rgba(0,0,0,.8), transparent);"></div>
          <div class="absolute bottom-3 left-3"><span class="rounded bg-brand-red/90 px-2 py-0.5 text-[10px] font-bold uppercase tracking-widest">Pack</span></div>
        </div>
        <div class="relative aspect-video w-72 flex-shrink-0 snap-start overflow-hidden rounded-xl border border-white/5" style="background: linear-gradient(135deg, #1a2e1a 0%, #1e3e1e 50%, #205020 100%);">
          <div class="absolute inset-0" style="background: linear-gradient(to top, rgba(0,0,0,.8), transparent);"></div>
          <div class="absolute bottom-3 left-3"><span class="rounded bg-brand-red/90 px-2 py-0.5 text-[10px] font-bold uppercase tracking-widest">Pack</span></div>
        </div>
        <div class="relative aspect-video w-72 flex-shrink-0 snap-start overflow-hidden rounded-xl border border-white/5" style="background: linear-gradient(135deg, #2e1a2e 0%, #3e1e3e 50%, #502050 100%);">
          <div class="absolute inset-0" style="background: linear-gradient(to top, rgba(0,0,0,.8), transparent);"></div>
          <div class="absolute bottom-3 left-3"><span class="rounded bg-brand-red/90 px-2 py-0.5 text-[10px] font-bold uppercase tracking-widest">Pack</span></div>
        </div>
        <div class="relative aspect-video w-72 flex-shrink-0 snap-start overflow-hidden rounded-xl border border-white/5" style="background: linear-gradient(135deg, #2e2a1a 0%, #3e3a1e 50%, #504a20 100%);">
          <div class="absolute inset-0" style="background: linear-gradient(to top, rgba(0,0,0,.8), transparent);"></div>
          <div class="absolute bottom-3 left-3"><span class="rounded bg-brand-red/90 px-2 py-0.5 text-[10px] font-bold uppercase tracking-widest">Pack</span></div>
        </div>
        <div class="relative aspect-video w-72 flex-shrink-0 snap-start overflow-hidden rounded-xl border border-white/5" style="background: linear-gradient(135deg, #1a2e2e 0%, #1e3e3e 50%, #205050 100%);">
          <div class="absolute inset-0" style="background: linear-gradient(to top, rgba(0,0,0,.8), transparent);"></div>
          <div class="absolute bottom-3 left-3"><span class="rounded bg-brand-red/90 px-2 py-0.5 text-[10px] font-bold uppercase tracking-widest">Pack</span></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ ATUALIZAÇÕES ============ -->
<section id="atualizacoes" class="border-y border-white/5 bg-brand-graphite py-20 sm:py-28">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="mx-auto max-w-3xl text-center">
      <span class="eyebrow mb-4">Sempre atualizado</span>
      <h2 class="section-title">
        Novas cenas <span class="text-brand-red">3x por semana</span>
      </h2>
      <p class="mt-6 text-base text-white/70 sm:text-lg">
        A biblioteca não para de crescer. Toda semana entram cenas novas, organizadas
        por categoria — e você tem acesso a <strong class="text-white">centenas de clipes desde o primeiro acesso</strong>.
      </p>
    </div>

    <div class="mt-14 grid gap-4 md:grid-cols-3">
      <div class="rounded-2xl border border-white/5 bg-brand-black/50 p-6 text-center">
        <div class="font-display text-brand-red" style="font-size: 3rem; line-height: 1;">3x</div>
        <p class="mt-1 text-xs font-bold uppercase tracking-widest text-white/40">por semana</p>
        <p class="mt-4 text-sm font-semibold text-white">Novas cenas adicionadas</p>
        <p class="mt-1 text-xs text-white/40">Ter, Qui e Sáb</p>
      </div>
      <div class="rounded-2xl border border-white/5 bg-brand-black/50 p-6 text-center">
        <div class="font-display text-brand-red" style="font-size: 3rem; line-height: 1;">+100</div>
        <p class="mt-1 text-xs font-bold uppercase tracking-widest text-white/40">clipes</p>
        <p class="mt-4 text-sm font-semibold text-white">Biblioteca acumulada</p>
        <p class="mt-1 text-xs text-white/40">Desde o início</p>
      </div>
      <div class="rounded-2xl border border-white/5 bg-brand-black/50 p-6 text-center">
        <div class="font-display text-brand-red" style="font-size: 3rem; line-height: 1;">0</div>
        <p class="mt-1 text-xs font-bold uppercase tracking-widest text-white/40">espera</p>
        <p class="mt-4 text-sm font-semibold text-white">Acesso imediato</p>
        <p class="mt-1 text-xs text-white/40">Após confirmação</p>
      </div>
    </div>
  </div>
</section>

<!-- ============ PLANOS ============ -->
<section id="planos" class="py-20 sm:py-28">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="mx-auto max-w-3xl text-center">
      <span class="eyebrow mb-4">Escolha seu plano</span>
      <h2 class="section-title">Acesso ao <span class="text-brand-red">PREDPACK</span></h2>
      <p class="mt-6 text-base text-white/70">
        Mesmo conteúdo, mesmo acesso. Escolha a frequência que faz mais sentido pra você.
      </p>
    </div>

    <div class="mt-14 grid gap-6 md:grid-cols-2 md:items-stretch">
      <!-- PLANO MENSAL -->
      <div class="relative flex flex-col rounded-3xl border p-8 transition border-white/10 bg-brand-graphite">
        <div class="mb-6">
          <h3 class="font-display text-3xl uppercase tracking-wide text-white">Mensal</h3>
          <div class="mt-4 flex items-end gap-1">
            <span class="text-sm text-white/50">R$</span>
            <span class="font-display leading-none text-white" style="font-size: 4rem;">29</span>
            <span class="font-display leading-none text-white" style="font-size: 2rem;">,90</span>
            <span class="ml-1 text-sm text-white/50">/mês</span>
          </div>
        </div>

        <ul class="mb-8 flex-1 space-y-3">
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Acesso completo ao PREDPACK</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Novas cenas 3x por semana</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Centenas de clipes desde o 1º acesso</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Canais do servidor: #pack de cenas, #bate-papo, #dicas e #avaliação</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Acesso via Discord</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Suporte direto</span>
          </li>
        </ul>

        <a href="https://pay.kiwify.com.br/lq10xeg" target="_blank" rel="noopener" class="btn-cta w-full" style="background: #fff; color: #0A0A0A;">
          QUERO O MENSAL
        </a>
        <p class="mt-4 text-center text-xs text-white/40">Compra segura via Kiwify</p>
      </div>

      <!-- PLANO ANUAL (DESTAQUE) -->
      <div class="relative flex flex-col rounded-3xl border p-8 transition md:-translate-y-2" style="border-color: rgba(225,29,46,.5); background: linear-gradient(to bottom, rgba(225,29,46,.1) 0%, #141414 40%, #141414 100%); box-shadow: 0 25px 50px -12px rgba(225,29,46,.15);">
        <div class="absolute -top-3 left-1/2 -translate-x-1/2 rounded-full bg-brand-red px-4 py-1 text-[11px] font-black uppercase tracking-widest text-white shadow-lg">
          Mais vantajoso
        </div>

        <div class="mb-6">
          <h3 class="font-display text-3xl uppercase tracking-wide text-white">Anual</h3>
          <div class="mt-4 flex items-end gap-1">
            <span class="text-sm text-white/50">R$</span>
            <span class="font-display leading-none text-white" style="font-size: 4rem;">169</span>
            <span class="font-display leading-none text-white" style="font-size: 2rem;">,90</span>
            <span class="ml-1 text-sm text-white/50">/ano</span>
          </div>
        </div>

        <ul class="mb-8 flex-1 space-y-3">
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Tudo do plano mensal</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Economia de mais de 50%</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Acesso por 12 meses completos</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Prioridade em novos packs</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Canais do servidor: #pack de cenas, #bate-papo, #dicas e #avaliação</span>
          </li>
          <li class="flex items-start gap-3 text-sm text-white/80">
            <svg class="mt-0.5 h-5 w-5 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2.5" d="M5 13l4 4L19 7"></path></svg>
            <span>Acesso via Discord</span>
          </li>
        </ul>

        <a href="https://pay.kiwify.com.br/1Vna5ZS" target="_blank" rel="noopener" class="btn-cta w-full">
          QUERO O ANUAL
          <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path></svg>
        </a>
        <p class="mt-4 text-center text-xs text-white/40">Compra segura via Kiwify</p>
      </div>
    </div>

    <!-- Garantia -->
    <div class="mx-auto mt-10 flex max-w-md items-center justify-center gap-3 rounded-full border border-white/10 bg-brand-graphite/60 px-6 py-3">
      <svg class="h-6 w-6 flex-shrink-0 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path>
      </svg>
      <span class="text-sm font-semibold text-white/80">Garantia de <strong class="text-white">7 dias</strong> — risco zero</span>
    </div>
  </div>
</section>

<!-- ============ FAQ ============ -->
<section id="faq" class="border-t border-white/5 bg-brand-graphite py-20 sm:py-28">
  <div class="mx-auto max-w-3xl px-4 sm:px-6 lg:px-8">
    <div class="text-center">
      <span class="eyebrow mb-4">Dúvidas frequentes</span>
      <h2 class="section-title">Perguntas <span class="text-brand-red">frequentes</span></h2>
    </div>

    <div class="mt-12 space-y-3" x-data="{ open: 0 }">
      <!-- FAQ 1 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 0 ? null : 0)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">O que é o PREDPACK?</span>
          <svg :class="open === 0 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 rotate-180 text-brand-red" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 0" x-collapse="">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            O PREDPACK é uma biblioteca de cenas de filmes e séries já selecionadas, cortadas e organizadas, prontas para você usar nas suas edições. Não é um acervo de filmes completos — é uma curadoria pensada para editores que precisam de cenas específicas com agilidade.
          </p>
        </div>
      </div>

      <!-- FAQ 2 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 1 ? null : 1)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">O que está incluído no PREDPACK?</span>
          <svg :class="open === 1 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 text-white/40" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 1" x-collapse="" style="display: none;">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            Você recebe acesso ao servidor no Discord com o canal #pack de cenas (biblioteca organizada por categorias), além dos canais #bate-papo, #dicas e #avaliação. As cenas já vêm cortadas e prontas para download e uso imediato na sua timeline.
          </p>
        </div>
      </div>

      <!-- FAQ 3 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 2 ? null : 2)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">As cenas já vêm cortadas?</span>
          <svg :class="open === 2 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 text-white/40" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 2" x-collapse="" style="display: none;">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            Sim. Todas as cenas são previamente selecionadas e cortadas pelos nossos editores. Você não perde tempo procurando o momento exato — é só baixar e jogar na timeline.
          </p>
        </div>
      </div>

      <!-- FAQ 4 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 3 ? null : 3)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">Com que frequência o PREDPACK é atualizado?</span>
          <svg :class="open === 3 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 text-white/40" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 3" x-collapse="" style="display: none;">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            Novas cenas são adicionadas 3 vezes por semana. Assim que você entra, já tem acesso a centenas de clipes acumulados desde o início do projeto, e continua recebendo conteúdo novo constantemente.
          </p>
        </div>
      </div>

      <!-- FAQ 5 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 4 ? null : 4)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">Que tipos de cenas estão disponíveis?</span>
          <svg :class="open === 4 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 text-white/40" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 4" x-collapse="" style="display: none;">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            Cenas de filmes e séries em geral: ação, drama, diálogos, transições, momentos icônicos, reações e muito mais — todas organizadas por categoria para você achar rápido o que precisa para cada tipo de edição.
          </p>
        </div>
      </div>

      <!-- FAQ 6 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 5 ? null : 5)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">Como funciona o acesso?</span>
          <svg :class="open === 5 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 text-white/40" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 5" x-collapse="" style="display: none;">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            Após a confirmação do pagamento, você recebe o convite para o servidor do Discord, onde fica toda a biblioteca. O acesso é imediato e você pode usar no celular ou no desktop.
          </p>
        </div>
      </div>

      <!-- FAQ 7 -->
      <div class="overflow-hidden rounded-xl border border-white/5 bg-brand-black/40">
        <button @click="open = (open === 6 ? null : 6)" class="flex w-full items-center justify-between gap-4 px-5 py-5 text-left transition hover:bg-white/[0.02]">
          <span class="font-semibold text-white">Tem garantia?</span>
          <svg :class="open === 6 ? 'rotate-180 text-brand-red' : 'text-white/40'" class="h-5 w-5 flex-shrink-0 transition-transform duration-300 text-white/40" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
          </svg>
        </button>
        <div x-show="open === 6" x-collapse="" style="display: none;">
          <p class="border-t border-white/5 px-5 py-5 text-sm leading-relaxed text-white/70">
            Sim. Você tem 7 dias de garantia. Se por qualquer motivo não fizer sentido pra você, é só solicitar o reembolso dentro desse período.
          </p>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ============ CTA FINAL ============ -->
<section class="relative overflow-hidden py-24 sm:py-32">
  <div class="absolute inset-0" style="background: radial-gradient(circle at center, rgba(225,29,46,0.15) 0%, transparent 60%);"></div>
  <div class="relative mx-auto max-w-4xl px-4 text-center sm:px-6 lg:px-8">
    <h2 class="section-title">
      Pare de <span class="text-brand-red">perder tempo</span><br>procurando cenas.
    </h2>
    <p class="mx-auto mt-6 max-w-xl text-base text-white/70 sm:text-lg">
      Acesso imediato ao PREDPACK, atualizado 3x por semana, com centenas de clipes prontos para editar.
    </p>
    <div class="mt-10">
      <a href="#planos" class="btn-cta" style="font-size: 1rem;">
        QUERO ACESSAR O PREDPACK
        <svg class="h-5 w-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"></path>
        </svg>
      </a>
    </div>
    <p class="mt-6 text-xs uppercase tracking-widest text-white/40">
      Garantia de 7 dias · Compra segura
    </p>
  </div>
</section>

</main>

<!-- ============ FOOTER ============ -->
<footer class="border-t border-white/5 bg-brand-black pb-28 pt-16 md:pb-16">
  <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
    <div class="grid gap-10 md:grid-cols-3">
      <div>
        <div class="font-display text-2xl tracking-wider text-white">
          PREDEST<span class="text-brand-red">1</span>NADOS
        </div>
        <p class="mt-3 max-w-xs text-sm text-white/50">
          Biblioteca de cenas para editores. Conteúdo organizado, atualizado e pronto para uso.
        </p>
      </div>

      <div>
        <p class="mb-4 text-xs font-bold uppercase tracking-widest text-white/40">Navegação</p>
        <ul class="space-y-3 text-sm">
          <li><a href="#predpack" class="text-white/70 transition hover:text-brand-red">O PREDPACK</a></li>
          <li><a href="#atualizacoes" class="text-white/70 transition hover:text-brand-red">Atualizações</a></li>
          <li><a href="#planos" class="text-white/70 transition hover:text-brand-red">Planos</a></li>
          <li><a href="#faq" class="text-white/70 transition hover:text-brand-red">FAQ</a></li>
        </ul>
      </div>

      <div>
        <p class="mb-4 text-xs font-bold uppercase tracking-widest text-white/40">Redes</p>
        <div class="flex gap-3">
          <a href="https://www.instagram.com/predestinadosbackup/" target="_blank" rel="noopener" class="flex h-10 w-10 items-center justify-center rounded-lg border border-white/10 text-white/70 transition hover:border-brand-red hover:text-brand-red" aria-label="Instagram">
            <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zM12 0C8.741 0 8.333.014 7.053.072 2.695.272.273 2.69.073 7.052.014 8.333 0 8.741 0 12c0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98C8.333 23.986 8.741 24 12 24c3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98C15.668.014 15.259 0 12 0zm0 5.838a6.162 6.162 0 100 12.324 6.162 6.162 0 000-12.324zM12 16a4 4 0 110-8 4 4 0 010 8zm6.406-11.845a1.44 1.44 0 100 2.881 1.44 1.44 0 000-2.881z"></path>
            </svg>
          </a>
          <a href="https://www.tiktok.com/@predest1nadoscore" target="_blank" rel="noopener" class="flex h-10 w-10 items-center justify-center rounded-lg border border-white/10 text-white/70 transition hover:border-brand-red hover:text-brand-red" aria-label="TikTok">
            <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 24 24">
              <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"></path>
            </svg>
          </a>
        </div>
      </div>
    </div>

    <div class="mt-12 border-t border-white/5 pt-6">
      <p class="text-center text-xs text-white/40">
        © <span id="year">2026</span> PREDEST1NADOS. Todos os direitos reservados.
      </p>
      <p class="mx-auto mt-4 max-w-2xl text-center text-[11px] leading-relaxed text-white/30">
        O PREDPACK é uma ferramenta de apoio à edição, oferecida pela PREDEST1NADOS, contendo cenas selecionadas e cortadas. Não reivindicamos propriedade ou direitos sobre os filmes, séries ou quaisquer obras originais eventualmente referenciadas. Todo o conteúdo de terceiros permanece de titularidade de seus respectivos detentores.
      </p>
    </div>
  </div>
</footer>

<!-- ============ CTA FIXO MOBILE ============ -->
<div x-data="{
    visible: false,
    plansVisible: false,
    init() {
      const onScroll = () =&gt; { this.visible = window.scrollY &gt; 600; };
      window.addEventListener('scroll', onScroll, { passive: true });
      onScroll();
      const plans = document.getElementById('planos');
      if (plans) {
        const obs = new IntersectionObserver((entries) =&gt; {
          entries.forEach(e =&gt; this.plansVisible = e.isIntersecting);
        }, { threshold: 0.15 });
        obs.observe(plans);
      }
    }
  }" x-show="visible &amp;&amp; !plansVisible" x-transition:enter="transition ease-out duration-300" x-transition:enter-start="translate-y-full" x-transition:enter-end="translate-y-0" x-transition:leave="transition ease-in duration-200" x-transition:leave-start="translate-y-0" x-transition:leave-end="translate-y-full" class="fixed bottom-0 left-0 right-0 z-40 border-t border-white/10 bg-brand-black/95 px-4 pb-3 pt-3 backdrop-blur md:hidden" style="padding-bottom: max(0.75rem, env(safe-area-inset-bottom)); display: none;">
  <a href="#planos" class="btn-cta w-full" style="padding: 0.9rem 1.5rem; font-size: 0.85rem;">
    QUERO ACESSAR O PREDPACK
  </a>
</div>

<script>
  document.getElementById('year').textContent = new Date().getFullYear();
</script>



</body></html>
