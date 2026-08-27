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
<body class="bg-[#0b0f19] text-gray-100 selection:bg-amber-500 selection:text-black min-h-screen pb-20">

    <!-- Contenedor adaptable para Celular y PC -->
    <div class="max-w-4xl mx-auto px-4 sm:px-6 pt-12">
        
        <!-- Tarjeta de Perfil Estilo Red Social -->
        <div class="bg-gray-900/90 border border-gray-800 rounded-3xl p-6 sm:p-10 text-center backdrop-blur-md shadow-2xl relative overflow-hidden mb-12">
            <!-- Fondo sutil decorativo -->
            <div class="absolute -top-32 left-1/2 -translate-x-1/2 w-80 h-80 bg-amber-500/10 rounded-full blur-3xl pointer-events-none"></div>

            <!-- Avatar del Creador (Tu foto 23161avatar.png) -->
            <div class="relative w-32 h-32 sm:w-36 sm:h-36 mx-auto mb-6 rounded-full p-1 bg-gradient-to-tr from-amber-500 to-amber-300 shadow-xl">
                <img src="23161avatar.png" alt="Alex.VFX" class="w-full h-full object-cover rounded-full bg-gray-950">
            </div>

            <!-- Nombre y Eslogan -->
            <h1 class="text-3xl sm:text-4xl font-extrabold text-white flex items-center justify-center gap-2">
                Alex.VFX <i class="fa-solid fa-circle-check text-amber-400 text-xl"></i>
            </h1>
            <p class="text-base sm:text-lg text-amber-400 font-medium mt-2 mb-4 flex items-center justify-center gap-2">
                <i class="fa-solid fa-clapperboard"></i> Video Editor & Content Creator
            </p>
            <p class="text-sm sm:text-base text-gray-300 max-w-xl mx-auto mb-8 leading-relaxed">
                Transformando ideas en historias visuales de alto impacto. Especialista en Premiere Pro, After Effects y DaVinci Resolve. ✨
            </p>

            <!-- Botones de Acción -->
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-8 max-w-md mx-auto">
                <a href="https://wa.me/tu_numero_aqui" target="_blank" class="w-full py-3.5 px-6 rounded-xl bg-emerald-600 hover:bg-emerald-500 text-white font-bold transition-all flex items-center justify-center gap-3 shadow-lg shadow-emerald-600/20 text-sm sm:text-base">
                    <i class="fa-brands fa-whatsapp text-lg"></i> Escríbeme al WhatsApp 🟢
                </a>
                <a href="mailto:contacto@alexvfx.com" class="w-full py-3.5 px-6 rounded-xl bg-gray-800/90 hover:bg-gray-800 border border-gray-700 text-gray-200 font-semibold transition-all flex items-center justify-center gap-2 text-sm sm:text-base">
                    <i class="fa-regular fa-envelope text-amber-400"></i> Correo 📬
                </a>
            </div>

            <!-- Redes Sociales -->
            <div class="flex items-center justify-center gap-5 pt-6 border-t border-gray-800">
                <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-750 transition-all text-lg"><i class="fa-brands fa-youtube"></i></a>
                <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-750 transition-all text-lg"><i class="fa-brands fa-instagram"></i></a>
                <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-750 transition-all text-lg"><i class="fa-brands fa-tiktok"></i></a>
                <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-750 transition-all text-lg"><i class="fa-brands fa-linkedin-in"></i></a>
                <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-750 transition-all text-lg"><i class="fa-brands fa-vimeo-v"></i></a>
            </div>
        </div>

        <!-- Sección de Trabajos Destacados (Grid: 1 columna en celular, 2 columnas en PC) -->
        <div class="mb-12">
            <h2 class="text-2xl font-bold mb-8 text-center text-gray-100 flex items-center justify-center gap-3">
                <i class="fa-solid fa-film text-amber-400"></i> Trabajos Destacados 🎬
            </h2>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Proyecto 1 -->
                <div class="group relative bg-gray-900/80 rounded-2xl overflow-hidden border border-gray-800 gold-glow transition-all duration-300 shadow-xl">
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?auto=format&fit=crop&w=800&q=80" alt="Reel Deportivo" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-85 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-black/40 group-hover:bg-black/20 transition-colors flex items-center justify-center">
                            <div class="w-14 h-14 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-xl transform scale-75 group-hover:scale-100 transition-all duration-300">
                                <i class="fa-solid fa-play ml-1 text-lg"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <span class="text-xs text-amber-400 font-bold tracking-widest uppercase">Comercial / Motion Graphics</span>
                        <h3 class="text-xl font-bold mt-1 text-white group-hover:text-amber-400 transition-colors">Reel Deportivo - Nike</h3>
                    </div>
                </div>

                <!-- Proyecto 2 -->
                <div class="group relative bg-gray-900/80 rounded-2xl overflow-hidden border border-gray-800 gold-glow transition-all duration-300 shadow-xl">
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1536240478700-b869070f9279?auto=format&fit=crop&w=800&q=80" alt="Videoclip Musical" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500 opacity-85 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-black/40 group-hover:bg-black/20 transition-colors flex items-center justify-center">
                            <div class="w-14 h-14 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-xl transform scale-75 group-hover:scale-100 transition-all duration-300">
                                <i class="fa-solid fa-play ml-1 text-lg"></i>
                            </div>
                        </div>
                    </div>
                    <div class="p-6">
                        <span class="text-xs text-amber-400 font-bold tracking-widest uppercase">Videoclip / Color Grading</span>
                        <h3 class="text-xl font-bold mt-1 text-white group-hover:text-amber-400 transition-colors">Neon Nights - Music Video</h3>
                    </div>
                </div>
            </div>
        </div>

        <!-- Footer -->
        <footer class="text-center text-sm text-gray-400 pt-8 border-t border-gray-900">
            <p>&copy; 2026 Alex.VFX. Todos los derechos reservados. ✨</p>
        </footer>

    </div>

</body>
</html>
