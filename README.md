<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alex.VFX | Video Editor & Content Creator</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            font-family: 'Inter', sans-serif;
        }
        body {
            background-color: #0a0a0a;
            color: #e5e5e5;
        }
        .gold {
            color: #d4a853;
        }
        .border-gold {
            border-color: #d4a853;
        }
        .avatar-ring {
            background: linear-gradient(135deg, #d4a853, #f0d080, #b8943e);
            padding: 3px;
        }
        .verified-badge {
            background: linear-gradient(135deg, #d4a853, #f0d080);
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- NAVBAR -->
    <nav class="fixed top-0 w-full bg-black/80 backdrop-blur-lg border-b border-neutral-800 z-50">
        <div class="max-w-5xl mx-auto px-6 py-4 flex items-center justify-between">
            <a href="#" class="text-lg font-semibold tracking-tight">
                Alex<span class="gold">.VFX</span>
            </a>
            <div class="hidden md:flex gap-8 text-sm text-neutral-400">
                <a href="#work" class="hover:text-white transition-colors">Trabajos</a>
                <a href="#about" class="hover:text-white transition-colors">Sobre mí</a>
                <a href="#contact" class="hover:text-white transition-colors">Contacto</a>
            </div>
            <a href="#contact" class="text-sm px-4 py-2 border border-neutral-700 hover:border-gold hover:text-gold transition-all rounded-full">
                Contratar
            </a>
        </div>
    </nav>

    <!-- PERFIL ESTILO RED SOCIAL -->
    <section class="pt-32 pb-16 px-6">
        <div class="max-w-2xl mx-auto">
            <!-- Tarjeta de perfil -->
            <div class="bg-neutral-950 border border-neutral-800 rounded-3xl overflow-hidden">
                <!-- Banner/Cover -->
                <div class="h-32 sm:h-40 bg-gradient-to-r from-neutral-900 via-neutral-800 to-neutral-900 relative">
                    <div class="absolute inset-0 opacity-20" style="background-image: radial-gradient(circle at 30% 50%, #d4a853 0%, transparent 50%), radial-gradient(circle at 70% 50%, #d4a853 0%, transparent 50%);"></div>
                </div>
                
                <!-- Contenido del perfil -->
                <div class="px-6 sm:px-8 pb-8">
                    <!-- Avatar superpuesto -->
                    <div class="flex justify-start -mt-16 sm:-mt-20 mb-4">
                        <div class="avatar-ring rounded-full w-28 h-28 sm:w-36 sm:h-36 shadow-2xl">
                            <img src="23161avatar.png" alt="Alex.VFX" class="w-full h-full object-cover rounded-full border-4 border-neutral-950">
                        </div>
                    </div>
                    
                    <!-- Nombre y verificación -->
                    <div class="flex items-center gap-2 mb-1">
                        <h1 class="text-2xl sm:text-3xl font-bold tracking-tight">Alex.VFX</h1>
                        <span class="verified-badge text-black rounded-full p-0.5">
                            <i class="fa-solid fa-check text-[10px]"></i>
                        </span>
                    </div>
                    
                    <!-- Título profesional -->
                    <p class="text-neutral-400 font-medium mb-3">Video Editor & Content Creator</p>
                    
                    <!-- Bio -->
                    <p class="text-neutral-500 text-sm leading-relaxed mb-4 max-w-md">
                        Transformo ideas en piezas visuales que conectan. Especializado en post-producción, motion graphics y color grading.
                    </p>
                    
                    <!-- Ubicación y estado -->
                    <div class="flex items-center gap-4 text-sm text-neutral-500 mb-6">
                        <span><i class="fa-solid fa-location-dot mr-1"></i> Venezuela</span>
                        <span class="flex items-center gap-1">
                            <span class="w-2 h-2 bg-green-500 rounded-full"></span>
                            Disponible
                        </span>
                    </div>
                    
                    <!-- Botones de acción -->
                    <div class="flex flex-col sm:flex-row gap-3 mb-6">
                        <a href="mailto:contacto@alexvfx.com" class="flex-1 px-6 py-3 bg-white text-black text-sm font-semibold rounded-full hover:bg-neutral-200 transition-colors text-center">
                            <i class="fa-regular fa-envelope mr-2"></i> Enviar Email
                        </a>
                        <a href="https://wa.me/tu_numero" target="_blank" class="flex-1 px-6 py-3 border border-neutral-700 text-sm font-semibold rounded-full hover:border-gold hover:text-gold transition-colors text-center">
                            <i class="fa-brands fa-whatsapp mr-2"></i> WhatsApp
                        </a>
                    </div>
                    
                    <!-- Redes sociales -->
                    <div class="flex items-center justify-center gap-6 pt-6 border-t border-neutral-800">
                        <a href="#" class="text-neutral-500 hover:text-white transition-colors transform hover:scale-110">
                            <i class="fa-brands fa-youtube text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-500 hover:text-white transition-colors transform hover:scale-110">
                            <i class="fa-brands fa-instagram text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-500 hover:text-white transition-colors transform hover:scale-110">
                            <i class="fa-brands fa-tiktok text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-500 hover:text-white transition-colors transform hover:scale-110">
                            <i class="fa-brands fa-vimeo-v text-xl"></i>
                        </a>
                        <a href="#" class="text-neutral-500 hover:text-white transition-colors transform hover:scale-110">
                            <i class="fa-brands fa-linkedin-in text-xl"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- TRABAJOS -->
    <section id="work" class="py-16 px-6">
        <div class="max-w-5xl mx-auto">
            <div class="flex items-end justify-between mb-10">
                <h2 class="text-2xl font-semibold tracking-tight">Trabajos Seleccionados</h2>
                <span class="text-sm text-neutral-500">2024 — 2026</span>
            </div>

            <div class="space-y-16">
                <!-- Proyecto 1 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-lg mb-4 bg-neutral-900">
                        <img src="https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?auto=format&fit=crop&w=1200&q=80" 
                             alt="Proyecto Nike" 
                             class="w-full aspect-video object-cover opacity-90 group-hover:opacity-100 group-hover:scale-[1.02] transition-all duration-500">
                        <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors flex items-center justify-center">
                            <span class="w-16 h-16 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all">
                                <i class="fa-solid fa-play text-white"></i>
                            </span>
                        </div>
                    </div>
                    <div class="flex items-start justify-between">
                        <div>
                            <h3 class="text-lg font-medium mb-1">Nike — Reel Deportivo</h3>
                            <p class="text-neutral-500 text-sm">Edición, Motion Graphics, Color Grading</p>
                        </div>
                        <span class="text-sm text-neutral-500">2026</span>
                    </div>
                </div>

                <!-- Proyecto 2 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-lg mb-4 bg-neutral-900">
                        <img src="https://images.unsplash.com/photo-1536240478700-b869070f9279?auto=format&fit=crop&w=1200&q=80" 
                             alt="Neon Nights" 
                             class="w-full aspect-video object-cover opacity-90 group-hover:opacity-100 group-hover:scale-[1.02] transition-all duration-500">
                        <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors flex items-center justify-center">
                            <span class="w-16 h-16 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all">
                                <i class="fa-solid fa-play text-white"></i>
                            </span>
                        </div>
                    </div>
                    <div class="flex items-start justify-between">
                        <div>
                            <h3 class="text-lg font-medium mb-1">Neon Nights — Videoclip Musical</h3>
                            <p class="text-neutral-500 text-sm">Dirección de post, VFX, Sound Design</p>
                        </div>
                        <span class="text-sm text-neutral-500">2025</span>
                    </div>
                </div>

                <!-- Proyecto 3 -->
                <div class="group cursor-pointer">
                    <div class="relative overflow-hidden rounded-lg mb-4 bg-neutral-900">
                        <img src="https://images.unsplash.com/photo-1492691527719-9d1e07e534b4?auto=format&fit=crop&w=1200&q=80" 
                             alt="Documental" 
                             class="w-full aspect-video object-cover opacity-90 group-hover:opacity-100 group-hover:scale-[1.02] transition-all duration-500">
                        <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors flex items-center justify-center">
                            <span class="w-16 h-16 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center opacity-0 group-hover:opacity-100 transition-all">
                                <i class="fa-solid fa-play text-white"></i>
                            </span>
                        </div>
                    </div>
                    <div class="flex items-start justify-between">
                        <div>
                            <h3 class="text-lg font-medium mb-1">Tierra — Documental</h3>
                            <p class="text-neutral-500 text-sm">Montaje, Corrección de color, Sonido</p>
                        </div>
                        <span class="text-sm text-neutral-500">2024</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SOBRE MÍ -->
    <section id="about" class="py-16 px-6 border-t border-neutral-900">
        <div class="max-w-3xl mx-auto text-center">
            <h2 class="text-2xl font-semibold tracking-tight mb-6">Sobre mí</h2>
            <p class="text-neutral-400 leading-relaxed mb-4">
                Soy editor de video con más de 5 años de experiencia trabajando con marcas, agencias y creadores de contenido. Mi enfoque está en la narrativa visual — cada corte, transición y ajuste de color tiene un propósito.
            </p>
            <p class="text-neutral-400 leading-relaxed">
                He colaborado con equipos en Latinoamérica y Europa, entregando proyectos que no solo cumplen, sino que superan las expectativas.
            </p>
        </div>
    </section>

    <!-- CONTACTO -->
    <section id="contact" class="py-16 px-6 border-t border-neutral-900">
        <div class="max-w-3xl mx-auto text-center">
            <h2 class="text-2xl font-semibold tracking-tight mb-4">¿Tienes un proyecto?</h2>
            <p class="text-neutral-400 mb-8 text-sm">Hablemos de cómo puedo ayudarte a llevarlo al siguiente nivel.</p>
            <div class="flex flex-col sm:flex-row gap-3 justify-center max-w-sm mx-auto">
                <a href="mailto:contacto@alexvfx.com" class="px-6 py-3 bg-white text-black text-sm font-medium rounded-full hover:bg-neutral-200 transition-colors">
                    <i class="fa-regular fa-envelope mr-2"></i> Email
                </a>
                <a href="https://wa.me/tu_numero" target="_blank" class="px-6 py-3 border border-neutral-700 text-sm rounded-full hover:border-neutral-400 transition-colors">
                    <i class="fa-brands fa-whatsapp mr-2"></i> WhatsApp
                </a>
            </div>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="py-8 px-6 border-t border-neutral-900">
        <div class="max-w-5xl mx-auto flex flex-col md:flex-row justify-between items-center text-sm text-neutral-600">
            <p>© 2026 Alex.VFX</p>
            <p>Editando historias que importan</p>
        </div>
    </footer>

</body>
</html>
