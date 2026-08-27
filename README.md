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
            overflow-x: hidden;
        }
        
        .gold-gradient {
            background: linear-gradient(135deg, #f59e0b 0%, #d97706 50%, #b45309 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        /* Bordes animados profesionales */
        .animated-border {
            position: relative;
            background: linear-gradient(#0b0f19, #0b0f19) padding-box,
                        linear-gradient(135deg, #f59e0b, #d97706, #fbbf24, #b45309) border-box;
            border: 2px solid transparent;
            animation: borderRotate 4s linear infinite;
        }
        
        @keyframes borderRotate {
            0% { 
                filter: hue-rotate(0deg);
            }
            100% { 
                filter: hue-rotate(360deg);
            }
        }
        
        /* Efecto de brillo en bordes */
        .border-glow {
            position: relative;
            overflow: hidden;
        }
        
        .border-glow::before {
            content: '';
            position: absolute;
            top: -2px;
            left: -2px;
            right: -2px;
            bottom: -2px;
            background: linear-gradient(45deg, #f59e0b, #d97706, #fbbf24, #b45309, #f59e0b);
            background-size: 400% 400%;
            animation: gradientShift 3s ease infinite;
            z-index: -1;
            border-radius: inherit;
        }
        
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .gold-glow:hover {
            box-shadow: 0 0 30px rgba(245, 158, 11, 0.3), 0 0 60px rgba(245, 158, 11, 0.1);
        }
        
        /* Animación de pulso para el avatar */
        @keyframes pulseRing {
            0% { transform: scale(1); opacity: 1; }
            100% { transform: scale(1.5); opacity: 0; }
        }
        
        .avatar-ring::after {
            content: '';
            position: absolute;
            inset: -3px;
            border-radius: 50%;
            border: 2px solid rgba(245, 158, 11, 0.6);
            animation: pulseRing 2s ease-out infinite;
        }
        
        /* Efecto de hover en proyectos */
        .project-card {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }
        
        .project-card:hover {
            transform: translateY(-8px);
            border-color: rgba(245, 158, 11, 0.6);
        }
        
        /* Barra de scroll personalizada */
        ::-webkit-scrollbar {
            width: 8px;
        }
        
        ::-webkit-scrollbar-track {
            background: #1a1f2e;
        }
        
        ::-webkit-scrollbar-thumb {
            background: linear-gradient(180deg, #d97706, #f59e0b);
            border-radius: 10px;
        }
        
        /* Efecto de brillo en texto */
        .shine-effect {
            position: relative;
            overflow: hidden;
        }
        
        .shine-effect::after {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(
                45deg,
                transparent 40%,
                rgba(255, 255, 255, 0.1) 50%,
                transparent 60%
            );
            animation: shine 3s infinite;
        }
        
        @keyframes shine {
            0% { transform: translateX(-100%) rotate(45deg); }
            100% { transform: translateX(100%) rotate(45deg); }
        }
        
        /* Fondo con patrón sutil */
        .bg-pattern {
            background-image: 
                radial-gradient(circle at 25% 25%, rgba(245, 158, 11, 0.03) 0%, transparent 50%),
                radial-gradient(circle at 75% 75%, rgba(245, 158, 11, 0.03) 0%, transparent 50%);
        }
    </style>
</head>
<body class="bg-[#0b0f19] text-gray-100 selection:bg-amber-500 selection:text-black min-h-screen pb-20 bg-pattern">

    <!-- Contenedor adaptable para Celular y PC -->
    <div class="max-w-4xl mx-auto px-4 sm:px-6 pt-12 relative">
        
        <!-- Línea decorativa superior -->
        <div class="absolute top-0 left-1/2 -translate-x-1/2 w-32 h-1 bg-gradient-to-r from-transparent via-amber-500 to-transparent rounded-full"></div>

        <!-- Tarjeta de Perfil Estilo Red Social con bordes mejorados -->
        <div class="relative bg-gray-900/95 rounded-3xl p-6 sm:p-10 text-center backdrop-blur-md shadow-2xl mb-12 border-glow">
            <!-- Borde animado -->
            <div class="absolute inset-0 rounded-3xl p-[2px] bg-gradient-to-r from-amber-500 via-yellow-400 to-amber-600 opacity-50 group-hover:opacity-100 transition-opacity"></div>
            <div class="absolute inset-[2px] rounded-3xl bg-gray-900/95"></div>
            
            <!-- Contenido -->
            <div class="relative z-10">
                <!-- Fondo sutil decorativo -->
                <div class="absolute -top-32 left-1/2 -translate-x-1/2 w-80 h-80 bg-amber-500/10 rounded-full blur-3xl pointer-events-none"></div>

                <!-- Avatar del Creador con anillo animado -->
                <div class="avatar-ring relative w-32 h-32 sm:w-36 sm:h-36 mx-auto mb-6 rounded-full p-1 bg-gradient-to-tr from-amber-500 to-amber-300 shadow-2xl">
                    <img src="23161avatar.png" alt="Alex.VFX" class="w-full h-full object-cover rounded-full bg-gray-950 relative z-10">
                    <div class="absolute inset-0 rounded-full bg-gradient-to-tr from-amber-500/20 to-transparent"></div>
                </div>

                <!-- Nombre y Eslogan con efecto shine -->
                <div class="shine-effect inline-block">
                    <h1 class="text-3xl sm:text-4xl font-extrabold text-white flex items-center justify-center gap-2 mb-2">
                        Alex.VFX <i class="fa-solid fa-circle-check text-amber-400 text-xl"></i>
                    </h1>
                </div>
                
                <p class="text-base sm:text-lg text-amber-400 font-medium mt-2 mb-4 flex items-center justify-center gap-2">
                    <i class="fa-solid fa-clapperboard"></i> Video Editor & Content Creator
                    <span class="inline-flex items-center gap-1 ml-2 px-2 py-0.5 bg-amber-500/10 rounded-full text-xs">
                        <i class="fa-solid fa-star text-amber-400"></i> PRO
                    </span>
                </p>
                
                <p class="text-sm sm:text-base text-gray-300 max-w-xl mx-auto mb-8 leading-relaxed">
                    Transformando ideas en historias visuales de alto impacto. Especialista en Premiere Pro, After Effects y DaVinci Resolve.
                </p>

                <!-- Botones de Acción con bordes mejorados -->
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-8 max-w-md mx-auto">
                    <a href="https://wa.me/tu_numero_aqui" target="_blank" class="w-full py-3.5 px-6 rounded-xl bg-gradient-to-r from-emerald-600 to-emerald-700 hover:from-emerald-500 hover:to-emerald-600 text-white font-bold transition-all flex items-center justify-center gap-3 shadow-lg shadow-emerald-600/30 text-sm sm:text-base border border-emerald-400/30 hover:border-emerald-400/60">
                        <i class="fa-brands fa-whatsapp text-lg"></i> Escríbeme al WhatsApp
                    </a>
                    <a href="mailto:contacto@alexvfx.com" class="w-full py-3.5 px-6 rounded-xl bg-gray-800/90 hover:bg-gray-800 border border-gray-700 hover:border-amber-500/50 text-gray-200 font-semibold transition-all flex items-center justify-center gap-2 text-sm sm:text-base">
                        <i class="fa-regular fa-envelope text-amber-400"></i> Correo
                    </a>
                </div>

                <!-- Redes Sociales con efectos hover -->
                <div class="flex items-center justify-center gap-4 pt-6 border-t border-gray-800">
                    <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-700 hover:border-amber-500 border border-transparent transition-all text-lg transform hover:scale-110 hover:rotate-3">
                        <i class="fa-brands fa-youtube"></i>
                    </a>
                    <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-700 hover:border-amber-500 border border-transparent transition-all text-lg transform hover:scale-110 hover:-rotate-3">
                        <i class="fa-brands fa-instagram"></i>
                    </a>
                    <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-700 hover:border-amber-500 border border-transparent transition-all text-lg transform hover:scale-110 hover:rotate-6">
                        <i class="fa-brands fa-tiktok"></i>
                    </a>
                    <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-700 hover:border-amber-500 border border-transparent transition-all text-lg transform hover:scale-110 hover:-rotate-6">
                        <i class="fa-brands fa-linkedin-in"></i>
                    </a>
                    <a href="#" class="w-11 h-11 rounded-full bg-gray-800 flex items-center justify-center text-gray-300 hover:text-amber-400 hover:bg-gray-700 hover:border-amber-500 border border-transparent transition-all text-lg transform hover:scale-110">
                        <i class="fa-brands fa-vimeo-v"></i>
                    </a>
                </div>
            </div>
        </div>

        <!-- Sección de Trabajos Destacados -->
        <div class="mb-12">
            <h2 class="text-2xl font-bold mb-8 text-center text-gray-100 flex items-center justify-center gap-3">
                <span class="w-8 h-px bg-gradient-to-r from-transparent to-amber-500"></span>
                <i class="fa-solid fa-film text-amber-400"></i> 
                Trabajos Destacados
                <span class="w-8 h-px bg-gradient-to-l from-transparent to-amber-500"></span>
            </h2>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Proyecto 1 -->
                <div class="project-card group relative bg-gray-900/80 rounded-2xl overflow-hidden border-2 border-gray-700 gold-glow shadow-xl">
                    <div class="absolute inset-0 bg-gradient-to-br from-amber-500/5 to-transparent pointer-events-none"></div>
                    
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1574717024653-61fd2cf4d44d?auto=format&fit=crop&w=800&q=80" alt="Reel Deportivo" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700 opacity-85 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
                        
                        <!-- Botón de play animado -->
                        <div class="absolute inset-0 flex items-center justify-center">
                            <div class="relative">
                                <div class="absolute inset-0 bg-amber-500/30 rounded-full scale-150 animate-ping opacity-75"></div>
                                <div class="w-14 h-14 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-2xl transform scale-75 group-hover:scale-100 group-hover:rotate-90 transition-all duration-300 relative z-10">
                                    <i class="fa-solid fa-play ml-1 text-lg"></i>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Badge de duración -->
                        <span class="absolute top-3 right-3 px-2 py-1 bg-black/70 backdrop-blur-sm rounded-lg text-xs font-medium text-white">
                            00:45
                        </span>
                    </div>
                    
                    <div class="p-6 border-t border-gray-800 group-hover:border-amber-500/50 transition-colors">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-xs text-amber-400 font-bold tracking-widest uppercase">Comercial / Motion Graphics</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-eye"></i> 12.5k</span>
                        </div>
                        <h3 class="text-xl font-bold text-white group-hover:text-amber-400 transition-colors">Reel Deportivo - Nike</h3>
                        <div class="flex gap-2 mt-3">
                            <span class="px-2 py-1 bg-gray-800 rounded text-xs text-gray-300">4K</span>
                            <span class="px-2 py-1 bg-gray-800 rounded text-xs text-gray-300">60fps</span>
                            <span class="px-2 py-1 bg-gray-800 rounded text-xs text-gray-300">Color Grading</span>
                        </div>
                    </div>
                </div>

                <!-- Proyecto 2 -->
                <div class="project-card group relative bg-gray-900/80 rounded-2xl overflow-hidden border-2 border-gray-700 gold-glow shadow-xl">
                    <div class="absolute inset-0 bg-gradient-to-br from-amber-500/5 to-transparent pointer-events-none"></div>
                    
                    <div class="relative aspect-video overflow-hidden bg-gray-950">
                        <img src="https://images.unsplash.com/photo-1536240478700-b869070f9279?auto=format&fit=crop&w=800&q=80" alt="Videoclip Musical" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700 opacity-85 group-hover:opacity-100">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
                        
                        <!-- Botón de play animado -->
                        <div class="absolute inset-0 flex items-center justify-center">
                            <div class="relative">
                                <div class="absolute inset-0 bg-amber-500/30 rounded-full scale-150 animate-ping opacity-75"></div>
                                <div class="w-14 h-14 rounded-full bg-amber-500 text-black flex items-center justify-center shadow-2xl transform scale-75 group-hover:scale-100 group-hover:rotate-90 transition-all duration-300 relative z-10">
                                    <i class="fa-solid fa-play ml-1 text-lg"></i>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Badge de duración -->
                        <span class="absolute top-3 right-3 px-2 py-1 bg-black/70 backdrop-blur-sm rounded-lg text-xs font-medium text-white">
                            03:12
                        </span>
                    </div>
                    
                    <div class="p-6 border-t border-gray-800 group-hover:border-amber-500/50 transition-colors">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-xs text-amber-400 font-bold tracking-widest uppercase">Videoclip / Color Grading</span>
                            <span class="text-xs text-gray-400"><i class="fa-solid fa-heart text-red-500"></i> 8.2k</span>
                        </div>
                        <h3 class="text-xl font-bold text-white group-hover:text-amber-400 transition-colors">Neon Nights - Music Video</h3>
                        <div class="flex gap-2 mt-3">
                            <span class="px-2 py-1 bg-gray-800 rounded text-xs text-gray-300">Cinematic</span>
                            <span class="px-2 py-1 bg-gray-800 rounded text-xs text-gray-300">VFX</span>
                            <span class="px-2 py-1 bg-gray-800 rounded text-xs text-gray-300">Sound Design</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Sección de Skills -->
        <div class="mb-12">
            <h2 class="text-2xl font-bold mb-8 text-center text-gray-100 flex items-center justify-center gap-3">
                <span class="w-8 h-px bg-gradient-to-r from-transparent to-amber-500"></span>
                <i class="fa-solid fa-tools text-amber-400"></i> 
                Habilidades
                <span class="w-8 h-px bg-gradient-to-l from-transparent to-amber-500"></span>
            </h2>
            
            <div class="grid grid-cols-2 sm:grid-cols-3 gap-4">
                <div class="bg-gray-900/80 border border-gray-800 rounded-xl p-4 text-center hover:border-amber-500/50 transition-all group">
                    <i class="fa-solid fa-video text-2xl text-amber-400 mb-2 group-hover:scale-110 transition-transform"></i>
                    <p class="text-sm font-semibold">Premiere Pro</p>
                    <div class="mt-2 h-1 bg-gray-800 rounded-full overflow-hidden">
                        <div class="h-full w-[95%] bg-gradient-to-r from-amber-500 to-amber-400 rounded-full"></div>
                    </div>
                </div>
                <div class="bg-gray-900/80 border border-gray-800 rounded-xl p-4 text-center hover:border-amber-500/50 transition-all group">
                    <i class="fa-solid fa-wand-magic-sparkles text-2xl text-amber-400 mb-2 group-hover:scale-110 transition-transform"></i>
                    <p class="text-sm font-semibold">After Effects</p>
                    <div class="mt-2 h-1 bg-gray-800 rounded-full overflow-hidden">
                        <div class="h-full w-[90%] bg-gradient-to-r from-amber-500 to-amber-400 rounded-full"></div>
                    </div>
                </div>
                <div class="bg-gray-900/80 border border-gray-800 rounded-xl p-4 text-center hover:border-amber-500/50 transition-all group">
                    <i class="fa-solid fa-palette text-2xl text-amber-400 mb-2 group-hover:scale-110 transition-transform"></i>
                    <p class="text-sm font-semibold">DaVinci Resolve</p>
                    <div class="mt-2 h-1 bg-gray-800 rounded-full overflow-hidden">
                        <div class="h-full w-[85%] bg-gradient-to-r from-amber-500 to-amber-400 rounded-full"></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Footer -->
        <footer class="text-center text-sm text-gray-400 pt-8 border-t border-gray-900 relative">
            <div class="absolute top-0 left-1/2 -translate-x-1/2 w-24 h-px bg-gradient-to-r from-transparent via-amber-500 to-transparent"></div>
            <p>&copy; 2026 Alex.VFX. Todos los derechos reservados.</p>
            <p class="mt-2 text-xs">
                <i class="fa-solid fa-location-dot text-amber-400"></i> Disponible para proyectos freelance
                <span class="mx-2">•</span>
                <i class="fa-solid fa-bolt text-amber-400"></i> Respuesta en menos de 24h
            </p>
        </footer>

    </div>

    <!-- Script para animaciones adicionales -->
    <script>
        // Animación de aparición al hacer scroll
        document.addEventListener('DOMContentLoaded', function() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = '1';
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, {
                threshold: 0.1
            });

            // Observar elementos para animación
            document.querySelectorAll('.project-card, .bg-gray-900\\/80').forEach(el => {
                el.style.opacity = '0';
                el.style.transform = 'translateY(20px)';
                el.style.transition = 'opacity 0.6s ease, transform 0.6s ease';
                observer.observe(el);
            });
        });
    </script>

</body>
</html>
