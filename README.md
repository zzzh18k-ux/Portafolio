<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex.VFX | Video Editor & Content Creator</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- Google Fonts: Montserrat -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- FontAwesome para iconos profesionales -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background-color: #0b0f19;
            color: #f3f4f6;
        }
        .gold-gradient {
            background: linear-gradient(135deg, #f59e0b 0%, #d97706 50%, #b45309 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .gold-glow:hover {
            box-shadow: 0 0 25px rgba(245, 158, 11, 0.25);
        }
    </style>
</head>
<body class="bg-[#0b0f19] text-gray-100 selection:bg-amber-500 selection:text-black min-h-screen pb-16">

    <div class="max-w-2xl mx-auto px-4 pt-10">
        
        <!-- Tarjeta de Perfil Estilo Red Social (Todo arriba) -->
        <div class="bg-gray-900/80 border border-gray-800 rounded-3xl p-6 sm:p-8 text-center backdrop-blur-md shadow-2xl relative overflow-hidden mb-10">
            <!-- Fondo sutil decorativo -->
            <div class="absolute -top-24 left-1/2 -translate-x-1/2 w-64 h-64 bg-amber-500/10 rounded-full blur-3xl pointer-events-none"></div>

            <!-- Avatar del Creador (Aquí está tu archivo local 23161avatar.png) -->
            <div class="relative w-28 h-28 sm:w-32 sm:h-32 mx-auto mb-5 rounded-full p-1 bg-gradient-to-tr from-amber-500 to-amber-300 shadow-xl">
                <img src="23161avatar.png" alt="Alex.VFX" class="w-full h-full object-cover rounded-full bg-gray-950">
            </div>

            <!-- Nombre y Eslogan -->
            <h1 class="text-2xl sm:text-3xl font-extrabold text-white flex items-center justify-center gap-2">
                Alex.VFX <i class="fa-solid fa-circle-check text-amber-400 text-lg"></i>
            </h1>
            <p class="text-sm sm:text-base text-amber-400/90 font-medium mt-1 mb-4 flex items-center justify-center gap-2">
                <i class="fa-solid fa-clapperboard"></i> Video Editor & Content Creator
            </p>
            <p class="text-xs sm:text-sm text-gray-400 max-w-md mx-auto mb-6 leading-relaxed">
                Transformando ideas en historias visuales de alto impacto. Especialista en Premiere Pro, After Effects y DaVinci Resolve.
            </p>

            <!-- Botones de Acción / Enlaces Principales Arriba -->
            <div class="flex flex-col gap-3 mb-8">
                <!-- WhatsApp Directo -->
                <a href="https://wa.me/tu_numero_aqui" target="_blank" class="w-full py-3.5 px-6 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white font-bold transition-all flex items-center justify-center gap-3 shadow-lg shadow-emerald-600/20 text-sm">
                    <i class="fa-brands fa-whatsapp text-lg"></i> Escríbeme al WhatsApp
                </a>
                <!-- Correo -->
                <a href="mailto:contacto@alexvfx.com" class="w-full py-3 px-6 rounded-xl bg-gray-800/80 hover:bg-gray-800 border border-gray-700/60 text-gray-200 font-semibold transition-all flex items-center justify-center gap-2 text-sm">
                    <i class="fa-regular fa-envelope text-amber-400"></i> contacto@alexvfx.com
                </a>
            </div>

            <!-- Redes Sociales (Iconos limpios) -->
            <div class="flex items-center justify-center gap-4 pt-4 border-t border-gray-800/80">
                <a href="#" class="w-10 h-10 rounded-full bg-gray-800/60 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-800 transition-all">
                    <i class="fa-brands fa-youtube"></i>
                </a>
                <a href="#" class="w-10 h-10 rounded-full bg-gray-800/60 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-800 transition-all">
                    <i class="fa-brands fa-instagram"></i>
                </a>
                <a href="#" class="w-10 h-10 rounded-full bg-gray-800/60 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-800 transition-all">
                    <i class="fa-brands fa-tiktok"></i>
                </a>
                <a href="#" class="w-10 h-10 rounded-full bg-gray-800/60 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-800 transition-all">
                    <i class="fa-brands fa-linkedin-in"></i>
                </a>
                <a href="#" class="w-10 h-10 rounded-full bg-gray-800/60 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-800 transition-all">
                    <i class="fa-brands fa-vimeo-v"></i>
                </a>
            </div>
        </div>

        <!-- Sección de Trabajos Destacados (Grid Limpio) -->
        <div class="mb-10">
            <h2 class="text-xl font-bold mb-6 text-center text-gray-200 flex items-center justify-center gap-2">
                <i class="fa-solid fa-film text-amber-400"></i> Trabajos Destacados
            </h2>

            <div class="grid grid-cols-1 gap-6">
                <!-- Proyecto 1 -->
                <div class="group relative bg-gray-900/60 rounded-2xl overflow-hidden border border-gray-800 gold-glow transition-all duration-300">
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?auto=format&fit=crop&w=800&q=80" alt="Reel Deportivo - Nike" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-80 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-black/40 group-hover:bg-black/20 transition-colors flex items-center justify-center">
                            <div class="w-12 h-12 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-xl transform scale-75 group-hover:scale-100 transition-all duration-300">
                                <i class="fa-solid fa-play ml-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-5">
                        <span class="text-xs text-amber-400 font-semibold tracking-wider uppercase">Comercial / Motion Graphics</span>
                        <h3 class="text-lg font-bold mt-1 text-white group-hover:text-amber-400 transition-colors">Reel Deportivo - Nike</h3>
                    </div>
                </div>

                <!-- Proyecto 2 -->
                <div class="group relative bg-gray-900/60 rounded-2xl overflow-hidden border border-gray-800 gold-glow transition-all duration-300">
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1536240478700-b869070f9279?auto=format&fit=crop&w=800&q=80" alt="Videoclip Musical" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-80 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-black/40 group-hover:bg-black/20 transition-colors flex items-center justify-center">
                            <div class="w-12 h-12 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-xl transform scale-75 group-hover:scale-100 transition-all duration-300">
                                <i class="fa-solid fa-play ml-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-5">
                        <span class="text-xs text-amber-400 font-semibold tracking-wider uppercase">Videoclip / Color Grading</span>
                        <h3 class="text-lg font-bold mt-1 text-white group-hover:text-amber-400 transition-colors">Neon Nights - Music Video</h3>
                    </div>
                </div>

                <!-- Proyecto 3 -->
                <div class="group relative bg-gray-900/60 rounded-2xl overflow-hidden border border-gray-800 gold-glow transition-all duration-300">
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1611162617474-5b21e879e113?auto=format&fit=crop&w=800&q=80" alt="Documental de Viajes" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-80 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-black/40 group-hover:bg-black/20 transition-colors flex items-center justify-center">
                            <div class="w-12 h-12 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-xl transform scale-75 group-hover:scale-100 transition-all duration-300">
                                <i class="fa-solid fa-play ml-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-5">
                        <span class="text-xs text-amber-400 font-semibold tracking-wider uppercase">Documental / Storytelling</span>
                        <h3 class="text-lg font-bold mt-1 text-white group-hover:text-amber-400 transition-colors">Expedición Patagonia</h3>
                    </div>
                </div>

                <!-- Proyecto 4 -->
                <div class="group relative bg-gray-900/60 rounded-2xl overflow-hidden border border-gray-800 gold-glow transition-all duration-300">
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1511512578047-dfb367046420?auto=format&fit=crop&w=800&q=80" alt="Lanzamiento de Videojuego" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-80 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-black/40 group-hover:bg-black/20 transition-colors flex items-center justify-center">
                            <div class="w-12 h-12 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-xl transform scale-75 group-hover:scale-100 transition-all duration-300">
                                <i class="fa-solid fa-play ml-1"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-5">
                        <span class="text-xs text-amber-400 font-semibold tracking-wider uppercase">Teaser / Gaming</span>
                        <h3 class="text-lg font-bold mt-1 text-white group-hover:text-amber-400 transition-colors">Cyber Odyssey Trailer</h3>
                    </div>
                </div>
            </div>
        </div>

        <!-- Footer simple -->
        <footer class="text-center text-xs text-gray-500 pt-6 border-t border-gray-900">
            <p>&copy; 2026 Alex.VFX. Todos los derechos reservados.</p>
        </footer>

    </div>

</body>
</html>
