<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex.VFX | Video Editor & Content Creator</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            font-family: 'Inter', sans-serif;
        }
        body {
            background-color: #0a0a0a;
            color: #e5e5e5;
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- PERFIL -->
    <section class="pt-20 pb-16 px-6">
        <div class="max-w-2xl mx-auto text-center">
            
            <!-- Avatar grande con borde -->
            <div class="w-32 h-32 sm:w-40 sm:h-40 mx-auto mb-6 rounded-full p-1 border border-neutral-700">
                <img src="23161avatar.png" alt="Alex.VFX" class="w-full h-full object-cover rounded-full">
            </div>
            
            <!-- Nombre -->
            <h1 class="text-3xl sm:text-4xl font-bold tracking-tight mb-2">Alex.VFX</h1>
            
            <!-- Título -->
            <p class="text-neutral-400 mb-4">Video Editor & Content Creator</p>
            
            <!-- Bio -->
            <p class="text-neutral-500 text-sm max-w-md mx-auto mb-8 leading-relaxed">
                Transformo ideas en piezas visuales que conectan. Especializado en post-producción, motion graphics y color grading.
            </p>
            
            <!-- Botones -->
            <div class="flex flex-col sm:flex-row gap-3 justify-center mb-8 max-w-sm mx-auto">
                <a href="mailto:contacto@alexvfx.com" class="px-6 py-3 bg-white text-black text-sm font-medium rounded-full hover:bg-neutral-200 transition-colors">
                    <i class="fa-regular fa-envelope mr-2"></i> Email
                </a>
                <a href="https://wa.me/tu_numero" target="_blank" class="px-6 py-3 border border-neutral-700 text-sm rounded-full hover:border-neutral-400 transition-colors">
                    <i class="fa-brands fa-whatsapp mr-2"></i> WhatsApp
                </a>
            </div>
            
            <!-- Redes sociales -->
            <div class="flex justify-center gap-6 text-neutral-500">
                <a href="#" class="hover:text-white transition-colors"><i class="fa-brands fa-youtube text-xl"></i></a>
                <a href="#" class="hover:text-white transition-colors"><i class="fa-brands fa-instagram text-xl"></i></a>
                <a href="#" class="hover:text-white transition-colors"><i class="fa-brands fa-tiktok text-xl"></i></a>
                <a href="#" class="hover:text-white transition-colors"><i class="fa-brands fa-vimeo-v text-xl"></i></a>
                <a href="#" class="hover:text-white transition-colors"><i class="fa-brands fa-linkedin-in text-xl"></i></a>
            </div>
        </div>
    </section>

    <!-- TRABAJOS -->
    <section class="py-16 px-6 border-t border-neutral-900">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-2xl font-semibold tracking-tight mb-10 text-center">Trabajos Seleccionados</h2>

            <div class="space-y-12">
                <!-- Proyecto 1 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900">
                        <img src="https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?auto=format&fit=crop&w=1200&q=80" 
                             alt="Proyecto Nike" 
                             class="w-full aspect-video object-cover group-hover:scale-[1.02] transition-all duration-500">
                        <div class="absolute inset-0 bg-black/30 group-hover:bg-black/50 transition-colors flex items-center justify-center">
                            <span class="w-14 h-14 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
                                <i class="fa-solid fa-play text-white ml-1"></i>
                            </span>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Nike — Reel Deportivo</h3>
                        <p class="text-neutral-500 text-sm">Edición, Motion Graphics, Color Grading</p>
                    </div>
                </div>

                <!-- Proyecto 2 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900">
                        <img src="https://images.unsplash.com/photo-1536240478700-b869070f9279?auto=format&fit=crop&w=1200&q=80" 
                             alt="Neon Nights" 
                             class="w-full aspect-video object-cover group-hover:scale-[1.02] transition-all duration-500">
                        <div class="absolute inset-0 bg-black/30 group-hover:bg-black/50 transition-colors flex items-center justify-center">
                            <span class="w-14 h-14 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
                                <i class="fa-solid fa-play text-white ml-1"></i>
                            </span>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Neon Nights — Videoclip Musical</h3>
                        <p class="text-neutral-500 text-sm">Dirección de post, VFX, Sound Design</p>
                    </div>
                </div>

                <!-- Proyecto 3 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900">
                        <img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?auto=format&fit=crop&w=1200&q=80" 
                             alt="Documental" 
                             class="w-full aspect-video object-cover group-hover:scale-[1.02] transition-all duration-500">
                        <div class="absolute inset-0 bg-black/30 group-hover:bg-black/50 transition-colors flex items-center justify-center">
                            <span class="w-14 h-14 rounded-full bg-white/20 backdrop-blur-md flex items-center justify-center">
                                <i class="fa-solid fa-play text-white ml-1"></i>
                            </span>
                        </div>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Tierra — Documental</h3>
                        <p class="text-neutral-500 text-sm">Montaje, Corrección de color, Sonido</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="py-10 px-6 border-t border-neutral-900">
        <div class="max-w-4xl mx-auto text-center text-sm text-neutral-600">
            <p>© 2026 Alex.VFX — Editando historias que importan</p>
        </div>
    </footer>

</body>
</html>
