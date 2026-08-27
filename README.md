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

    <!-- TRABAJOS (Videos de YouTube) -->
    <section class="py-16 px-6 border-t border-neutral-900">
        <div class="max-w-4xl mx-auto">
            <h2 class="text-2xl font-semibold tracking-tight mb-10 text-center">Trabajos Seleccionados</h2>

            <div class="space-y-12">
                <!-- Proyecto 1 -->
                <div>
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900 aspect-video">
                        <iframe class="w-full h-full" src="https://www.youtube-nocookie.com/embed/CBE1PkDRONc" title="Proyecto 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Proyecto 1</h3>
                        <p class="text-neutral-500 text-sm">Edición, Motion Graphics, Color Grading</p>
                    </div>
                </div>

                <!-- Proyecto 2 -->
                <div>
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900 aspect-video">
                        <iframe class="w-full h-full" src="https://www.youtube-nocookie.com/embed/iM32pC5zweY" title="Proyecto 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Proyecto 2</h3>
                        <p class="text-neutral-500 text-sm">Dirección de post, VFX, Sound Design</p>
                    </div>
                </div>

                <!-- Proyecto 3 -->
                <div>
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900 aspect-video">
                        <iframe class="w-full h-full" src="https://www.youtube-nocookie.com/embed/WZQHXE6hvmg" title="Proyecto 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Proyecto 3</h3>
                        <p class="text-neutral-500 text-sm">Montaje, Corrección de color, Sonido</p>
                    </div>
                </div>

                <!-- Proyecto 4 -->
                <div>
                    <div class="relative overflow-hidden rounded-xl mb-4 bg-neutral-900 aspect-video">
                        <iframe class="w-full h-full" src="https://www.youtube-nocookie.com/embed/iM32pC5zweY" title="Proyecto 4" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div>
                        <h3 class="text-lg font-medium mb-1">Proyecto 4</h3>
                        <p class="text-neutral-500 text-sm">Post-producción y Edición Avanzada</p>
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
