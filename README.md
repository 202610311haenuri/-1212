<!doctype html>
<html lang="ko"><head><script>window["__codeletBootstrap__"]=JSON.parse('{"A":"A","B":"20261019-00-0efa619","C":{"Abril Fatface":"YACgEZbkUVE,0","Albert Sans":"YAHO2HRfeh4,0","Alfa Slab One":"YACgEYS9sJU,0","Anton":"YACgEcYqQ-A,0","Archivo Black":"YACgEZulLoA,0","Archivo":"YAHO2-t-jNE,0","Arial":"YAGyDvJ_4Ts,0","Baloo 2":"YAHO2IcQUcM,0","Barlow Condensed":"YAFdJljEuFc,0","Barlow":"YAFdJsyuOPM,1","Bebas Neue":"YACgESME5ew,0","Bricolage Grotesque":"YAFyMcdwzpc,0","Cairo":"YAFdtXpDzlQ,0","Canva Sans":"YAFdJjTk5UU,1","Caveat":"YALBs2ploWQ,0","Cinzel":"YACgEeV8bIQ,0","Cormorant Garamond":"YAFdJhX-538,0","Courier New":"YAGzXiGs0_8,0","Courier Prime":"YAD1aFjegN8,0","DM Sans":"YAD1aU3sLnI,0","DM Serif Display":"YAD1aYG82rc,0","Figtree":"YAHO2b-mV7A,0","Forum":"YACgEcnnqB4,0","Fraunces":"YAFdJpU7Kkk,0","Fredoka":"YACgEZml080,0","Georgia":"YAGzXkO0pEM,0","Hanken Grotesk":"YAHO2VB9G0I,0","Helvetica":"YAFcf7zkXN0,0","IBM Plex Mono":"YAFdJkmvhGI,0","IBM Plex Sans":"YAFdJgT0SHI,0","Impact":"YAFcfnjI7Vk,0","Instrument Sans":"YAHO2bKyaSQ,0","Instrument Serif":"YAHFeOnZNEk,0","Inter":"YAFdJvSyp_k,3","Italiana":"YAHO2Toik_w,0","Jacques Francois":"YAHO2a5g66Q,0","JetBrains Mono":"YAFdJksXcAk,0","Josefin Sans":"YAFdJjvw9Ps,0","Karla":"YAHO2V2NSXM,0","Lato":"YAFdJuFCnaw,0","Libre Baskerville":"YACgEUFdPdA,0","Libre Caslon Display":"YAHO2XhLmt0,0","Lobster":"YAD8SnSjSFI,0","Lora":"YACgEXvxf8Q,0","Manrope":"YAHO2b2feC4,0","Merriweather":"YACgEXvHxxs,0","Montserrat":"YAFdtQi73Xs,0","Noto Sans JP":"YAFdJiHXlcI,0","Noto Sans KR":"YAGsojZj-RQ,0","Nunito Sans":"YAFdtQJYB9w,1","Nunito":"YAFdJoNRMmU,1","Oleo Script":"YACgEQQ14jI,0","Open Sans":"YAFdJt8dAY0,1","Oswald":"YACgEQY10lw,0","Outfit":"YAHO2nVlg14,0","Pacifico":"YADLjORQ1u4,0","Playfair Display":"YAFdJhem5V8,1","Plus Jakarta Sans":"YAHO2gdhi18,0","Poppins":"YAFdJjbTu24,1","Press Start 2P":"YAFyGr-8pmQ,0","Public Sans":"YAFdJj8NdaU,1","Quicksand":"YAFdJpYtCxE,1","Raleway":"YAFdJhmxbVQ,1","Roboto Slab":"YAFdJswIKAg,0","Rockwell":"YAFcfyVZnN0,0","Rye":"YACgEdQP21k,0","STIX Two Text":"YAHO2joycuk,0","Sarabun":"YAFdJssSnME,0","Schibsted Grotesk":"YAHO2sWydRk,0","Segoe UI":"YAHNdRD1Klw,0","Source Sans 3":"YAG4lO1Mj10,0","Space Grotesk":"YAHO2sjPCSM,0","Space Mono":"YADW1-vpsoc,0","Spectral":"YAHO2rVUHIM,0","Times New Roman":"YAGzXW3gftg,0","Trebuchet MS":"YAFcfrglpVA,0","Ubuntu":"YACgERDU--Q,0","Verdana":"YAGzXTctYtQ,0","Work Sans":"YAGXhLOKv44,0","Yellowtail":"YACgEYG4kG4,0"}}');</script><script src="/_sdk/05db820ba1544614.telemetry_sdk.js" integrity="sha512-a7JzkQDDcioSXpM61nxTfeRW7PcxWQy5+BrhyeTFmQFsXJ+Gncm0y50u7fTA7qOPegFnRgqCfa0mGUOK1yjDWQ=="></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>중1 과학 - 힘의 합성 및 평형 시뮬레이션</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Pretendard:wght@400;600;700;800&amp;display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
            background-color: #f0f4f8;
            user-select: none;
        }
        /* 격자 무늬 배경 스타일 */
        .grid-bg {
            background-size: 25px 25px;
            background-image: 
                linear-gradient(to right, rgba(148, 163, 184, 0.25) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(148, 163, 184, 0.25) 1px, transparent 1px);
        }
        /* 슬라이더 커스텀 스타일 */
        input[type=range] {
            -webkit-appearance: none;
            appearance: none;
            background: transparent;
            cursor: pointer;
        }
        input[type=range]::-webkit-slider-runnable-track {
            height: 10px;
            border-radius: 999px;
        }
        input[type=range]::-webkit-slider-thumb {
            -webkit-appearance: none;
            appearance: none;
            height: 24px;
            width: 24px;
            border-radius: 50%;
            margin-top: -7px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.25);
            transition: transform 0.15s ease;
        }
        input[type=range]::-webkit-slider-thumb:hover {
            transform: scale(1.15);
        }
        .slider-blue::-webkit-slider-runnable-track { background: #dbeafe; }
        .slider-blue::-webkit-slider-thumb { background: #2563eb; border: 3px solid #ffffff; }
        .slider-orange::-webkit-slider-runnable-track { background: #ffedd5; }
        .slider-orange::-webkit-slider-thumb { background: #ea580c; border: 3px solid #ffffff; }

        /* 평형 달성 글로우 효과 */
        .equilibrium-glow {
            box-shadow: 0 0 25px rgba(16, 185, 129, 0.55);
        }
        @keyframes floatPulse {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-4px); }
        }
        .badge-float {
            animation: floatPulse 2s infinite ease-in-out;
        }
    </style>
<style>*, ::before, ::after{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgb(59 130 246 / 0.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: ;--tw-contain-size: ;--tw-contain-layout: ;--tw-contain-paint: ;--tw-contain-style: }/* ! tailwindcss v3.4.17 | MIT License | https://tailwindcss.com */*,::after,::before{box-sizing:border-box;border-width:0;border-style:solid;border-color:#e5e7eb}::after,::before{--tw-content:''}:host,html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;tab-size:4;font-family:ui-sans-serif, system-ui, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-feature-settings:normal;font-variation-settings:normal;-webkit-tap-highlight-color:transparent}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace;font-feature-settings:normal;font-variation-settings:normal;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-feature-settings:inherit;font-variation-settings:inherit;font-size:100%;font-weight:inherit;line-height:inherit;letter-spacing:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}button,input:where([type=button]),input:where([type=reset]),input:where([type=submit]){-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0;padding:0}legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}dialog{padding:0}textarea{resize:vertical}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]:where(:not([hidden=until-found])){display:none}.pointer-events-none{pointer-events:none}.absolute{position:absolute}.relative{position:relative}.bottom-4{bottom:1rem}.left-1\/2{left:50%}.top-16{top:4rem}.top-4{top:1rem}.z-10{z-index:10}.z-20{z-index:20}.mx-auto{margin-left:auto;margin-right:auto}.my-4{margin-top:1rem;margin-bottom:1rem}.mb-1{margin-bottom:0.25rem}.mb-2{margin-bottom:0.5rem}.mb-3{margin-bottom:0.75rem}.mt-0\.5{margin-top:0.125rem}.mt-1{margin-top:0.25rem}.mt-2{margin-top:0.5rem}.mt-4{margin-top:1rem}.block{display:block}.inline-block{display:inline-block}.flex{display:flex}.inline-flex{display:inline-flex}.grid{display:grid}.hidden{display:none}.h-11{height:2.75rem}.h-2\.5{height:0.625rem}.h-3{height:0.75rem}.h-3\.5{height:0.875rem}.h-4{height:1rem}.h-7{height:1.75rem}.h-80{height:20rem}.h-auto{height:auto}.h-full{height:100%}.min-h-screen{min-height:100vh}.w-11{width:2.75rem}.w-3{width:0.75rem}.w-3\.5{width:0.875rem}.w-4{width:1rem}.w-7{width:1.75rem}.w-full{width:100%}.max-w-5xl{max-width:64rem}.max-w-full{max-width:100%}.max-w-md{max-width:28rem}.flex-1{flex:1 1 0%}.shrink-0{flex-shrink:0}.-translate-x-1\/2{--tw-translate-x:-50%;transform:translate(var(--tw-translate-x), var(--tw-translate-y)) rotate(var(--tw-rotate)) skewX(var(--tw-skew-x)) skewY(var(--tw-skew-y)) scaleX(var(--tw-scale-x)) scaleY(var(--tw-scale-y))}.cursor-pointer{cursor:pointer}.grid-cols-1{grid-template-columns:repeat(1, minmax(0, 1fr))}.grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.flex-col{flex-direction:column}.flex-wrap{flex-wrap:wrap}.items-center{align-items:center}.items-baseline{align-items:baseline}.justify-end{justify-content:flex-end}.justify-center{justify-content:center}.justify-between{justify-content:space-between}.gap-1{gap:0.25rem}.gap-1\.5{gap:0.375rem}.gap-2{gap:0.5rem}.gap-2\.5{gap:0.625rem}.gap-3{gap:0.75rem}.gap-3\.5{gap:0.875rem}.gap-4{gap:1rem}.gap-5{gap:1.25rem}.space-y-1\.5 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.375rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.375rem * var(--tw-space-y-reverse))}.space-y-2 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.5rem * var(--tw-space-y-reverse))}.space-y-3 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(0.75rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(0.75rem * var(--tw-space-y-reverse))}.space-y-5 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.25rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.25rem * var(--tw-space-y-reverse))}.space-y-6 > :not([hidden]) ~ :not([hidden]){--tw-space-y-reverse:0;margin-top:calc(1.5rem * calc(1 - var(--tw-space-y-reverse)));margin-bottom:calc(1.5rem * var(--tw-space-y-reverse))}.overflow-hidden{overflow:hidden}.whitespace-nowrap{white-space:nowrap}.rounded{border-radius:0.25rem}.rounded-2xl{border-radius:1rem}.rounded-full{border-radius:9999px}.rounded-lg{border-radius:0.5rem}.rounded-xl{border-radius:0.75rem}.border{border-width:1px}.border-2{border-width:2px}.border-b{border-bottom-width:1px}.border-blue-100{--tw-border-opacity:1;border-color:rgb(219 234 254 / var(--tw-border-opacity, 1))}.border-emerald-200{--tw-border-opacity:1;border-color:rgb(167 243 208 / var(--tw-border-opacity, 1))}.border-orange-100{--tw-border-opacity:1;border-color:rgb(255 237 213 / var(--tw-border-opacity, 1))}.border-slate-200{--tw-border-opacity:1;border-color:rgb(226 232 240 / var(--tw-border-opacity, 1))}.border-blue-600{--tw-border-opacity:1;border-color:rgb(37 99 235 / var(--tw-border-opacity, 1))}.border-orange-600{--tw-border-opacity:1;border-color:rgb(234 88 12 / var(--tw-border-opacity, 1))}.bg-amber-400{--tw-bg-opacity:1;background-color:rgb(251 191 36 / var(--tw-bg-opacity, 1))}.bg-blue-600{--tw-bg-opacity:1;background-color:rgb(37 99 235 / var(--tw-bg-opacity, 1))}.bg-emerald-50{--tw-bg-opacity:1;background-color:rgb(236 253 245 / var(--tw-bg-opacity, 1))}.bg-indigo-100{--tw-bg-opacity:1;background-color:rgb(224 231 255 / var(--tw-bg-opacity, 1))}.bg-indigo-50{--tw-bg-opacity:1;background-color:rgb(238 242 255 / var(--tw-bg-opacity, 1))}.bg-indigo-600{--tw-bg-opacity:1;background-color:rgb(79 70 229 / var(--tw-bg-opacity, 1))}.bg-orange-50{--tw-bg-opacity:1;background-color:rgb(255 247 237 / var(--tw-bg-opacity, 1))}.bg-orange-600{--tw-bg-opacity:1;background-color:rgb(234 88 12 / var(--tw-bg-opacity, 1))}.bg-rose-600{--tw-bg-opacity:1;background-color:rgb(225 29 72 / var(--tw-bg-opacity, 1))}.bg-slate-100{--tw-bg-opacity:1;background-color:rgb(241 245 249 / var(--tw-bg-opacity, 1))}.bg-slate-200{--tw-bg-opacity:1;background-color:rgb(226 232 240 / var(--tw-bg-opacity, 1))}.bg-slate-50{--tw-bg-opacity:1;background-color:rgb(248 250 252 / var(--tw-bg-opacity, 1))}.bg-slate-50\/60{background-color:rgb(248 250 252 / 0.6)}.bg-white{--tw-bg-opacity:1;background-color:rgb(255 255 255 / var(--tw-bg-opacity, 1))}.bg-white\/20{background-color:rgb(255 255 255 / 0.2)}.bg-white\/90{background-color:rgb(255 255 255 / 0.9)}.bg-gradient-to-r{background-image:linear-gradient(to right, var(--tw-gradient-stops))}.from-emerald-600{--tw-gradient-from:#059669 var(--tw-gradient-from-position);--tw-gradient-to:rgb(5 150 105 / 0) var(--tw-gradient-to-position);--tw-gradient-stops:var(--tw-gradient-from), var(--tw-gradient-to)}.to-teal-600{--tw-gradient-to:#0d9488 var(--tw-gradient-to-position)}.p-1\.5{padding:0.375rem}.p-3{padding:0.75rem}.p-3\.5{padding:0.875rem}.p-4{padding:1rem}.p-5{padding:1.25rem}.p-6{padding:1.5rem}.p-8{padding:2rem}.px-2\.5{padding-left:0.625rem;padding-right:0.625rem}.px-3{padding-left:0.75rem;padding-right:0.75rem}.px-3\.5{padding-left:0.875rem;padding-right:0.875rem}.px-4{padding-left:1rem;padding-right:1rem}.px-5{padding-left:1.25rem;padding-right:1.25rem}.px-6{padding-left:1.5rem;padding-right:1.5rem}.py-0\.5{padding-top:0.125rem;padding-bottom:0.125rem}.py-1{padding-top:0.25rem;padding-bottom:0.25rem}.py-2{padding-top:0.5rem;padding-bottom:0.5rem}.py-2\.5{padding-top:0.625rem;padding-bottom:0.625rem}.py-3{padding-top:0.75rem;padding-bottom:0.75rem}.pt-2{padding-top:0.5rem}.text-left{text-align:left}.text-center{text-align:center}.text-2xl{font-size:1.5rem;line-height:2rem}.text-3xl{font-size:1.875rem;line-height:2.25rem}.text-6xl{font-size:3.75rem;line-height:1}.text-base{font-size:1rem;line-height:1.5rem}.text-lg{font-size:1.125rem;line-height:1.75rem}.text-sm{font-size:0.875rem;line-height:1.25rem}.text-xl{font-size:1.25rem;line-height:1.75rem}.text-xs{font-size:0.75rem;line-height:1rem}.font-bold{font-weight:700}.font-extrabold{font-weight:800}.font-medium{font-weight:500}.font-semibold{font-weight:600}.uppercase{text-transform:uppercase}.leading-relaxed{line-height:1.625}.leading-snug{line-height:1.375}.tracking-wider{letter-spacing:0.05em}.text-blue-600{--tw-text-opacity:1;color:rgb(37 99 235 / var(--tw-text-opacity, 1))}.text-emerald-600{--tw-text-opacity:1;color:rgb(5 150 105 / var(--tw-text-opacity, 1))}.text-indigo-600{--tw-text-opacity:1;color:rgb(79 70 229 / var(--tw-text-opacity, 1))}.text-indigo-700{--tw-text-opacity:1;color:rgb(67 56 202 / var(--tw-text-opacity, 1))}.text-orange-600{--tw-text-opacity:1;color:rgb(234 88 12 / var(--tw-text-opacity, 1))}.text-rose-600{--tw-text-opacity:1;color:rgb(225 29 72 / var(--tw-text-opacity, 1))}.text-slate-400{--tw-text-opacity:1;color:rgb(148 163 184 / var(--tw-text-opacity, 1))}.text-slate-500{--tw-text-opacity:1;color:rgb(100 116 139 / var(--tw-text-opacity, 1))}.text-slate-600{--tw-text-opacity:1;color:rgb(71 85 105 / var(--tw-text-opacity, 1))}.text-slate-700{--tw-text-opacity:1;color:rgb(51 65 85 / var(--tw-text-opacity, 1))}.text-slate-800{--tw-text-opacity:1;color:rgb(30 41 59 / var(--tw-text-opacity, 1))}.text-slate-900{--tw-text-opacity:1;color:rgb(15 23 42 / var(--tw-text-opacity, 1))}.text-white{--tw-text-opacity:1;color:rgb(255 255 255 / var(--tw-text-opacity, 1))}.text-orange-700{--tw-text-opacity:1;color:rgb(194 65 12 / var(--tw-text-opacity, 1))}.accent-indigo-600{accent-color:#4f46e5}.shadow{--tw-shadow:0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 1px 3px 0 var(--tw-shadow-color), 0 1px 2px -1px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-lg{--tw-shadow:0 10px 15px -3px rgb(0 0 0 / 0.1), 0 4px 6px -4px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 10px 15px -3px var(--tw-shadow-color), 0 4px 6px -4px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.shadow-sm{--tw-shadow:0 1px 2px 0 rgb(0 0 0 / 0.05);--tw-shadow-colored:0 1px 2px 0 var(--tw-shadow-color);box-shadow:var(--tw-ring-offset-shadow, 0 0 #0000), var(--tw-ring-shadow, 0 0 #0000), var(--tw-shadow)}.backdrop-blur{--tw-backdrop-blur:blur(8px);-webkit-backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia);backdrop-filter:var(--tw-backdrop-blur) var(--tw-backdrop-brightness) var(--tw-backdrop-contrast) var(--tw-backdrop-grayscale) var(--tw-backdrop-hue-rotate) var(--tw-backdrop-invert) var(--tw-backdrop-opacity) var(--tw-backdrop-saturate) var(--tw-backdrop-sepia)}.transition{transition-property:color, background-color, border-color, fill, stroke, opacity, box-shadow, transform, filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter;transition-property:color, background-color, border-color, text-decoration-color, fill, stroke, opacity, box-shadow, transform, filter, backdrop-filter, -webkit-text-decoration-color, -webkit-backdrop-filter;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.transition-all{transition-property:all;transition-timing-function:cubic-bezier(0.4, 0, 0.2, 1);transition-duration:150ms}.duration-300{transition-duration:300ms}.hover\:bg-amber-300:hover{--tw-bg-opacity:1;background-color:rgb(252 211 77 / var(--tw-bg-opacity, 1))}.hover\:bg-indigo-700:hover{--tw-bg-opacity:1;background-color:rgb(67 56 202 / var(--tw-bg-opacity, 1))}.hover\:bg-slate-200:hover{--tw-bg-opacity:1;background-color:rgb(226 232 240 / var(--tw-bg-opacity, 1))}.hover\:bg-white\/30:hover{background-color:rgb(255 255 255 / 0.3)}.hover\:bg-slate-100:hover{--tw-bg-opacity:1;background-color:rgb(241 245 249 / var(--tw-bg-opacity, 1))}.hover\:text-slate-900:hover{--tw-text-opacity:1;color:rgb(15 23 42 / var(--tw-text-opacity, 1))}@media (min-width: 640px){.sm\:h-96{height:24rem}.sm\:w-auto{width:auto}.sm\:grid-cols-2{grid-template-columns:repeat(2, minmax(0, 1fr))}.sm\:flex-row{flex-direction:row}.sm\:items-center{align-items:center}.sm\:text-base{font-size:1rem;line-height:1.5rem}.sm\:text-sm{font-size:0.875rem;line-height:1.25rem}}@media (min-width: 768px){.md\:w-auto{width:auto}.md\:flex-initial{flex:0 1 auto}.md\:flex-row{flex-direction:row}.md\:p-5{padding:1.25rem}.md\:p-6{padding:1.5rem}.md\:p-8{padding:2rem}.md\:text-2xl{font-size:1.5rem;line-height:2rem}.md\:text-3xl{font-size:1.875rem;line-height:2.25rem}.md\:text-lg{font-size:1.125rem;line-height:1.75rem}}@media (min-width: 1024px){.lg\:grid-cols-3{grid-template-columns:repeat(3, minmax(0, 1fr))}}</style><script src="/_sdk/5fa8f362ef4e2c5f.resizing_sdk.js" integrity="sha512-kKvaRbCwwiCO6OKrcKCvfDux0gj4RnZXfYCdrcqpGf/6E1mrkUTiDrO7dyg1WJhqchEOplL+9VEB3M8hKc9Kww=="></script><script src="/_sdk/570d53629f0b998d.data_sdk.js" integrity="sha512-JEN39+V+Nvv9ZZOVS8vNk1iA9ErZJHTdgOw9KzPuMiK7m0I+KPEr/wmTnCFIQVsDjCZgJWfGnFi1IQh2Io2qyA=="></script></head>
<body class="min-h-screen text-slate-800 p-3 md:p-6" data-html-import-id="html-import-0" data-template-id="__page-root" style="background: rgb(240, 244, 248);">

<div class="max-w-5xl mx-auto space-y-5" data-html-import-id="html-import-1">
    <!-- 상단 헤더 & 모드 전환 탭 -->
    <header class="bg-white rounded-2xl shadow-sm border border-slate-200 p-4 md:p-5 flex flex-col md:flex-row items-center justify-between gap-4 canva-header" data-html-import-id="html-import-2" data-template-id="header-0" style="background: rgb(255, 255, 255);">
        <div class="flex items-center gap-3 w-full md:w-auto" data-html-import-id="html-import-3">
            <div class="w-11 h-11 rounded-xl bg-indigo-600 flex items-center justify-center text-white font-extrabold text-xl shadow-md shrink-0 canva-container" data-html-import-id="html-import-4" data-template-id="div-1" style="background: rgb(79, 70, 229); color: rgb(255, 255, 255); font-weight: 800; font-size: 20px;">
                F
            </div>
            <div data-html-import-id="html-import-5">
                <span class="text-xs font-bold text-indigo-600 bg-indigo-50 px-2.5 py-0.5 rounded-full canva-text" data-html-import-id="html-import-6" data-template-id="span-2" style="background: rgb(238, 242, 255); color: rgb(79, 70, 229); font-weight: 700; font-size: 12px;">중학교 1학년 과학</span>
                <h1 class="text-xl md:text-2xl font-extrabold text-slate-900 mt-0.5 canva-text" data-html-import-id="html-import-7" data-template-id="h1-3" style="color: rgb(15, 23, 42); font-weight: 800; font-size: 24px;">힘의 합성 및 평형 시뮬레이터</h1>
            </div>
        </div>

        <!-- 모드 탭 (3가지 모드) -->
        <div class="flex bg-slate-100 p-1.5 rounded-xl w-full md:w-auto gap-1 canva-container" data-html-import-id="html-import-8" data-template-id="div-4" style="background: rgb(241, 245, 249);">
            <button id="tabFree" onclick="switchMode('free')" class="flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all bg-white text-indigo-600 shadow-sm whitespace-nowrap canva-button" data-html-import-id="html-import-9" data-template-id="button-5" style="background: rgb(255, 255, 255); color: rgb(79, 70, 229); font-family: Pretendard; font-weight: 700; font-size: 14px;">🔬 자유 실험</button>
            <button id="tabQuiz" onclick="switchMode('quiz')" class="flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all text-slate-600 hover:text-slate-900 whitespace-nowrap canva-button" data-html-import-id="html-import-10" data-template-id="button-6" style="color: rgb(71, 85, 105); font-family: Pretendard; font-weight: 700; font-size: 14px;">🎯 평형 맞추기</button>
            <button id="tabExam" onclick="switchMode('exam')" class="flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all text-slate-600 hover:text-slate-900 whitespace-nowrap canva-button" data-html-import-id="html-import-11" data-template-id="button-7" style="color: rgb(71, 85, 105); font-family: Pretendard; font-weight: 700; font-size: 14px;">📝 개념 문제 퀴즈</button>
        </div>
    </header>

    <!-- ========================================== -->
    <!-- 1. 시뮬레이션 영역 (자유 실험 & 평형 맞추기 모드) -->
    <!-- ========================================== -->
    <div id="simulationSection" class="space-y-5" data-html-import-id="html-import-12">
        <!-- 미니게임 미션 배너 (평형 맞추기 모드에서만 표시) -->
        <div id="quizBanner" class="hidden bg-gradient-to-r from-emerald-600 to-teal-600 text-white rounded-2xl p-4 shadow-md flex flex-col sm:flex-row items-center justify-between gap-4" data-html-import-id="html-import-13">
            <div class="flex items-center gap-3" data-html-import-id="html-import-14">
                <div class="text-3xl canva-container" data-html-import-id="html-import-15" data-template-id="div-8" style="color: rgb(255, 255, 255); font-size: 30px;">🏆</div>
                <div data-html-import-id="html-import-16">
                    <div class="flex items-center gap-2" data-html-import-id="html-import-17">
                        <span class="text-xs font-extrabold uppercase tracking-wider bg-white/20 px-2.5 py-0.5 rounded-full canva-text" data-html-import-id="html-import-18" data-template-id="span-9" style="background: rgba(255, 255, 255, 0.2); color: rgb(255, 255, 255); font-weight: 800; font-size: 12px;">미션 챌린지</span>
                        <span id="quizScoreBadge" class="text-xs font-extrabold bg-amber-400 text-slate-900 px-2.5 py-0.5 rounded-full canva-text" data-html-import-id="html-import-19" data-template-id="span-10" style="background: rgb(251, 191, 36); color: rgb(15, 23, 42); font-weight: 800; font-size: 12px;">연속 성공: 0회</span>
                    </div>
                    <p id="quizMissionText" class="text-base md:text-lg font-bold mt-1 canva-text" data-html-import-id="html-import-20" data-template-id="p-11" style="color: rgb(255, 255, 255); font-weight: 700; font-size: 18px;">
                        주어진 힘 1(F₁)을 보고, 힘 2(F₂)를 조절해 상자를 '힘의 평형(합력 0 N)' 상태로 만드세요!
                    </p>
                </div>
            </div>
            <div class="flex items-center gap-2 w-full sm:w-auto justify-end" data-html-import-id="html-import-21">
                <button onclick="checkQuizAnswer()" class="px-4 py-2.5 bg-amber-400 hover:bg-amber-300 text-slate-900 font-extrabold rounded-xl shadow transition text-sm whitespace-nowrap canva-button" data-html-import-id="html-import-22" data-template-id="button-12" style="background: rgb(251, 191, 36); color: rgb(15, 23, 42); font-family: Pretendard; font-weight: 800; font-size: 14px;">
                    ✅ 정답 확인
                </button>
                <button onclick="generateNewQuiz()" class="px-3.5 py-2.5 bg-white/20 hover:bg-white/30 text-white font-bold rounded-xl transition text-sm whitespace-nowrap canva-button" data-html-import-id="html-import-23" data-template-id="button-13" style="background: rgba(255, 255, 255, 0.2); color: rgb(255, 255, 255); font-family: Pretendard; font-weight: 700; font-size: 14px;">
                    🔄 다음 문제
                </button>
            </div>
        </div>

        <!-- 메인 시뮬레이션 뷰포트 카드 -->
        <div class="bg-white rounded-2xl shadow-sm border border-slate-200 overflow-hidden relative canva-container" data-html-import-id="html-import-24" data-template-id="div-14" style="background: rgb(255, 255, 255);">
            <!-- 뷰포트 상단 바 (상태 요약 및 격자 스위치) -->
            <div class="px-4 py-3 bg-slate-50 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2 canva-container" data-html-import-id="html-import-25" data-template-id="div-15" style="background: rgb(248, 250, 252);">
                <div class="flex items-center gap-4 text-xs sm:text-sm font-semibold" data-html-import-id="html-import-26">
                    <span class="flex items-center gap-1.5 text-blue-600 canva-text" data-html-import-id="html-import-27" data-template-id="span-16" style="color: rgb(37, 99, 235);">
                        <span class="w-3 h-3 rounded-full bg-blue-600 inline-block canva-text" data-html-import-id="html-import-28" data-template-id="span-17" style="background: rgb(37, 99, 235);"></span><canva-inline-text data-template-id="canva-inline-text-18" class="canva-text" style="color: rgb(37, 99, 235);">힘 1 (F₁)</canva-inline-text></span>
                    <span class="flex items-center gap-1.5 text-orange-600 canva-text" data-html-import-id="html-import-29" data-template-id="span-19" style="color: rgb(234, 88, 12);">
                        <span class="w-3 h-3 rounded-full bg-orange-600 inline-block canva-text" data-html-import-id="html-import-30" data-template-id="span-20" style="background: rgb(234, 88, 12);"></span><canva-inline-text data-template-id="canva-inline-text-21" class="canva-text" style="color: rgb(234, 88, 12);">힘 2 (F₂)</canva-inline-text></span>
                    <span class="flex items-center gap-1.5 text-rose-600 canva-text" data-html-import-id="html-import-31" data-template-id="span-22" style="color: rgb(225, 29, 72);">
                        <span class="w-3 h-3 rounded-full bg-rose-600 inline-block canva-text" data-html-import-id="html-import-32" data-template-id="span-23" style="background: rgb(225, 29, 72);"></span><canva-inline-text data-template-id="canva-inline-text-24" class="canva-text" style="color: rgb(225, 29, 72);">합력 (알짜힘)</canva-inline-text></span>
                </div>

                <div class="flex items-center gap-3" data-html-import-id="html-import-33">
                    <label class="flex items-center gap-2 text-xs sm:text-sm font-semibold text-slate-600 cursor-pointer canva-text" data-html-import-id="html-import-34" data-template-id="label-25" style="color: rgb(71, 85, 105); font-weight: 600; font-size: 14px;">
                        <input type="checkbox" id="gridToggle" checked="" onchange="toggleGrid()" class="w-4 h-4 accent-indigo-600 rounded cursor-pointer canva-input" data-html-import-id="html-import-35" data-template-id="input-26" style="color: rgb(71, 85, 105); font-family: Pretendard; font-weight: 600; font-size: 14px;">
                        <span data-html-import-id="html-import-36" data-template-id="span-27" class="canva-text" style="color: rgb(71, 85, 105);">모눈 격자 보기 (1칸 = 5 N)</span>
                    </label>
                </div>
            </div>

            <!-- 시뮬레이션 캔버스 영역 -->
            <div id="simViewport" class="relative w-full h-80 sm:h-96 grid-bg bg-slate-50/60 overflow-hidden flex items-center justify-center canva-container" data-html-import-id="html-import-37" data-template-id="div-28" style="background: rgba(248, 250, 252, 0.6);">
                <!-- 상단 실시간 합력 뱃지 -->
                <div class="absolute top-4 left-1/2 -translate-x-1/2 z-10 flex flex-col items-center pointer-events-none" data-html-import-id="html-import-38">
                    <div id="netForceBadge" class="badge-float px-5 py-2 rounded-full font-extrabold text-sm sm:text-base shadow-md transition-all duration-300 flex items-center gap-2 bg-rose-600 text-white canva-container" data-html-import-id="html-import-39" data-template-id="div-29" style="background: rgb(225, 29, 72); color: rgb(255, 255, 255); font-weight: 800; font-size: 16px;"><span data-html-import-id="html-import-40" data-template-id="span-30" class="canva-text" style="color: rgb(255, 255, 255);">합력: 오른쪽 ▶ 10 N</span></div>
                </div>

                <!-- 미니게임 정답 토스트 메시지 -->
                <div id="quizToast" class="hidden absolute top-16 left-1/2 -translate-x-1/2 z-20 px-5 py-2.5 rounded-xl font-extrabold text-sm shadow-lg transition-all" data-html-import-id="html-import-41"></div>

                <!-- HTML5 Canvas -->
                <canvas id="simCanvas" class="w-full h-full block" width="974" height="384" data-html-import-id="html-import-42"></canvas>

                <!-- 하단 시뮬레이션 컨트롤 버튼 플로팅 바 -->
                <div class="absolute bottom-4 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2.5 bg-white/90 backdrop-blur px-4 py-2 rounded-2xl shadow-md border border-slate-200 canva-container" data-html-import-id="html-import-43" data-template-id="div-31" style="background: rgba(255, 255, 255, 0.9);">
                    <button id="playBtn" onclick="togglePlay()" class="px-5 py-2 rounded-xl font-extrabold text-sm bg-indigo-600 hover:bg-indigo-700 text-white shadow transition flex items-center gap-1.5 canva-button" data-html-import-id="html-import-44" data-template-id="button-32" style="background: rgb(79, 70, 229); color: rgb(255, 255, 255); font-family: Pretendard; font-weight: 800; font-size: 14px;">
                        <span id="playIcon" data-html-import-id="html-import-45" data-template-id="span-33" class="canva-text" style="color: rgb(255, 255, 255);">▶</span> <span id="playText" data-html-import-id="html-import-46" data-template-id="span-34" class="canva-text" style="color: rgb(255, 255, 255);">출발 (움직임 관찰)</span>
                    </button>
                    <button onclick="resetBoxPosition()" class="px-4 py-2 rounded-xl font-bold text-sm bg-slate-100 hover:bg-slate-200 text-slate-700 transition flex items-center gap-1 canva-button" data-html-import-id="html-import-47" data-template-id="button-35" style="background: rgb(241, 245, 249); color: rgb(51, 65, 85); font-family: Pretendard; font-weight: 700; font-size: 14px;">↺ 원위치 리셋</button>
                </div>
            </div>
        </div>

        <!-- 컨트롤러 & 학습 해설 그리드 -->
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-5" data-html-import-id="html-import-48">
            <!-- 힘 1 (F1) 컨트롤 카드 -->
            <div id="f1Card" class="bg-white rounded-2xl shadow-sm border-2 border-blue-100 p-5 flex flex-col justify-between transition canva-container" data-html-import-id="html-import-49" data-template-id="div-36" style="background: rgb(255, 255, 255);">
                <div data-html-import-id="html-import-50">
                    <div class="flex items-center justify-between mb-3" data-html-import-id="html-import-51">
                        <div class="flex items-center gap-2" data-html-import-id="html-import-52">
                            <span class="w-3.5 h-3.5 rounded-full bg-blue-600 canva-text" data-html-import-id="html-import-53" data-template-id="span-37" style="background: rgb(37, 99, 235);"></span>
                            <h2 class="font-extrabold text-lg text-slate-800 canva-text" data-html-import-id="html-import-54" data-template-id="h2-38" style="color: rgb(30, 41, 59); font-weight: 800; font-size: 18px;">힘 1 (F₁) 설정</h2>
                        </div>
                        <span id="f1LockBadge" class="hidden text-xs font-bold bg-slate-200 text-slate-700 px-2.5 py-1 rounded-full canva-text" data-html-import-id="html-import-55" data-template-id="span-39" style="background: rgb(226, 232, 240); color: rgb(51, 65, 85); font-weight: 700; font-size: 12px;">🔒 문제 고정값</span>
                    </div>

                    <!-- 크기 슬라이더 -->
                    <div class="my-4" data-html-import-id="html-import-56">
                        <div class="flex justify-between items-baseline mb-2" data-html-import-id="html-import-57">
                            <span class="text-sm font-semibold text-slate-500 canva-text" data-html-import-id="html-import-58" data-template-id="span-40" style="color: rgb(100, 116, 139); font-weight: 600; font-size: 14px;">힘의 크기</span>
                            <span id="f1ValueText" class="text-2xl font-extrabold text-blue-600 canva-text" data-html-import-id="html-import-59" data-template-id="span-41" style="color: rgb(37, 99, 235); font-weight: 800; font-size: 24px;">20 N</span>
                        </div>
                        <input id="f1Slider" type="range" min="0" max="50" step="5" value="20" oninput="updateForceFromUI()" class="w-full slider-blue canva-input" data-html-import-id="html-import-60" data-template-id="input-42" style="color: rgb(30, 41, 59); font-family: Pretendard; font-weight: 400; font-size: 16px;">
                        <div class="flex justify-between text-xs font-bold text-slate-400 mt-1 canva-container" data-html-import-id="html-import-61" data-template-id="div-43" style="color: rgb(148, 163, 184); font-weight: 700; font-size: 12px;">
                            <span data-html-import-id="html-import-62" data-template-id="span-44" class="canva-text" style="color: rgb(148, 163, 184);">0 N</span>
                            <span data-html-import-id="html-import-63" data-template-id="span-45" class="canva-text" style="color: rgb(148, 163, 184);">10 N</span>
                            <span data-html-import-id="html-import-64" data-template-id="span-46" class="canva-text" style="color: rgb(148, 163, 184);">20 N</span>
                            <span data-html-import-id="html-import-65" data-template-id="span-47" class="canva-text" style="color: rgb(148, 163, 184);">30 N</span>
                            <span data-html-import-id="html-import-66" data-template-id="span-48" class="canva-text" style="color: rgb(148, 163, 184);">40 N</span>
                            <span data-html-import-id="html-import-67" data-template-id="span-49" class="canva-text" style="color: rgb(148, 163, 184);">50 N</span>
                        </div>
                    </div>
                </div>

                <!-- 방향 토글 버튼 -->
                <div class="mt-2" data-html-import-id="html-import-68">
                    <span class="text-xs font-bold text-slate-500 block mb-2 canva-text" data-html-import-id="html-import-69" data-template-id="span-50" style="color: rgb(100, 116, 139); font-weight: 700; font-size: 12px;">작용 방향 선택</span>
                    <div class="grid grid-cols-2 gap-2" data-html-import-id="html-import-70">
                        <button id="f1DirLeft" onclick="setDirection(1, -1)" class="py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 bg-blue-600 text-white border-blue-600 shadow-sm canva-button" data-html-import-id="html-import-71" data-template-id="button-51" style="background: rgb(37, 99, 235); color: rgb(255, 255, 255); font-family: Pretendard; font-weight: 700; font-size: 14px;">◀ 왼쪽</button>
                        <button id="f1DirRight" onclick="setDirection(1, 1)" class="py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 bg-slate-50 text-slate-600 border-slate-200 hover:bg-slate-100 canva-button" data-html-import-id="html-import-72" data-template-id="button-52" style="background: rgb(248, 250, 252); color: rgb(71, 85, 105); font-family: Pretendard; font-weight: 700; font-size: 14px;">오른쪽 ▶</button>
                    </div>
                </div>
            </div>

            <!-- 힘 2 (F2) 컨트롤 카드 -->
            <div class="bg-white rounded-2xl shadow-sm border-2 border-orange-100 p-5 flex flex-col justify-between canva-container" data-html-import-id="html-import-73" data-template-id="div-53" style="background: rgb(255, 255, 255);">
                <div data-html-import-id="html-import-74">
                    <div class="flex items-center justify-between mb-3" data-html-import-id="html-import-75">
                        <div class="flex items-center gap-2" data-html-import-id="html-import-76">
                            <span class="w-3.5 h-3.5 rounded-full bg-orange-600 canva-text" data-html-import-id="html-import-77" data-template-id="span-54" style="background: rgb(234, 88, 12);"></span>
                            <h2 class="font-extrabold text-lg text-slate-800 canva-text" data-html-import-id="html-import-78" data-template-id="h2-55" style="color: rgb(30, 41, 59); font-weight: 800; font-size: 18px;">힘 2 (F₂) 설정</h2>
                        </div>
                        <span class="text-xs font-bold text-orange-600 bg-orange-50 px-2.5 py-1 rounded-full canva-text" data-html-import-id="html-import-79" data-template-id="span-56" style="background: rgb(255, 247, 237); color: rgb(234, 88, 12); font-weight: 700; font-size: 12px;">조절 가능</span>
                    </div>

                    <!-- 크기 슬라이더 -->
                    <div class="my-4" data-html-import-id="html-import-80">
                        <div class="flex justify-between items-baseline mb-2" data-html-import-id="html-import-81">
                            <span class="text-sm font-semibold text-slate-500 canva-text" data-html-import-id="html-import-82" data-template-id="span-57" style="color: rgb(100, 116, 139); font-weight: 600; font-size: 14px;">힘의 크기</span>
                            <span id="f2ValueText" class="text-2xl font-extrabold text-orange-600 canva-text" data-html-import-id="html-import-83" data-template-id="span-58" style="color: rgb(234, 88, 12); font-weight: 800; font-size: 24px;">30 N</span>
                        </div>
                        <input id="f2Slider" type="range" min="0" max="50" step="5" value="30" oninput="updateForceFromUI()" class="w-full slider-orange canva-input" data-html-import-id="html-import-84" data-template-id="input-59" style="color: rgb(30, 41, 59); font-family: Pretendard; font-weight: 400; font-size: 16px;">
                        <div class="flex justify-between text-xs font-bold text-slate-400 mt-1 canva-container" data-html-import-id="html-import-85" data-template-id="div-60" style="color: rgb(148, 163, 184); font-weight: 700; font-size: 12px;">
                            <span data-html-import-id="html-import-86" data-template-id="span-61" class="canva-text" style="color: rgb(148, 163, 184);">0 N</span>
                            <span data-html-import-id="html-import-87" data-template-id="span-62" class="canva-text" style="color: rgb(148, 163, 184);">10 N</span>
                            <span data-html-import-id="html-import-88" data-template-id="span-63" class="canva-text" style="color: rgb(148, 163, 184);">20 N</span>
                            <span data-html-import-id="html-import-89" data-template-id="span-64" class="canva-text" style="color: rgb(148, 163, 184);">30 N</span>
                            <span data-html-import-id="html-import-90" data-template-id="span-65" class="canva-text" style="color: rgb(148, 163, 184);">40 N</span>
                            <span data-html-import-id="html-import-91" data-template-id="span-66" class="canva-text" style="color: rgb(148, 163, 184);">50 N</span>
                        </div>
                    </div>
                </div>

                <!-- 방향 토글 버튼 -->
                <div class="mt-2" data-html-import-id="html-import-92">
                    <span class="text-xs font-bold text-slate-500 block mb-2 canva-text" data-html-import-id="html-import-93" data-template-id="span-67" style="color: rgb(100, 116, 139); font-weight: 700; font-size: 12px;">작용 방향 선택</span>
                    <div class="grid grid-cols-2 gap-2" data-html-import-id="html-import-94">
                        <button id="f2DirLeft" onclick="setDirection(2, -1)" class="py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 bg-slate-50 text-slate-600 border-slate-200 hover:bg-slate-100 canva-button" data-html-import-id="html-import-95" data-template-id="button-68" style="background: rgb(248, 250, 252); color: rgb(71, 85, 105); font-family: Pretendard; font-weight: 700; font-size: 14px;">◀ 왼쪽</button>
                        <button id="f2DirRight" onclick="setDirection(2, 1)" class="py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 bg-orange-600 text-white border-orange-600 shadow-sm canva-button" data-html-import-id="html-import-96" data-template-id="button-69" style="background: rgb(234, 88, 12); color: rgb(255, 255, 255); font-family: Pretendard; font-weight: 700; font-size: 14px;">오른쪽 ▶</button>
                    </div>
                </div>
            </div>

            <!-- 실시간 학습 피드백 카드 -->
            <div id="feedbackCard" class="bg-white rounded-2xl shadow-sm border-2 border-slate-200 p-5 flex flex-col justify-between transition-all duration-300 canva-container" data-html-import-id="html-import-97" data-template-id="div-70" style="background: rgb(255, 255, 255);">
                <div data-html-import-id="html-import-98">
                    <div class="flex items-center justify-between mb-3" data-html-import-id="html-import-99">
                        <span class="text-xs font-extrabold uppercase tracking-wider px-2.5 py-1 rounded-full bg-indigo-50 text-indigo-700 canva-text" data-html-import-id="html-import-100" data-template-id="span-71" style="background: rgb(238, 242, 255); color: rgb(67, 56, 202); font-weight: 800; font-size: 12px;">💡 실시간 원리 해설</span>
                        <span id="situationTag" class="text-xs font-bold text-orange-700 bg-orange-50 px-2.5 py-0.5 rounded-full canva-text" data-html-import-id="html-import-101" data-template-id="span-72" style="background: rgb(255, 247, 237); color: rgb(194, 65, 12); font-weight: 700; font-size: 12px;">반대 방향의 두 힘</span>
                    </div>

                    <h3 id="feedbackTitle" class="text-lg font-extrabold text-slate-900 mb-2 canva-text" data-html-import-id="html-import-102" data-template-id="h3-73" style="color: rgb(15, 23, 42); font-weight: 800; font-size: 18px;">두 힘이 반대 방향으로 작용해요!</h3>

                    <p id="feedbackDesc" class="text-sm text-slate-600 leading-relaxed canva-text" data-html-import-id="html-import-103" data-template-id="p-74" style="color: rgb(71, 85, 105); font-size: 14px;"><canva-inline-text data-template-id="canva-inline-text-75" class="canva-text" style="color: rgb(71, 85, 105); font-size: 14px;">서로 반대 방향으로 작용할 때의 합력은 </canva-inline-text><strong data-html-import-id="html-import-104" data-template-id="strong-76" class="canva-text" style="color: rgb(71, 85, 105); font-weight: 700;">큰 힘에서 작은 힘을 뺀 값</strong><canva-inline-text data-template-id="canva-inline-text-77" class="canva-text" style="color: rgb(71, 85, 105); font-size: 14px;">과 같고, 방향은 </canva-inline-text><strong data-html-import-id="html-import-105" data-template-id="strong-78" class="canva-text" style="color: rgb(71, 85, 105); font-weight: 700;">더 큰 힘의 방향</strong><canva-inline-text data-template-id="canva-inline-text-79" class="canva-text" style="color: rgb(71, 85, 105); font-size: 14px;">을 따릅니다.</canva-inline-text></p>
                </div>

                <!-- 수식 계산 박스 -->
                <div class="mt-4 bg-slate-50 rounded-xl p-3.5 border border-slate-200 canva-container" data-html-import-id="html-import-106" data-template-id="div-80" style="background: rgb(248, 250, 252);">
                    <div class="text-xs font-bold text-slate-400 mb-1 canva-container" data-html-import-id="html-import-107" data-template-id="div-81" style="color: rgb(148, 163, 184); font-weight: 700; font-size: 12px;">합력(알짜힘) 계산식</div>
                    <div id="formulaBox" class="text-base font-extrabold text-slate-800 canva-container" data-html-import-id="html-import-108" data-template-id="div-82" style="color: rgb(30, 41, 59); font-weight: 800; font-size: 16px;">합력 = 30 N - 20 N = 10 N (오른쪽)</div>
                </div>
            </div>
        </div>
    </div>

    <!-- ========================================== -->
    <!-- 2. 개념 확인 문제 퀴즈 섹션 (문제 퀴즈 모드) -->
    <!-- ========================================== -->
    <div id="examSection" class="hidden space-y-5" data-html-import-id="html-import-109">
        <!-- 퀴즈 상단 진행도 바 카드 -->
        <div class="bg-white rounded-2xl shadow-sm border border-slate-200 p-5 canva-container" data-html-import-id="html-import-110" data-template-id="div-83" style="background: rgb(255, 255, 255);">
            <div class="flex flex-wrap items-center justify-between gap-4 mb-3" data-html-import-id="html-import-111">
                <div class="flex items-center gap-2.5" data-html-import-id="html-import-112">
                    <span class="px-3 py-1 rounded-full bg-indigo-100 text-indigo-700 font-extrabold text-xs canva-text" data-html-import-id="html-import-113" data-template-id="span-84" style="background: rgb(224, 231, 255); color: rgb(67, 56, 202); font-weight: 800; font-size: 12px;">중1 과학 핵심 문제</span>
                    <h2 class="text-lg font-extrabold text-slate-800 canva-text" data-html-import-id="html-import-114" data-template-id="h2-85" style="color: rgb(30, 41, 59); font-weight: 800; font-size: 18px;">힘의 합성과 평형 마스터 퀴즈</h2>
                </div>
                <div class="flex items-center gap-3" data-html-import-id="html-import-115">
                    <span id="examScoreBadge" class="text-sm font-extrabold text-emerald-600 bg-emerald-50 px-3 py-1 rounded-full border border-emerald-200 canva-text" data-html-import-id="html-import-116" data-template-id="span-86" style="background: rgb(236, 253, 245); color: rgb(5, 150, 105); font-weight: 800; font-size: 14px;">
                        현재 점수: 0 / 5
                    </span>
                    <span id="examProgressText" class="text-sm font-extrabold text-slate-500 canva-text" data-html-import-id="html-import-117" data-template-id="span-87" style="color: rgb(100, 116, 139); font-weight: 800; font-size: 14px;">
                        문제 1 / 5
                    </span>
                </div>
            </div>
            <!-- 진행 게이지 바 -->
            <div class="w-full h-2.5 bg-slate-100 rounded-full overflow-hidden canva-container" data-html-import-id="html-import-118" data-template-id="div-88" style="background: rgb(241, 245, 249);">
                <div id="examProgressBar" class="h-full bg-indigo-600 transition-all duration-300 canva-container" style="width: 20%; background: rgb(79, 70, 229);" data-html-import-id="html-import-119" data-template-id="div-89"></div>
            </div>
        </div>

        <!-- 문제 풀이 메인 카드 -->
        <div id="examQuestionCard" class="bg-white rounded-2xl shadow-sm border border-slate-200 p-6 md:p-8 space-y-6 canva-container" data-html-import-id="html-import-120" data-template-id="div-90" style="background: rgb(255, 255, 255);">
            <!-- 문제 번호 및 질문 -->
            <div class="space-y-3" data-html-import-id="html-import-121">
                <div class="inline-flex items-center gap-2 text-indigo-600 font-extrabold text-sm canva-container" data-html-import-id="html-import-122" data-template-id="div-91" style="color: rgb(79, 70, 229); font-weight: 800; font-size: 14px;">
                    <span id="qNumberBadge" class="w-7 h-7 rounded-lg bg-indigo-600 text-white flex items-center justify-center text-sm canva-text" data-html-import-id="html-import-123" data-template-id="span-92" style="background: rgb(79, 70, 229); color: rgb(255, 255, 255); font-size: 14px;">Q1</span>
                    <span id="qCategoryText" data-html-import-id="html-import-124" data-template-id="span-93" class="canva-text" style="color: rgb(79, 70, 229);">같은 방향의 두 힘의 합성</span>
                </div>
                <h3 id="qTitleText" class="text-xl md:text-2xl font-extrabold text-slate-900 leading-snug canva-text" data-html-import-id="html-import-125" data-template-id="h3-94" style="color: rgb(15, 23, 42); font-weight: 800; font-size: 24px;">
                    문제 텍스트가 여기에 표시됩니다.
                </h3>
            </div>

            <!-- 문제 상황 일러스트 캔버스/다이어그램 박스 -->
            <div id="qDiagramBox" class="bg-slate-50 border border-slate-200 rounded-2xl p-4 flex flex-col items-center justify-center canva-container" data-html-import-id="html-import-126" data-template-id="div-95" style="background: rgb(248, 250, 252);">
                <canvas id="quizDiagramCanvas" width="520" height="140" class="max-w-full h-auto" data-html-import-id="html-import-127"></canvas>
                <p id="qDiagramCaption" class="text-xs font-bold text-slate-400 mt-1 canva-text" data-html-import-id="html-import-128" data-template-id="p-96" style="color: rgb(148, 163, 184); font-weight: 700; font-size: 12px;">▲ 문제 상황 모식도</p>
            </div>

            <!-- 4지선다 보기 그리드 -->
            <div id="qOptionsGrid" class="grid grid-cols-1 sm:grid-cols-2 gap-3.5" data-html-import-id="html-import-129">
                <!-- 자바스크립트에서 동적 생성 -->
            </div>

            <!-- 정답 해설 및 다음 문제 영역 -->
            <div id="qExplanationBox" class="hidden rounded-2xl p-5 border-2 transition-all" data-html-import-id="html-import-130">
                <div class="flex flex-col sm:flex-row sm:items-center justify-between gap-4" data-html-import-id="html-import-131">
                    <div class="space-y-1.5" data-html-import-id="html-import-132">
                        <div id="qResultHeadline" class="text-base font-extrabold flex items-center gap-2" data-html-import-id="html-import-133">
                            <!-- 정답/오답 여부 -->
                        </div>
                        <p id="qExplanationText" class="text-sm text-slate-700 leading-relaxed canva-text" data-html-import-id="html-import-134" data-template-id="p-97" style="color: rgb(51, 65, 85); font-size: 14px;">
                            <!-- 상세 해설 -->
                        </p>
                    </div>
                    <button id="nextQuestionBtn" onclick="nextExamQuestion()" class="px-6 py-3 bg-indigo-600 hover:bg-indigo-700 text-white font-extrabold rounded-xl shadow-md transition text-sm whitespace-nowrap shrink-0 canva-button" data-html-import-id="html-import-135" data-template-id="button-98" style="background: rgb(79, 70, 229); color: rgb(255, 255, 255); font-family: Pretendard; font-weight: 800; font-size: 14px;">
                        다음 문제 ▶
                    </button>
                </div>
            </div>
        </div>

        <!-- 퀴즈 최종 결과 화면 (5문제 완료 후 표시) -->
        <div id="examResultCard" class="hidden bg-white rounded-2xl shadow-sm border border-slate-200 p-8 text-center space-y-6 canva-container" data-html-import-id="html-import-136" data-template-id="div-99" style="background: rgb(255, 255, 255);">
            <div id="resultEmoji" class="text-6xl canva-container" data-html-import-id="html-import-137" data-template-id="div-100" style="color: rgb(30, 41, 59); font-size: 60px;">🎉</div>
            <div class="space-y-2" data-html-import-id="html-import-138">
                <span class="px-3 py-1 rounded-full bg-indigo-50 text-indigo-600 font-extrabold text-xs canva-text" data-html-import-id="html-import-139" data-template-id="span-101" style="background: rgb(238, 242, 255); color: rgb(79, 70, 229); font-weight: 800; font-size: 12px;">퀴즈 완료!</span>
                <h3 id="resultTitle" class="text-2xl md:text-3xl font-extrabold text-slate-900 canva-text" data-html-import-id="html-import-140" data-template-id="h3-102" style="color: rgb(15, 23, 42); font-weight: 800; font-size: 30px;">
                    참 잘했어요! 모든 문제를 풀었습니다.
                </h3>
                <p id="resultSummary" class="text-slate-600 text-base canva-text" data-html-import-id="html-import-141" data-template-id="p-103" style="color: rgb(71, 85, 105); font-size: 16px;"><canva-inline-text data-template-id="canva-inline-text-104" class="canva-text" style="color: rgb(71, 85, 105); font-size: 16px;">
                    총 5문제 중 </canva-inline-text><strong class="text-indigo-600 font-extrabold canva-text" data-html-import-id="html-import-142" data-template-id="strong-105" style="color: rgb(79, 70, 229); font-weight: 800;">0문제</strong><canva-inline-text data-template-id="canva-inline-text-106" class="canva-text" style="color: rgb(71, 85, 105); font-size: 16px;">를 맞혔습니다!
                </canva-inline-text></p>
            </div>

            <div class="max-w-md mx-auto bg-slate-50 rounded-2xl p-5 border border-slate-200 text-left space-y-2 canva-container" data-html-import-id="html-import-143" data-template-id="div-107" style="background: rgb(248, 250, 252);">
                <div class="text-xs font-extrabold text-slate-400 uppercase canva-container" data-html-import-id="html-import-144" data-template-id="div-108" style="color: rgb(148, 163, 184); font-weight: 800; font-size: 12px;">📌 핵심 요약 노트</div>
                <ul class="text-sm text-slate-700 space-y-1.5 font-medium canva-list" data-html-import-id="html-import-145" data-template-id="ul-109" style="color: rgb(51, 65, 85); font-weight: 500; font-size: 14px;">
                    <li data-html-import-id="html-import-146" data-template-id="li-110" class="canva-text" style="color: rgb(51, 65, 85);"><canva-inline-text data-template-id="canva-inline-text-111" class="canva-text" style="color: rgb(51, 65, 85);">• </canva-inline-text><strong data-html-import-id="html-import-147" data-template-id="strong-112" class="canva-text" style="color: rgb(51, 65, 85); font-weight: 700;">같은 방향 두 힘의 합력:</strong><canva-inline-text data-template-id="canva-inline-text-113" class="canva-text" style="color: rgb(51, 65, 85);"> 두 힘의 크기를 더하고($F_1 + F_2$), 방향은 그대로 유지됩니다.</canva-inline-text></li>
                    <li data-html-import-id="html-import-148" data-template-id="li-114" class="canva-text" style="color: rgb(51, 65, 85);"><canva-inline-text data-template-id="canva-inline-text-115" class="canva-text" style="color: rgb(51, 65, 85);">• </canva-inline-text><strong data-html-import-id="html-import-149" data-template-id="strong-116" class="canva-text" style="color: rgb(51, 65, 85); font-weight: 700;">반대 방향 두 힘의 합력:</strong><canva-inline-text data-template-id="canva-inline-text-117" class="canva-text" style="color: rgb(51, 65, 85);"> 큰 힘에서 작은 힘을 빼고($|F_1 - F_2|$), 큰 힘의 방향을 따릅니다.</canva-inline-text></li>
                    <li data-html-import-id="html-import-150" data-template-id="li-118" class="canva-text" style="color: rgb(51, 65, 85);"><canva-inline-text data-template-id="canva-inline-text-119" class="canva-text" style="color: rgb(51, 65, 85);">• </canva-inline-text><strong data-html-import-id="html-import-151" data-template-id="strong-120" class="canva-text" style="color: rgb(51, 65, 85); font-weight: 700;">힘의 평형 조건:</strong><canva-inline-text data-template-id="canva-inline-text-121" class="canva-text" style="color: rgb(51, 65, 85);"> 두 힘의 </canva-inline-text><strong data-html-import-id="html-import-152" data-template-id="strong-122" class="canva-text" style="color: rgb(51, 65, 85); font-weight: 700;">크기가 같고</strong><canva-inline-text data-template-id="canva-inline-text-123" class="canva-text" style="color: rgb(51, 65, 85);">, </canva-inline-text><strong data-html-import-id="html-import-153" data-template-id="strong-124" class="canva-text" style="color: rgb(51, 65, 85); font-weight: 700;">방향이 서로 반대</strong><canva-inline-text data-template-id="canva-inline-text-125" class="canva-text" style="color: rgb(51, 65, 85);">이며, </canva-inline-text><strong data-html-import-id="html-import-154" data-template-id="strong-126" class="canva-text" style="color: rgb(51, 65, 85); font-weight: 700;">한 직선(같은 작용선)</strong><canva-inline-text data-template-id="canva-inline-text-127" class="canva-text" style="color: rgb(51, 65, 85);"> 위에서 한 물체에 작용할 때 합력이 $0\text{ N}$이 됩니다.</canva-inline-text></li>
                </ul>
            </div>

            <div class="flex items-center justify-center gap-3 pt-2" data-html-import-id="html-import-155">
                <button onclick="restartExam()" class="px-6 py-3 bg-indigo-600 hover:bg-indigo-700 text-white font-extrabold rounded-xl shadow transition text-sm canva-button" data-html-import-id="html-import-156" data-template-id="button-128" style="background: rgb(79, 70, 229); color: rgb(255, 255, 255); font-family: Pretendard; font-weight: 800; font-size: 14px;">
                    🔄 퀴즈 다시 풀기
                </button>
                <button onclick="switchMode('free')" class="px-6 py-3 bg-slate-100 hover:bg-slate-200 text-slate-700 font-bold rounded-xl transition text-sm canva-button" data-html-import-id="html-import-157" data-template-id="button-129" style="background: rgb(241, 245, 249); color: rgb(51, 65, 85); font-family: Pretendard; font-weight: 700; font-size: 14px;">
                    🔬 실험실로 돌아가기
                </button>
            </div>
        </div>
    </div>
</div>

<script data-html-import-id="html-import-158">
    // 시뮬레이션 상태 변수 정의
    const state = {
        mode: 'free',        // 'free' (자유 실험), 'quiz' (평형 맞추기), 'exam' (개념 문제 퀴즈)
        f1Mag: 20,           // 힘 1 크기 (0 ~ 50 N)
        f1Dir: -1,           // 힘 1 방향 (-1: 왼쪽, 1: 오른쪽)
        f2Mag: 30,           // 힘 2 크기 (0 ~ 50 N)
        f2Dir: 1,            // 힘 2 방향 (-1: 왼쪽, 1: 오른쪽)
        isPlaying: false,    // 출발 애니메이션 재생 여부
        boxXOffset: 0,       // 상자의 중앙 대비 수평 이동 거리 (px)
        boxVelocity: 0,      // 상자의 현재 속도
        wheelAngle: 0,       // 바퀴 회전 각도
        quizStreak: 0        // 미니게임 연속 정답 횟수
    };

    // ==========================================
    // 중1 과학 객관식 문제 퀴즈 데이터 (총 5문항)
    // ==========================================
    const examQuestions = [
        {
            category: "같은 방향의 두 힘의 합성",
            question: "수레에 오른쪽으로 15 N의 힘과 오른쪽으로 25 N의 힘이 동시에 작용하고 있습니다. 이 수레에 작용하는 합력(알짜힘)의 크기와 방향은?",
            diagram: { f1Mag: 15, f1Dir: 1, f2Mag: 25, f2Dir: 1 },
            options: [
                "오른쪽으로 10 N",
                "왼쪽으로 10 N",
                "오른쪽으로 40 N",
                "왼쪽으로 40 N"
            ],
            correctIndex: 2,
            explanation: "한 물체에 같은 방향으로 나란하게 작용하는 두 힘의 합력의 크기는 두 힘을 더한 값(15 N + 25 N = 40 N)이고, 방향은 두 힘의 방향과 같은 오른쪽입니다."
        },
        {
            category: "반대 방향의 두 힘의 합성",
            question: "줄다리기 시합에서 왼쪽 팀이 45 N의 힘으로 당기고, 오른쪽 팀이 30 N의 힘으로 당기고 있습니다. 줄에 작용하는 합력의 크기와 이동 방향은?",
            diagram: { f1Mag: 45, f1Dir: -1, f2Mag: 30, f2Dir: 1 },
            options: [
                "왼쪽으로 15 N",
                "오른쪽으로 15 N",
                "왼쪽으로 75 N",
                "힘의 평형 (0 N)"
            ],
            correctIndex: 0,
            explanation: "반대 방향으로 작용하는 두 힘의 합력은 큰 힘에서 작은 힘을 뺀 값(45 N - 30 N = 15 N)이며, 방향은 더 큰 힘이 작용한 왼쪽입니다."
        },
        {
            category: "힘의 평형과 합력",
            question: "바닥에 놓인 상자를 민수가 오른쪽으로 35 N의 힘으로 밀었더니 상자가 움직이지 않고 힘의 평형을 이루었습니다. 이때 반대쪽에서 지영이가 상자를 민 힘은?",
            diagram: { f1Mag: 35, f1Dir: 1, f2Mag: 35, f2Dir: -1, hideF2Label: true },
            options: [
                "오른쪽으로 35 N",
                "왼쪽으로 35 N",
                "왼쪽으로 70 N",
                "힘을 전혀 주지 않았다 (0 N)"
            ],
            correctIndex: 1,
            explanation: "두 힘이 평형을 이루려면(합력 = 0 N) 두 힘의 크기가 같고 방향이 서로 반대여야 합니다. 민수가 오른쪽으로 35 N을 주었으므로 지영이는 왼쪽으로 35 N의 힘을 주어야 합니다."
        },
        {
            category: "합력을 이용한 미지의 힘 구하기",
            question: "상자에 왼쪽으로 20 N의 힘(F₁)과 오른쪽으로 어떤 힘(F₂)이 동시에 작용했더니, 최종 합력이 '오른쪽으로 15 N'이 되었습니다. 오른쪽으로 작용한 힘(F₂)의 크기는?",
            diagram: { f1Mag: 20, f1Dir: -1, f2Mag: 35, f2Dir: 1, hideF2Label: true },
            options: [
                "5 N",
                "15 N",
                "30 N",
                "35 N"
            ],
            correctIndex: 3,
            explanation: "반대 방향의 두 힘에서 합력이 오른쪽으로 15 N이 나왔으므로 오른쪽 힘(F₂)이 왼쪽 힘(20 N)보다 15 N 더 커야 합니다. 따라서 F₂ = 20 N + 15 N = 35 N입니다."
        },
        {
            category: "두 힘의 합력의 최대·최소 범위",
            question: "크기가 각각 20 N과 30 N인 두 힘이 한 물체에 동시에 작용할 때, 만들어질 수 있는 합력의 크기로 알맞게 짝지어진 것은? (단, 두 힘은 나란하게 작용한다.)",
            diagram: { f1Mag: 20, f1Dir: 1, f2Mag: 30, f2Dir: 1 },
            options: [
                "최소 0 N, 최대 30 N",
                "최소 10 N, 최대 50 N",
                "최소 20 N, 최대 30 N",
                "최소 10 N, 최대 60 N"
            ],
            correctIndex: 1,
            explanation: "두 힘이 반대 방향일 때 합력이 최소(30 N - 20 N = 10 N)가 되고, 같은 방향일 때 합력이 최대(20 N + 30 N = 50 N)가 됩니다."
        }
    ];

    const examState = {
        currentIndex: 0,
        score: 0,
        answered: false
    };

    const canvas = document.getElementById('simCanvas');
    const ctx = canvas.getContext('2d');

    // 1 N 당 화살표 픽셀 스케일 (모눈 1칸 = 25px = 5N -> 1N = 5px)
    const PIXELS_PER_NEWTON = 5;

    // 캔버스 해상도 리사이징 처리
    function resizeCanvas() {
        const rect = canvas.parentElement.getBoundingClientRect();
        if (rect.width === 0) return;
        const dpr = window.devicePixelRatio || 1;
        canvas.width = rect.width * dpr;
        canvas.height = rect.height * dpr;
        ctx.setTransform(dpr, 0, 0, dpr, 0, 0);
    }

    window.addEventListener('resize', resizeCanvas);

    // 방향 버튼 스타일 및 상태 업데이트
    function setDirection(forceNum, dir) {
        if (state.mode === 'quiz' && forceNum === 1) return; // 퀴즈 모드에서는 F1 변경 불가

        if (forceNum === 1) {
            state.f1Dir = dir;
        } else {
            state.f2Dir = dir;
        }
        resetBoxPosition();
        updateUI();
    }

    // 슬라이더 조작 시 상태 반영
    function updateForceFromUI() {
        if (state.mode !== 'quiz') {
            state.f1Mag = parseInt(document.getElementById('f1Slider').value, 10);
        }
        state.f2Mag = parseInt(document.getElementById('f2Slider').value, 10);
        resetBoxPosition();
        updateUI();
    }

    // 모눈 격자 배경 토글
    function toggleGrid() {
        const viewport = document.getElementById('simViewport');
        const isChecked = document.getElementById('gridToggle').checked;
        if (isChecked) {
            viewport.classList.add('grid-bg');
        } else {
            viewport.classList.remove('grid-bg');
        }
    }

    // 합력(알짜힘) 계산 함수
    function getNetForce() {
        const f1Vector = state.f1Mag * state.f1Dir;
        const f2Vector = state.f2Mag * state.f2Dir;
        const netVector = f1Vector + f2Vector;
        return {
            f1Vector,
            f2Vector,
            netVector,
            netMag: Math.abs(netVector),
            netDir: netVector > 0 ? 1 : (netVector < 0 ? -1 : 0)
        };
    }

    // 전체 UI 텍스트, 버튼 활성화, 실시간 해설 업데이트
    function updateUI() {
        const { netMag, netDir } = getNetForce();

        // 수치 텍스트 반영
        document.getElementById('f1ValueText').textContent = `${state.f1Mag} N`;
        document.getElementById('f2ValueText').textContent = `${state.f2Mag} N`;
        document.getElementById('f1Slider').value = state.f1Mag;
        document.getElementById('f2Slider').value = state.f2Mag;

        // 방향 토글 버튼 활성화 스타일 업데이트
        const activeBlue = "bg-blue-600 text-white border-blue-600 shadow-sm";
        const inactiveBtn = "bg-slate-50 text-slate-600 border-slate-200 hover:bg-slate-100";
        const activeOrange = "bg-orange-600 text-white border-orange-600 shadow-sm";

        document.getElementById('f1DirLeft').className = `py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 ${state.f1Dir === -1 ? activeBlue : inactiveBtn}`;
        document.getElementById('f1DirRight').className = `py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 ${state.f1Dir === 1 ? activeBlue : inactiveBtn}`;

        document.getElementById('f2DirLeft').className = `py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 ${state.f2Dir === -1 ? activeOrange : inactiveBtn}`;
        document.getElementById('f2DirRight').className = `py-2.5 px-3 rounded-xl font-bold text-sm border-2 transition flex items-center justify-center gap-1 ${state.f2Dir === 1 ? activeOrange : inactiveBtn}`;

        // 상단 합력 뱃지 및 학습 해설 카드 업데이트
        const badge = document.getElementById('netForceBadge');
        const feedbackCard = document.getElementById('feedbackCard');
        const situationTag = document.getElementById('situationTag');
        const feedbackTitle = document.getElementById('feedbackTitle');
        const feedbackDesc = document.getElementById('feedbackDesc');
        const formulaBox = document.getElementById('formulaBox');

        const dirText = netDir === 1 ? '오른쪽 ▶' : '◀ 왼쪽';

        if (netMag === 0) {
            // 힘의 평형 상태
            badge.className = "badge-float px-5 py-2 rounded-full font-extrabold text-sm sm:text-base shadow-md transition-all duration-300 flex items-center gap-2 bg-emerald-600 text-white equilibrium-glow";
            badge.innerHTML = `<span>⚖️ 힘의 평형! (합력 = 0 N)</span>`;

            feedbackCard.className = "bg-emerald-50/70 rounded-2xl shadow-sm border-2 border-emerald-400 p-5 flex flex-col justify-between transition-all duration-300 equilibrium-glow";
            situationTag.textContent = "힘의 평형 상태";
            situationTag.className = "text-xs font-extrabold text-emerald-700 bg-emerald-100 px-2.5 py-0.5 rounded-full";
            feedbackTitle.textContent = "합력이 0 N입니다! (힘의 평형)";
            if (state.f1Mag === 0 && state.f2Mag === 0) {
                feedbackDesc.innerHTML = "작용하는 힘이 없으므로 합력이 <strong>0 N</strong>이며 물체는 정지 상태를 유지합니다.";
                formulaBox.textContent = "합력 = 0 N";
            } else {
                feedbackDesc.innerHTML = "두 힘의 <strong>크기가 같고 방향이 서로 반대</strong>여서 힘이 상쇄되었습니다. 정지해 있던 물체는 계속 정지해 있습니다!";
                formulaBox.textContent = `합력 = ${state.f1Mag} N - ${state.f2Mag} N = 0 N (정지)`;
            }
        } else if (state.f1Dir === state.f2Dir || state.f1Mag === 0 || state.f2Mag === 0) {
            // 같은 방향
            badge.className = "badge-float px-5 py-2 rounded-full font-extrabold text-sm sm:text-base shadow-md transition-all duration-300 flex items-center gap-2 bg-rose-600 text-white";
            badge.innerHTML = `<span>합력: ${dirText} ${netMag} N</span>`;

            feedbackCard.className = "bg-white rounded-2xl shadow-sm border-2 border-slate-200 p-5 flex flex-col justify-between transition-all duration-300";
            situationTag.textContent = "같은 방향의 두 힘";
            situationTag.className = "text-xs font-bold text-blue-700 bg-blue-50 px-2.5 py-0.5 rounded-full";
            feedbackTitle.textContent = "두 힘이 같은 방향으로 작용해요!";
            feedbackDesc.innerHTML = "나란하게 같은 방향으로 작용하는 두 힘의 합력은 <strong>두 힘의 크기를 더한 값</strong>과 같고, 방향은 두 힘의 방향과 같습니다.";
            formulaBox.textContent = `합력 = ${state.f1Mag} N + ${state.f2Mag} N = ${netMag} N (${netDir === 1 ? '오른쪽' : '왼쪽'})`;
        } else {
            // 반대 방향 (평형이 아닐 때)
            badge.className = "badge-float px-5 py-2 rounded-full font-extrabold text-sm sm:text-base shadow-md transition-all duration-300 flex items-center gap-2 bg-rose-600 text-white";
            badge.innerHTML = `<span>합력: ${dirText} ${netMag} N</span>`;

            feedbackCard.className = "bg-white rounded-2xl shadow-sm border-2 border-slate-200 p-5 flex flex-col justify-between transition-all duration-300";
            situationTag.textContent = "반대 방향의 두 힘";
            situationTag.className = "text-xs font-bold text-orange-700 bg-orange-50 px-2.5 py-0.5 rounded-full";
            feedbackTitle.textContent = "두 힘이 반대 방향으로 작용해요!";
            feedbackDesc.innerHTML = "서로 반대 방향으로 작용할 때의 합력은 <strong>큰 힘에서 작은 힘을 뺀 값</strong>과 같고, 방향은 <strong>더 큰 힘의 방향</strong>을 따릅니다.";
            const maxF = Math.max(state.f1Mag, state.f2Mag);
            const minF = Math.min(state.f1Mag, state.f2Mag);
            formulaBox.textContent = `합력 = ${maxF} N - ${minF} N = ${netMag} N (${netDir === 1 ? '오른쪽' : '왼쪽'})`;
        }
    }

    // 출발 / 일시정지 토글
    function togglePlay() {
        state.isPlaying = !state.isPlaying;
        updatePlayButtonUI();
    }

    function updatePlayButtonUI() {
        const playBtn = document.getElementById('playBtn');
        const playIcon = document.getElementById('playIcon');
        const playText = document.getElementById('playText');

        if (state.isPlaying) {
            playBtn.className = "px-5 py-2 rounded-xl font-extrabold text-sm bg-amber-500 hover:bg-amber-600 text-white shadow transition flex items-center gap-1.5";
            playIcon.textContent = "⏸";
            playText.textContent = "일시정지";
        } else {
            playBtn.className = "px-5 py-2 rounded-xl font-extrabold text-sm bg-indigo-600 hover:bg-indigo-700 text-white shadow transition flex items-center gap-1.5";
            playIcon.textContent = "▶";
            playText.textContent = "출발 (움직임 관찰)";
        }
    }

    // 상자 원위치 리셋
    function resetBoxPosition() {
        state.isPlaying = false;
        state.boxXOffset = 0;
        state.boxVelocity = 0;
        updatePlayButtonUI();
    }

    // 모드 전환 (자유 실험 / 평형 맞추기 / 개념 문제 퀴즈)
    function switchMode(mode) {
        state.mode = mode;
        const tabFree = document.getElementById('tabFree');
        const tabQuiz = document.getElementById('tabQuiz');
        const tabExam = document.getElementById('tabExam');

        const simulationSection = document.getElementById('simulationSection');
        const examSection = document.getElementById('examSection');

        const quizBanner = document.getElementById('quizBanner');
        const f1Slider = document.getElementById('f1Slider');
        const f1LockBadge = document.getElementById('f1LockBadge');
        const f1Card = document.getElementById('f1Card');

        const inactiveTabClass = "flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all text-slate-600 hover:text-slate-900 whitespace-nowrap";

        tabFree.className = inactiveTabClass;
        tabQuiz.className = inactiveTabClass;
        tabExam.className = inactiveTabClass;

        if (mode === 'exam') {
            tabExam.className = "flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all bg-white text-indigo-600 shadow-sm whitespace-nowrap";
            simulationSection.classList.add('hidden');
            examSection.classList.remove('hidden');
            resetBoxPosition();
            renderExamQuestion();
        } else if (mode === 'quiz') {
            tabQuiz.className = "flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all bg-white text-emerald-600 shadow-sm whitespace-nowrap";
            examSection.classList.add('hidden');
            simulationSection.classList.remove('hidden');
            quizBanner.classList.remove('hidden');
            f1Slider.disabled = true;
            f1LockBadge.classList.remove('hidden');
            f1Card.classList.add('bg-slate-50/80');
            resizeCanvas();
            generateNewQuiz();
        } else {
            tabFree.className = "flex-1 md:flex-initial px-3.5 py-2 rounded-lg text-xs sm:text-sm font-bold transition-all bg-white text-indigo-600 shadow-sm whitespace-nowrap";
            examSection.classList.add('hidden');
            simulationSection.classList.remove('hidden');
            quizBanner.classList.add('hidden');
            f1Slider.disabled = false;
            f1LockBadge.classList.add('hidden');
            f1Card.classList.remove('bg-slate-50/80');
            hideQuizToast();
            resizeCanvas();
            resetBoxPosition();
            updateUI();
        }
    }

    // 미니게임 새 문제 출제
    function generateNewQuiz() {
        hideQuizToast();
        const randomMag = (Math.floor(Math.random() * 10) + 1) * 5;
        const randomDir = Math.random() < 0.5 ? -1 : 1;

        state.f1Mag = randomMag;
        state.f1Dir = randomDir;

        state.f2Mag = 10;
        state.f2Dir = randomDir;

        const dirKor = randomDir === 1 ? '오른쪽' : '왼쪽';
        document.getElementById('quizMissionText').innerHTML = 
            `미션: 상자에 <strong>${dirKor}으로 ${randomMag} N</strong>의 힘(F₁)이 작용 중입니다. F₂를 조절해 <strong>힘의 평형(0 N)</strong>을 만드세요!`;

        resetBoxPosition();
        updateUI();
    }

    // 미니게임 정답 확인
    function checkQuizAnswer() {
        const { netMag } = getNetForce();
        const toast = document.getElementById('quizToast');
        toast.classList.remove('hidden');

        if (netMag === 0) {
            state.quizStreak++;
            document.getElementById('quizScoreBadge').textContent = `연속 성공: ${state.quizStreak}회`;
            toast.className = "absolute top-16 left-1/2 -translate-x-1/2 z-20 px-5 py-2.5 rounded-xl font-extrabold text-sm shadow-lg bg-emerald-600 text-white";
            toast.textContent = "🎉 정답입니다! 크기 같고 방향 반대인 힘으로 완벽한 평형을 만들었어요!";
            state.isPlaying = true;
            updatePlayButtonUI();
        } else {
            state.quizStreak = 0;
            document.getElementById('quizScoreBadge').textContent = `연속 성공: 0회`;
            toast.className = "absolute top-16 left-1/2 -translate-x-1/2 z-20 px-5 py-2.5 rounded-xl font-extrabold text-sm shadow-lg bg-rose-600 text-white";
            toast.textContent = `❗ 아직 합력이 ${netMag} N 남아있어요! 상자가 움직입니다. 힘의 크기와 방향을 다시 확인해 보세요!`;
            state.isPlaying = true;
            updatePlayButtonUI();
        }
    }

    function hideQuizToast() {
        document.getElementById('quizToast').classList.add('hidden');
    }

    // ==========================================
    // 개념 문제 퀴즈 (Exam) 로직
    // ==========================================
    function renderExamQuestion() {
        const total = examQuestions.length;
        const currentQ = examQuestions[examState.currentIndex];
        examState.answered = false;

        document.getElementById('examQuestionCard').classList.remove('hidden');
        document.getElementById('examResultCard').classList.add('hidden');
        document.getElementById('qExplanationBox').classList.add('hidden');

        // 상단 진행도 업데이트
        document.getElementById('examScoreBadge').textContent = `현재 점수: ${examState.score} / ${total}`;
        document.getElementById('examProgressText').textContent = `문제 ${examState.currentIndex + 1} / ${total}`;
        document.getElementById('examProgressBar').style.width = `${((examState.currentIndex + 1) / total) * 100}%`;

        // 문제 텍스트 업데이트
        document.getElementById('qNumberBadge').textContent = `Q${examState.currentIndex + 1}`;
        document.getElementById('qCategoryText').textContent = currentQ.category;
        document.getElementById('qTitleText').textContent = currentQ.question;

        // 모식도 그리기
        drawQuizDiagram(currentQ.diagram);

        // 보기 버튼 생성
        const optionsGrid = document.getElementById('qOptionsGrid');
        optionsGrid.innerHTML = '';

        currentQ.options.forEach((optText, idx) => {
            const btn = document.createElement('button');
            btn.className = "w-full text-left p-4 rounded-xl border-2 border-slate-200 hover:border-indigo-400 hover:bg-indigo-50/40 font-bold text-slate-800 transition flex items-center gap-3";
            btn.innerHTML = `
                <span class="w-7 h-7 rounded-lg bg-slate-100 text-slate-700 font-extrabold text-sm flex items-center justify-center shrink-0">${idx + 1}</span>
                <span class="text-base">${optText}</span>
            `;
            btn.onclick = () => selectExamOption(idx);
            optionsGrid.appendChild(btn);
        });
    }

    function selectExamOption(selectedIndex) {
        if (examState.answered) return;
        examState.answered = true;

        const currentQ = examQuestions[examState.currentIndex];
        const isCorrect = selectedIndex === currentQ.correctIndex;
        if (isCorrect) {
            examState.score++;
        }

        document.getElementById('examScoreBadge').textContent = `현재 점수: ${examState.score} / ${examQuestions.length}`;

        // 보기 버튼 색상 피드백
        const buttons = document.getElementById('qOptionsGrid').children;
        for (let i = 0; i < buttons.length; i++) {
            const btn = buttons[i];
            btn.disabled = true;
            if (i === currentQ.correctIndex) {
                btn.className = "w-full text-left p-4 rounded-xl border-2 border-emerald-500 bg-emerald-50 font-extrabold text-emerald-900 transition flex items-center justify-between gap-3";
                btn.innerHTML += `<span class="text-emerald-600 text-xs font-extrabold px-2 py-0.5 bg-emerald-100 rounded-full shrink-0">정답 O</span>`;
            } else if (i === selectedIndex && !isCorrect) {
                btn.className = "w-full text-left p-4 rounded-xl border-2 border-rose-400 bg-rose-50 font-bold text-rose-900 transition flex items-center justify-between gap-3";
                btn.innerHTML += `<span class="text-rose-600 text-xs font-extrabold px-2 py-0.5 bg-rose-100 rounded-full shrink-0">선택 X</span>`;
            } else {
                btn.className = "w-full text-left p-4 rounded-xl border-2 border-slate-100 bg-slate-50/50 text-slate-400 font-semibold transition flex items-center gap-3 opacity-60";
            }
        }

        // 해설 박스 표시
        const expBox = document.getElementById('qExplanationBox');
        const headline = document.getElementById('qResultHeadline');
        const expText = document.getElementById('qExplanationText');
        const nextBtn = document.getElementById('nextQuestionBtn');

        expBox.classList.remove('hidden');
        if (isCorrect) {
            expBox.className = "rounded-2xl p-5 border-2 border-emerald-300 bg-emerald-50/70 transition-all";
            headline.className = "text-base font-extrabold text-emerald-700 flex items-center gap-2";
            headline.innerHTML = `<span>🎉 정답입니다! 정확하게 이해하고 있네요.</span>`;
        } else {
            expBox.className = "rounded-2xl p-5 border-2 border-rose-300 bg-rose-50/70 transition-all";
            headline.className = "text-base font-extrabold text-rose-700 flex items-center gap-2";
            headline.innerHTML = `<span>💡 아쉽네요! 아래 해설을 읽고 원리를 확인해 보세요.</span>`;
        }

        expText.textContent = currentQ.explanation;
        nextBtn.textContent = (examState.currentIndex === examQuestions.length - 1) ? "결과 보기 🏆" : "다음 문제 ▶";
    }

    function nextExamQuestion() {
        if (examState.currentIndex < examQuestions.length - 1) {
            examState.currentIndex++;
            renderExamQuestion();
        } else {
            showExamResults();
        }
    }

    function showExamResults() {
        document.getElementById('examQuestionCard').classList.add('hidden');
        const resultCard = document.getElementById('examResultCard');
        resultCard.classList.remove('hidden');

        const total = examQuestions.length;
        const score = examState.score;

        const emoji = document.getElementById('resultEmoji');
        const title = document.getElementById('resultTitle');
        const summary = document.getElementById('resultSummary');

        if (score === total) {
            emoji.textContent = "🏆";
            title.textContent = "완벽해요! 만점을 달성했습니다!";
        } else if (score >= 3) {
            emoji.textContent = "🎉";
            title.textContent = "잘했어요! 힘의 합성 원리를 잘 알고 있네요.";
        } else {
            emoji.textContent = "💪";
            title.textContent = "조금만 더 연습해 볼까요?";
        }

        summary.innerHTML = `총 ${total}문제 중 <strong class="text-indigo-600 font-extrabold">${score}문제</strong>를 맞혔습니다!`;
    }

    function restartExam() {
        examState.currentIndex = 0;
        examState.score = 0;
        examState.answered = false;
        renderExamQuestion();
    }

    // 문제 모식도 전용 미니 캔버스 렌더링
    function drawQuizDiagram(diagram) {
        const dCanvas = document.getElementById('quizDiagramCanvas');
        const dCtx = dCanvas.getContext('2d');
        const w = dCanvas.width;
        const h = dCanvas.height;
        const cx = w / 2;
        const cy = h / 2 + 12;

        dCtx.clearRect(0, 0, w, h);

        // 바닥 선
        dCtx.strokeStyle = '#cbd5e1';
        dCtx.lineWidth = 3;
        dCtx.beginPath();
        dCtx.moveTo(40, cy + 32);
        dCtx.lineTo(w - 40, cy + 32);
        dCtx.stroke();

        // 미니 상자
        const boxW = 64;
        const boxH = 50;
        dCtx.fillStyle = '#f59e0b';
        dCtx.strokeStyle = '#b45309';
        dCtx.lineWidth = 3;
        dCtx.beginPath();
        dCtx.roundRect(cx - boxW / 2, cy - boxH / 2, boxW, boxH, 8);
        dCtx.fill();
        dCtx.stroke();

        // 화살표 그리기 내부 함수
        function drawMiniArrow(yPos, mag, dir, color, label) {
            const len = Math.min(mag * 3.5, 160);
            const startX = cx + (dir * 34);
            const endX = startX + (dir * len);

            dCtx.save();
            dCtx.strokeStyle = color;
            dCtx.fillStyle = color;
            dCtx.lineWidth = 5;
            dCtx.lineCap = 'round';

            dCtx.beginPath();
            dCtx.moveTo(startX, yPos);
            dCtx.lineTo(endX - dir * 5, yPos);
            dCtx.stroke();

            dCtx.beginPath();
            dCtx.moveTo(endX, yPos);
            dCtx.lineTo(endX - dir * 11, yPos - 7);
            dCtx.lineTo(endX - dir * 11, yPos + 7);
            dCtx.closePath();
            dCtx.fill();

            dCtx.font = '800 12px Pretendard, sans-serif';
            dCtx.textAlign = 'center';
            dCtx.fillText(label, (startX + endX) / 2, yPos - 12);
            dCtx.restore();
        }

        drawMiniArrow(cy - 10, diagram.f1Mag, diagram.f1Dir, '#2563eb', `F₁ = ${diagram.f1Mag} N`);
        const f2Label = diagram.hideF2Label ? 'F₂ = ? N' : `F₂ = ${diagram.f2Mag} N`;
        drawMiniArrow(cy + 14, diagram.f2Mag, diagram.f2Dir, '#ea580c', f2Label);
    }

    // 캔버스 화살표 그리기 헬퍼 함수
    function drawForceArrow(ctx, startX, startY, magnitude, direction, color, labelPrefix) {
        if (magnitude === 0) return;

        const length = magnitude * PIXELS_PER_NEWTON;
        const endX = startX + length * direction;
        const headLength = 14;

        ctx.save();
        ctx.strokeStyle = color;
        ctx.fillStyle = color;
        ctx.lineWidth = 7;
        ctx.lineCap = 'round';

        // 화살표 몸통 선
        ctx.beginPath();
        ctx.moveTo(startX, startY);
        ctx.lineTo(endX - (direction * 6), startY);
        ctx.stroke();

        // 화살촉 삼각형
        ctx.beginPath();
        ctx.moveTo(endX, startY);
        ctx.lineTo(endX - direction * headLength, startY - 9);
        ctx.lineTo(endX - direction * headLength, startY + 9);
        ctx.closePath();
        ctx.fill();

        // 화살표 시작점 원형 포인트
        ctx.beginPath();
        ctx.arc(startX, startY, 5, 0, Math.PI * 2);
        ctx.fillStyle = '#ffffff';
        ctx.fill();
        ctx.lineWidth = 3;
        ctx.stroke();

        // 화살표 수치 라벨 캡슐
        const labelText = `${labelPrefix}: ${magnitude} N`;
        ctx.font = '800 13px Pretendard, sans-serif';
        const textWidth = ctx.measureText(labelText).width;
        const midX = startX + (length * direction) / 2;
        const pillWidth = textWidth + 16;
        const pillHeight = 24;
        const pillY = startY - 28;

        ctx.fillStyle = color;
        ctx.beginPath();
        ctx.roundRect(midX - pillWidth / 2, pillY, pillWidth, pillHeight, 8);
        ctx.fill();

        ctx.fillStyle = '#ffffff';
        ctx.textAlign = 'center';
        ctx.textBaseline = 'middle';
        ctx.fillText(labelText, midX, pillY + pillHeight / 2);

        ctx.restore();
    }

    // 귀여운 나무 수레(상자) 그리기 함수
    function drawWoodenCart(ctx, centerX, groundY, isEquilibrium, netMag) {
        const boxW = 96;
        const boxH = 74;
        const wheelRadius = 12;
        const boxX = centerX - boxW / 2;
        const boxY = groundY - boxH - wheelRadius * 1.5;

        ctx.save();

        // 힘의 평형일 때 초록빛 오라 표시
        if (isEquilibrium) {
            ctx.shadowColor = 'rgba(16, 185, 129, 0.6)';
            ctx.shadowBlur = 22;
        } else {
            ctx.shadowColor = 'rgba(15, 23, 42, 0.15)';
            ctx.shadowBlur = 12;
            ctx.shadowOffsetY = 4;
        }

        // 상자 본체
        ctx.fillStyle = '#d97706';
        ctx.strokeStyle = isEquilibrium ? '#10b981' : '#92400e';
        ctx.lineWidth = isEquilibrium ? 4 : 3;
        ctx.beginPath();
        ctx.roundRect(boxX, boxY, boxW, boxH, 12);
        ctx.fill();
        ctx.stroke();

        ctx.shadowBlur = 0;
        ctx.shadowOffsetY = 0;

        // 나무 판자 디테일 무늬
        ctx.fillStyle = '#f59e0b';
        ctx.beginPath();
        ctx.roundRect(boxX + 8, boxY + 8, boxW - 16, boxH - 16, 8);
        ctx.fill();

        // 상자 귀여운 표정 그리기
        ctx.fillStyle = '#451a03';
        const eyeY = boxY + 32;
        ctx.beginPath();
        ctx.arc(centerX - 16, eyeY, 4.5, 0, Math.PI * 2);
        ctx.arc(centerX + 16, eyeY, 4.5, 0, Math.PI * 2);
        ctx.fill();

        // 입 모양
        ctx.lineWidth = 3;
        ctx.strokeStyle = '#451a03';
        ctx.beginPath();
        if (isEquilibrium) {
            ctx.arc(centerX, eyeY + 6, 9, 0.15 * Math.PI, 0.85 * Math.PI);
            ctx.stroke();
        } else if (netMag > 0 && state.isPlaying) {
            ctx.arc(centerX, eyeY + 10, 5, 0, Math.PI * 2);
            ctx.stroke();
        } else {
            ctx.moveTo(centerX - 7, eyeY + 11);
            ctx.lineTo(centerX + 7, eyeY + 11);
            ctx.stroke();
        }

        // 바퀴 2개 그리기
        const wheelPositions = [centerX - 26, centerX + 26];
        wheelPositions.forEach(wx => {
            const wy = groundY - wheelRadius;
            ctx.save();
            ctx.translate(wx, wy);
            ctx.rotate(state.wheelAngle);

            ctx.fillStyle = '#334155';
            ctx.beginPath();
            ctx.arc(0, 0, wheelRadius, 0, Math.PI * 2);
            ctx.fill();

            ctx.strokeStyle = '#cbd5e1';
            ctx.lineWidth = 2.5;
            ctx.beginPath();
            ctx.moveTo(-wheelRadius + 3, 0);
            ctx.lineTo(wheelRadius - 3, 0);
            ctx.moveTo(0, -wheelRadius + 3);
            ctx.lineTo(0, wheelRadius - 3);
            ctx.stroke();

            ctx.fillStyle = '#94a3b8';
            ctx.beginPath();
            ctx.arc(0, 0, 4, 0, Math.PI * 2);
            ctx.fill();
            ctx.restore();
        });

        ctx.restore();
        return { boxCenterY: boxY + boxH / 2, boxTopY: boxY };
    }

    // 메인 애니메이션 루프
    function animate() {
        if (state.mode !== 'exam') {
            const width = canvas.clientWidth;
            const height = canvas.clientHeight;
            ctx.clearRect(0, 0, width, height);

            const { netVector, netMag, netDir } = getNetForce();
            const isEquilibrium = netMag === 0;

            if (state.isPlaying) {
                if (netMag > 0) {
                    const accel = netVector * 0.004;
                    state.boxVelocity += accel;
                    state.boxXOffset += state.boxVelocity;
                    state.wheelAngle += state.boxVelocity * 0.05;

                    const maxOffset = width / 2 - 80;
                    if (state.boxXOffset > maxOffset) {
                        state.boxXOffset = maxOffset;
                        state.boxVelocity = 0;
                        state.isPlaying = false;
                        updatePlayButtonUI();
                    } else if (state.boxXOffset < -maxOffset) {
                        state.boxXOffset = -maxOffset;
                        state.boxVelocity = 0;
                        state.isPlaying = false;
                        updatePlayButtonUI();
                    }
                } else {
                    state.boxVelocity = 0;
                }
            }

            const groundY = height - 68;
            const centerX = width / 2 + state.boxXOffset;

            // 1. 기준선(중앙 원점 표시선)
            ctx.save();
            ctx.strokeStyle = 'rgba(148, 163, 184, 0.6)';
            ctx.setLineDash([5, 5]);
            ctx.lineWidth = 1.5;
            ctx.beginPath();
            ctx.moveTo(width / 2, 50);
            ctx.lineTo(width / 2, groundY);
            ctx.stroke();
            ctx.fillStyle = '#94a3b8';
            ctx.font = '700 11px Pretendard, sans-serif';
            ctx.textAlign = 'center';
            ctx.fillText('기준점 (0)', width / 2, groundY + 18);
            ctx.restore();

            // 2. 바닥 트랙 선 그리기
            ctx.save();
            ctx.strokeStyle = '#64748b';
            ctx.lineWidth = 4;
            ctx.beginPath();
            ctx.moveTo(20, groundY);
            ctx.lineTo(width - 20, groundY);
            ctx.stroke();
            ctx.restore();

            // 3. 나무 수레(상자) 그리기
            const { boxCenterY, boxTopY } = drawWoodenCart(ctx, centerX, groundY, isEquilibrium, netMag);

            // 4. 힘 1 및 힘 2 화살표 그리기
            drawForceArrow(ctx, centerX, boxCenterY - 12, state.f1Mag, state.f1Dir, '#2563eb', 'F₁');
            drawForceArrow(ctx, centerX, boxCenterY + 18, state.f2Mag, state.f2Dir, '#ea580c', 'F₂');

            // 5. 상단 합력 화살표 그리기
            const netArrowY = boxTopY - 38;
            if (netMag > 0) {
                drawForceArrow(ctx, centerX, netArrowY, netMag, netDir, '#e11d48', '합력');
            } else {
                ctx.save();
                ctx.fillStyle = '#059669';
                ctx.font = '800 13px Pretendard, sans-serif';
                ctx.textAlign = 'center';
                ctx.fillText('✨ 알짜힘 0 N (힘의 평형)', centerX, netArrowY);
                ctx.restore();
            }
        }

        requestAnimationFrame(animate);
    }

    // 초기 실행
    window.onload = function () {
        resizeCanvas();
        updateUI();
        animate();
    };
</script>

<script src="/_sdk/258b5de2ce998246.editing_sdk.js" integrity="sha512-7Dim6BG+4D+CHmb/Jnkrbx3kVronaRNOJ6e2RHGNPKP38LS3G9me5bcy7vclqda3mPtv9Sg7ZQujXKhsSy016Q=="></script></body></html>
