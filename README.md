<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Institución Educativa Hispanoamericana</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">
    <!-- Header -->
    <header class="bg-white shadow-sm border-b">
        <div class="container mx-auto px-4 lg:px-6 h-16 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <i data-lucide="graduation-cap" class="h-8 w-8 text-emerald-600"></i>
                <div>
                    <h1 class="text-xl font-bold text-gray-900">Institución Educativa</h1>
                    <p class="text-sm text-emerald-600 font-medium">Hispanoamericana</p>
                </div>
            </div>
            <nav class="hidden md:flex items-center space-x-6">
                <a href="#inicio" class="text-gray-700 hover:text-emerald-600 transition-colors">
                    Inicio
                </a>
                <a href="#nosotros" class="text-gray-700 hover:text-emerald-600 transition-colors">
                    Nosotros
                </a>
                <a href="#programas" class="text-gray-700 hover:text-emerald-600 transition-colors">
                    Programas
                </a>
                <a href="#instalaciones" class="text-gray-700 hover:text-emerald-600 transition-colors">
                    Instalaciones
                </a>
                <a href="#contacto" class="text-gray-700 hover:text-emerald-600 transition-colors">
                    Contacto
                </a>
            </nav>
            <button class="bg-emerald-600 hover:bg-emerald-700 text-white py-2 px-4 rounded-md transition-colors">Admisiones</button>
        </div>
    </header>

    <main class="flex-1">
        <!-- Hero Section -->
        <section id="inicio" class="bg-gradient-to-r from-emerald-50 to-teal-50 py-20">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="grid lg:grid-cols-2 gap-12 items-center">
                    <div class="space-y-6">
                        <span class="bg-emerald-100 text-emerald-800 hover:bg-emerald-100 text-sm font-medium px-3 py-1 rounded-full">
                            Excelencia Educativa desde 1985
                        </span>
                        <h1 class="text-4xl lg:text-6xl font-bold text-gray-900 leading-tight">
                            Formando líderes del <span class="text-emerald-600">futuro</span>
                        </h1>
                        <p class="text-xl text-gray-600 leading-relaxed">
                            En la Institución Educativa Hispanoamericana, brindamos una educación integral que combina excelencia
                            académica, valores sólidos y desarrollo personal para preparar a nuestros estudiantes para los
                            desafíos del mañana.
                        </p>
                        <div class="flex flex-col sm:flex-row gap-4">
                            <button class="bg-emerald-600 hover:bg-emerald-700 text-white py-3 px-6 rounded-md text-lg transition-colors">
                                Conoce más
                            </button>
                            <button class="border border-emerald-600 text-emerald-600 hover:bg-emerald-50 py-3 px-6 rounded-md text-lg transition-colors">
                                Solicitar información
                            </button>
                        </div>
                    </div>
                    <div class="relative">
                        <img
                            src="https://via.placeholder.com/600x500"
                            alt="Estudiantes de la Institución Educativa Hispanoamericana"
                            class="rounded-lg shadow-2xl w-full"
                        />
                    </div>
                </div>
            </div>
        </section>

        <!-- Stats Section -->
        <section class="py-16 bg-white">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="grid grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center">
                        <div class="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">38+</div>
                        <p class="text-gray-600">Años de experiencia</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">1,200+</div>
                        <p class="text-gray-600">Estudiantes activos</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">95%</div>
                        <p class="text-gray-600">Tasa de graduación</p>
                    </div>
                    <div class="text-center">
                        <div class="text-3xl lg:text-4xl font-bold text-emerald-600 mb-2">50+</div>
                        <p class="text-gray-600">Docentes calificados</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Section -->
        <section id="nosotros" class="py-20 bg-gray-50">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="grid lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <img
                            src="https://via.placeholder.com/500x400"
                            alt="Campus de la institución"
                            class="rounded-lg shadow-lg w-full"
                        />
                    </div>
                    <div class="space-y-6">
                        <h2 class="text-3xl lg:text-4xl font-bold text-gray-900">Nuestra Historia y Misión</h2>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            Fundada en 1985, la Institución Educativa Hispanoamericana ha sido pionera en brindar educación de
                            calidad que trasciende las fronteras tradicionales del aprendizaje.
                        </p>
                        <div class="space-y-4">
                            <div class="flex items-start space-x-3">
                                <i data-lucide="award" class="h-6 w-6 text-emerald-600 mt-1"></i>
                                <div>
                                    <h3 class="font-semibold text-gray-900">Excelencia Académica</h3>
                                    <p class="text-gray-600">Programas educativos reconocidos a nivel nacional</p>
                                </div>
                            </div>
                            <div class="flex items-start space-x-3">
                                <i data-lucide="users" class="h-6 w-6 text-emerald-600 mt-1"></i>
                                <div>
                                    <h3 class="font-semibold text-gray-900">Comunidad Diversa</h3>
                                    <p class="text-gray-600">Estudiantes de diferentes culturas y backgrounds</p>
                                </div>
                            </div>
                            <div class="flex items-start space-x-3">
                                <i data-lucide="globe" class="h-6 w-6 text-emerald-600 mt-1"></i>
                                <div>
                                    <h3 class="font-semibold text-gray-900">Perspectiva Global</h3>
                                    <p class="text-gray-600">Preparamos ciudadanos del mundo</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Programs Section -->
        <section id="programas" class="py-20 bg-white">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="text-center mb-16">
                    <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">Nuestros Programas Académicos</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Ofrecemos una amplia gama de programas diseñados para desarrollar el potencial completo de cada
                        estudiante
                    </p>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm hover:shadow-lg transition-shadow p-6">
                        <div class="mb-6">
                            <i data-lucide="book-open" class="h-12 w-12 text-emerald-600 mb-4"></i>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Educación Primaria</h3>
                            <p class="text-gray-600">Fundamentos sólidos para el desarrollo integral de los más pequeños</p>
                        </div>
                        <div class="space-y-2 text-sm text-gray-600">
                            <p>• Metodología lúdica y participativa</p>
                            <p>• Desarrollo de habilidades básicas</p>
                            <p>• Formación en valores</p>
                            <p>• Actividades extracurriculares</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm hover:shadow-lg transition-shadow p-6">
                        <div class="mb-6">
                            <i data-lucide="users" class="h-12 w-12 text-emerald-600 mb-4"></i>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Educación Secundaria</h3>
                            <p class="text-gray-600">Preparación integral para la vida universitaria y profesional</p>
                        </div>
                        <div class="space-y-2 text-sm text-gray-600">
                            <p>• Bachillerato académico</p>
                            <p>• Énfasis en ciencias y humanidades</p>
                            <p>• Preparación para pruebas ICFES</p>
                            <p>• Orientación vocacional</p>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm hover:shadow-lg transition-shadow p-6">
                        <div class="mb-6">
                            <i data-lucide="award" class="h-12 w-12 text-emerald-600 mb-4"></i>
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Programas Especiales</h3>
                            <p class="text-gray-600">Actividades complementarias para el desarrollo integral</p>
                        </div>
                        <div class="space-y-2 text-sm text-gray-600">
                            <p>• Bilingüismo (Inglés-Español)</p>
                            <p>• Deportes y recreación</p>
                            <p>• Arte y cultura</p>
                            <p>• Tecnología e innovación</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Facilities Section -->
        <section id="instalaciones" class="py-20 bg-gray-50">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="text-center mb-16">
                    <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">Nuestras Instalaciones</h2>
                    <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                        Espacios modernos y equipados para brindar la mejor experiencia educativa
                    </p>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="relative group">
                        <img
                            src="https://via.placeholder.com/400x250"
                            alt="Aulas modernas"
                            class="rounded-lg shadow-md group-hover:shadow-lg transition-shadow w-full"
                        />
                        <div class="absolute inset-0 bg-black bg-opacity-40 rounded-lg flex items-end p-6">
                            <div class="text-white">
                                <h3 class="text-xl font-semibold mb-2">Aulas Inteligentes</h3>
                                <p class="text-sm">Equipadas con tecnología de punta</p>
                            </div>
                        </div>
                    </div>
                    <div class="relative group">
                        <img
                            src="https://via.placeholder.com/400x250"
                            alt="Laboratorios"
                            class="rounded-lg shadow-md group-hover:shadow-lg transition-shadow w-full"
                        />
                        <div class="absolute inset-0 bg-black bg-opacity-40 rounded-lg flex items-end p-6">
                            <div class="text-white">
                                <h3 class="text-xl font-semibold mb-2">Laboratorios</h3>
                                <p class="text-sm">Ciencias, informática y idiomas</p>
                            </div>
                        </div>
                    </div>
                    <div class="relative group">
                        <img
                            src="https://via.placeholder.com/400x250"
                            alt="Biblioteca"
                            class="rounded-lg shadow-md group-hover:shadow-lg transition-shadow w-full"
                        />
                        <div class="absolute inset-0 bg-black bg-opacity-40 rounded-lg flex items-end p-6">
                            <div class="text-white">
                                <h3 class="text-xl font-semibold mb-2">Biblioteca</h3>
                                <p class="text-sm">Amplio acervo bibliográfico</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section class="py-20 bg-white">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="text-center mb-16">
                    <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-4">Lo que dicen nuestras familias</h2>
                </div>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm p-6">
                        <div class="flex items-center mb-4">
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                        </div>
                        <p class="text-gray-600 mb-4">
                            "La educación que recibe mi hija en Hispanoamericana es excepcional. Los maestros son dedicados y el
                            ambiente es muy acogedor."
                        </p>
                        <div class="flex items-center">
                            <div class="w-10 h-10 bg-emerald-100 rounded-full flex items-center justify-center mr-3">
                                <span class="text-emerald-600 font-semibold">MG</span>
                            </div>
                            <div>
                                <p class="font-semibold text-gray-900">María González</p>
                                <p class="text-sm text-gray-600">Madre de familia</p>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm p-6">
                        <div class="flex items-center mb-4">
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                        </div>
                        <p class="text-gray-600 mb-4">
                            "Mis hijos han desarrollado no solo conocimientos académicos, sino también valores y habilidades
                            para la vida."
                        </p>
                        <div class="flex items-center">
                            <div class="w-10 h-10 bg-emerald-100 rounded-full flex items-center justify-center mr-3">
                                <span class="text-emerald-600 font-semibold">CR</span>
                            </div>
                            <div>
                                <p class="font-semibold text-gray-900">Carlos Rodríguez</p>
                                <p class="text-sm text-gray-600">Padre de familia</p>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm p-6">
                        <div class="flex items-center mb-4">
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                            <i data-lucide="star" class="h-5 w-5 text-yellow-400 fill-current"></i>
                        </div>
                        <p class="text-gray-600 mb-4">
                            "La preparación que recibí me permitió ingresar a la universidad de mis sueños. Siempre estaré
                            agradecida."
                        </p>
                        <div class="flex items-center">
                            <div class="w-10 h-10 bg-emerald-100 rounded-full flex items-center justify-center mr-3">
                                <span class="text-emerald-600 font-semibold">AS</span>
                            </div>
                            <div>
                                <p class="font-semibold text-gray-900">Ana Sofía</p>
                                <p class="text-sm text-gray-600">Egresada 2023</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contacto" class="py-20 bg-emerald-50">
            <div class="container mx-auto px-4 lg:px-6">
                <div class="grid lg:grid-cols-2 gap-12">
                    <div>
                        <h2 class="text-3xl lg:text-4xl font-bold text-gray-900 mb-6">Contáctanos</h2>
                        <p class="text-lg text-gray-600 mb-8">
                            Estamos aquí para resolver todas tus dudas y acompañarte en el proceso de admisión. ¡Contáctanos hoy
                            mismo!
                        </p>

                        <div class="space-y-6">
                            <div class="flex items-center space-x-4">
                                <i data-lucide="map-pin" class="h-6 w-6 text-emerald-600"></i>
                                <div>
                                    <p class="font-semibold text-gray-900">Dirección</p>
                                    <p class="text-gray-600">Calle 123 #45-67, Bogotá, Colombia</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-4">
                                <i data-lucide="phone" class="h-6 w-6 text-emerald-600"></i>
                                <div>
                                    <p class="font-semibold text-gray-900">Teléfono</p>
                                    <p class="text-gray-600">+57 (1) 234-5678</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-4">
                                <i data-lucide="mail" class="h-6 w-6 text-emerald-600"></i>
                                <div>
                                    <p class="font-semibold text-gray-900">Email</p>
                                    <p class="text-gray-600">info@hispanoamericana.edu.co</p>
                                </div>
                            </div>
                            <div class="flex items-center space-x-4">
                                <i data-lucide="clock" class="h-6 w-6 text-emerald-600"></i>
                                <div>
                                    <p class="font-semibold text-gray-900">Horario de atención</p>
                                    <p class="text-gray-600">Lunes a Viernes: 7:00 AM - 5:00 PM</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white rounded-lg border border-gray-200 shadow-sm p-6">
                        <div class="mb-6">
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Solicitar Información</h3>
                            <p class="text-gray-600">Completa el formulario y nos pondremos en contacto contigo</p>
                        </div>
                        <div class="space-y-4">
                            <div class="grid grid-cols-2 gap-4">
                                <div>
                                    <label class="text-sm font-medium text-gray-700 mb-2 block">Nombre</label>
                                    <input type="text" placeholder="Tu nombre" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-emerald-500">
                                </div>
                                <div>
                                    <label class="text-sm font-medium text-gray-700 mb-2 block">Apellido</label>
                                    <input type="text" placeholder="Tu apellido" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-emerald-500">
                                </div>
                            </div>
                            <div>
                                <label class="text-sm font-medium text-gray-700 mb-2 block">Email</label>
                                <input type="email" placeholder="tu@email.com" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-emerald-500">
                            </div>
                            <div>
                                <label class="text-sm font-medium text-gray-700 mb-2 block">Teléfono</label>
                                <input type="tel" placeholder="Tu número de teléfono" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-emerald-500">
                            </div>
                            <div>
                                <label class="text-sm font-medium text-gray-700 mb-2 block">Mensaje</label>
                                <textarea placeholder="Cuéntanos en qué podemos ayudarte..." rows="4" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-emerald-500"></textarea>
                            </div>
                            <button class="w-full bg-emerald-600 hover:bg-emerald-700 text-white py-3 px-6 rounded-md transition-colors">Enviar mensaje</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="container mx-auto px-4 lg:px-6">
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i data-lucide="graduation-cap" class="h-8 w-8 text-emerald-400"></i>
                        <div>
                            <h3 class="text-lg font-bold">Institución Educativa</h3>
                            <p class="text-emerald-400 font-medium">Hispanoamericana</p>
                        </div>
                    </div>
                    <p class="text-gray-400 text-sm">
                        Formando líderes del futuro con excelencia académica y valores sólidos.
                    </p>
                </div>

                <div>
                    <h4 class="font-semibold mb-4">Enlaces rápidos</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li>
                            <a href="#inicio" class="hover:text-emerald-400 transition-colors">
                                Inicio
                            </a>
                        </li>
                        <li>
                            <a href="#nosotros" class="hover:text-emerald-400 transition-colors">
                                Nosotros
                            </a>
                        </li>
                        <li>
                            <a href="#programas" class="hover:text-emerald-400 transition-colors">
                                Programas
                            </a>
                        </li>
                        <li>
                            <a href="#contacto" class="hover:text-emerald-400 transition-colors">
                                Contacto
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-semibold mb-4">Programas</h4>
                    <ul class="space-y-2 text-sm text-gray-400">
                        <li>Educación Primaria</li>
                        <li>Educación Secundaria</li>
                        <li>Bilingüismo</li>
                        <li>Actividades Extracurriculares</li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-semibold mb-4">Contacto</h4>
                    <div class="space-y-2 text-sm text-gray-400">
                        <p>Calle 123 #45-67</p>
                        <p>Bogotá, Colombia</p>
                        <p>+57 (1) 234-5678</p>
                        <p>info@hispanoamericana.edu.co</p>
                    </div>
                </div>
            </div>

            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-sm text-gray-400">
                <p>
                    &copy; <span id="current-year"></span> Institución Educativa Hispanoamericana. Todos los derechos reservados.
                </p>
            </div>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();
        
        // Set current year in footer
        document.getElementById('current-year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
