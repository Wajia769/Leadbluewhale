<!DOCTYPE html>
<html lang="es" class="smooth-scroll">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LeadBlueWhale - Soluciones de IA End-to-End que Transforman Negocios</title>
    <meta name="description" content="Agencia líder en soluciones de Inteligencia Artificial end-to-end. Desde estrategia hasta implementación. Automatización, IA conversacional, análisis predictivo y más.">
    <meta name="keywords" content="inteligencia artificial, IA, automatización, machine learning, soluciones IA, agencia IA, transformación digital">
    <meta name="robots" content="index, follow">
    <meta property="og:title" content="LeadBlueWhale - Soluciones de IA End-to-End">
    <meta property="og:description" content="Transformamos su negocio con soluciones de IA personalizadas. De la estrategia al resultado.">
    <meta property="og:type" content="website">
    
    <!-- External Libraries -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Custom Styles -->
    <style>
        /* Apply the main font */
        body { font-family: 'Inter', sans-serif; }
        
        /* Enable smooth scrolling via CSS */
        .smooth-scroll { scroll-behavior: smooth; }

        /* Custom gradient styles */
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .gradient-text { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        
        /* Animations */
        .hero-animation { animation: fadeInUp 1s ease-out; }
        .floating { animation: floating 3s ease-in-out infinite; }
        @keyframes fadeInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
        @keyframes floating { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-10px); } }

        /* Card hover effect */
        .card-hover { transition: all 0.3s ease; }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 20px 40px rgba(0,0,0,0.1); }
        
        /* Button styles */
        .btn-primary { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); transition: all 0.3s ease; }
        .btn-primary:hover { transform: translateY(-2px); box-shadow: 0 10px 25px rgba(102, 126, 234, 0.3); }

        /* Section fade-in effect */
        .section-fade { opacity: 0; transform: translateY(50px); transition: all 0.6s ease-out; }
        .section-fade.visible { opacity: 1; transform: translateY(0); }

        /* Stats counter style */
        .stats-counter { font-size: 2.5rem; font-weight: 800; color: #667eea; }
        
        /* Process steps connector line */
        .process-step { position: relative; }
        .process-step::after { content: ''; position: absolute; top: 50%; right: -25px; width: 50px; height: 2px; background: #667eea; z-index: 1; }
        .process-step:last-child::after { display: none; }

        /* Methodology timeline styles */
        .methodology-timeline { position: relative; }
        .methodology-timeline::before { content: ''; position: absolute; left: 50%; top: 0; bottom: 0; width: 3px; background: #667eea; transform: translateX(-50%); }
        .timeline-item { position: relative; margin: 2rem 0; }
        .timeline-item::before { content: ''; position: absolute; left: 50%; top: 20px; width: 15px; height: 15px; background: #667eea; border-radius: 50%; transform: translateX(-50%); z-index: 2; }
        .timeline-content { background: white; padding: 2rem; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        .timeline-left { margin-right: 50%; padding-right: 3rem; }
        .timeline-right { margin-left: 50%; padding-left: 3rem; }
        
        /* Mobile menu transition */
        .mobile-menu { transform: translateX(100%); transition: transform 0.3s ease-in-out; }
        .mobile-menu.active { transform: translateX(0); }

        /* Case study card style */
        .case-study-card { background: linear-gradient(135deg, #ffffff 0%, #f8fafc 100%); border-left: 4px solid #667eea; }
        .metric-highlight { color: #667eea; font-weight: 800; font-size: 1.5rem; }
        .ai-icon { color: #667eea; font-size: 3rem; margin-bottom: 1rem; }

        /* Responsive adjustments for timeline */
        @media (max-width: 768px) {
            .methodology-timeline::before { left: 20px; }
            .timeline-item::before { left: 20px; }
            .timeline-left, .timeline-right { margin: 0; padding: 0; padding-left: 3rem; }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <!-- Navigation -->
    <nav class="fixed w-full bg-white/95 backdrop-blur-sm shadow-lg z-50">
        <div class="container mx-auto px-4 py-4">
            <div class="flex justify-between items-center">
                <a href="#inicio" class="flex items-center space-x-3">
                    <!-- Inlined SVG Logo for performance and clarity -->
                    <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-10 w-10">
                        <path d="M20 5L30 25H10L20 5Z" fill="#667eea"/>
                        <path d="M15 20C15 20 20 25 20 25S25 20 25 20" stroke="#764ba2" stroke-width="2"/>
                    </svg>
                    <span class="text-2xl font-bold gradient-text">LeadBlueWhale</span>
                </a>
                <div class="hidden md:flex space-x-8">
                    <a href="#inicio" class="text-gray-600 hover:text-blue-600 transition-colors">Inicio</a>
                    <a href="#soluciones" class="text-gray-600 hover:text-blue-600 transition-colors">Soluciones</a>
                    <a href="#metodologia" class="text-gray-600 hover:text-blue-600 transition-colors">Metodología</a>
                    <a href="#casos" class="text-gray-600 hover:text-blue-600 transition-colors">Casos de Éxito</a>
                    <a href="#contacto" class="text-gray-600 hover:text-blue-600 transition-colors">Contacto</a>
                </div>
                <div class="hidden md:block">
                    <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="btn-primary text-white px-6 py-3 rounded-lg font-semibold">
                        Solicitar Evaluación
                    </a>
                </div>
                <button id="mobile-menu-btn" class="md:hidden text-gray-600">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="mobile-menu fixed top-0 right-0 w-full h-full bg-white shadow-lg md:hidden">
            <div class="p-4 text-right">
                <button id="close-menu" class="text-gray-600">
                    <i class="fas fa-times text-2xl"></i>
                </button>
            </div>
            <div class="mt-8 flex flex-col items-center space-y-6">
                <a href="#inicio" class="block text-gray-600 hover:text-blue-600 text-lg">Inicio</a>
                <a href="#soluciones" class="block text-gray-600 hover:text-blue-600 text-lg">Soluciones</a>
                <a href="#metodologia" class="block text-gray-600 hover:text-blue-600 text-lg">Metodología</a>
                <a href="#casos" class="block text-gray-600 hover:text-blue-600 text-lg">Casos de Éxito</a>
                <a href="#contacto" class="block text-gray-600 hover:text-blue-600 text-lg">Contacto</a>
                <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="block btn-primary text-white px-6 py-3 rounded-lg font-semibold text-center mt-8">
                    Solicitar Evaluación
                </a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="pt-28 pb-12 gradient-bg text-white">
        <div class="container mx-auto px-4">
            <div class="hero-animation text-center max-w-4xl mx-auto">
                <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">
                    Soluciones de IA que <span class="text-yellow-300">Impulsan</span> su Negocio
                </h1>
                <p class="text-xl md:text-2xl mb-8 text-gray-100 leading-relaxed">
                    Diseñamos, construimos y desplegamos tecnología de Inteligencia Artificial a medida para resolver sus desafíos más complejos. <strong>De la Estrategia al Resultado.</strong>
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
                    <a href="#soluciones" class="bg-white text-blue-600 px-8 py-4 rounded-lg font-semibold text-lg hover:bg-gray-100 transition-colors">
                        <i class="fas fa-rocket mr-2"></i>Ver Nuestras Soluciones
                    </a>
                    <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="border-2 border-white text-white px-8 py-4 rounded-lg font-semibold text-lg hover:bg-white hover:text-blue-600 transition-colors">
                        <i class="fas fa-calendar-check mr-2"></i>Solicitar Evaluación
                    </a>
                </div>
            </div>
        </div>
        <div class="mt-16 text-center">
            <a href="#confianza" aria-label="Scroll down">
                <div class="floating">
                    <i class="fas fa-chevron-down text-white text-2xl"></i>
                </div>
            </a>
        </div>
    </section>

    <!-- Trust Indicators -->
    <section id="confianza" class="py-12 bg-white">
        <div class="container mx-auto px-4">
            <div class="flex flex-wrap justify-center items-center gap-y-8 gap-x-12">
                <div class="text-center">
                    <div class="stats-counter">98%</div>
                    <p class="text-gray-600">Satisfacción del Cliente</p>
                </div>
                <div class="text-center">
                    <div class="stats-counter">50+</div>
                    <p class="text-gray-600">Proyectos Completados</p>
                </div>
                <div class="text-center">
                    <div class="stats-counter">3x</div>
                    <p class="text-gray-600">ROI Promedio</p>
                </div>
                <div class="text-center">
                    <div class="stats-counter">24/7</div>
                    <p class="text-gray-600">Soporte Técnico</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Our Approach Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="section-fade max-w-4xl mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-800">
                    El Éxito en la IA no es Magia, <span class="gradient-text">es un Proceso</span>
                </h2>
                <div class="bg-white rounded-2xl shadow-xl p-8 md:p-12">
                    <p class="text-lg md:text-xl text-gray-700 leading-relaxed mb-8">
                        En LeadBlueWhale, hemos perfeccionado un enfoque integral que <strong>garantiza el éxito</strong>. No escribimos una sola línea de código sin antes construir un caso de negocio sólido y una hoja de ruta clara. Cada solución que construimos está diseñada para generar un <strong>impacto medible</strong> en sus objetivos.
                    </p>
                    <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mt-12">
                        <div class="process-step text-center">
                            <div class="ai-icon"><i class="fas fa-search"></i></div>
                            <h3 class="font-semibold text-lg mb-2">Descubrimiento</h3>
                            <p class="text-gray-600">Análisis profundo de sus necesidades</p>
                        </div>
                        <div class="process-step text-center">
                            <div class="ai-icon"><i class="fas fa-lightbulb"></i></div>
                            <h3 class="font-semibold text-lg mb-2">Estrategia</h3>
                            <p class="text-gray-600">Hoja de ruta técnica y de negocio</p>
                        </div>
                        <div class="process-step text-center">
                            <div class="ai-icon"><i class="fas fa-cogs"></i></div>
                            <h3 class="font-semibold text-lg mb-2">Desarrollo</h3>
                            <p class="text-gray-600">Construcción de soluciones robustas</p>
                        </div>
                        <div class="process-step text-center">
                            <div class="ai-icon"><i class="fas fa-chart-line"></i></div>
                            <h3 class="font-semibold text-lg mb-2">Optimización</h3>
                            <p class="text-gray-600">Mejora continua y resultados</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Solutions Section -->
    <section id="soluciones" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="section-fade text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-800">
                    Nuestras Soluciones de <span class="gradient-text">Ciclo Completo</span>
                </h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">
                    Desde la estrategia inicial hasta la optimización continua, cubrimos cada aspecto de su transformación con IA.
                </p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Solution Card 1 -->
                <div class="card-hover bg-white rounded-xl shadow-lg p-8 border-l-4 border-blue-500">
                    <div class="flex items-center mb-6"><i class="fas fa-brain text-blue-500 text-3xl mr-4"></i><h3 class="text-2xl font-bold text-gray-800">Descubrimiento y Estrategia de IA</h3></div>
                    <p class="text-gray-600 mb-6 leading-relaxed">Todo gran proyecto empieza con un gran plan. Auditamos sus procesos, identificamos oportunidades, definimos KPIs y creamos una hoja de ruta detallada para alinear la inversión con <strong>resultados reales</strong>.</p>
                    <div class="flex flex-wrap gap-2"><span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">Auditoría de Procesos</span><span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">Definición de KPIs</span><span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm">Hoja de Ruta</span></div>
                </div>
                <!-- Solution Card 2 -->
                <div class="card-hover bg-white rounded-xl shadow-lg p-8 border-l-4 border-purple-500">
                    <div class="flex items-center mb-6"><i class="fas fa-robot text-purple-500 text-3xl mr-4"></i><h3 class="text-2xl font-bold text-gray-800">Desarrollo e Implementación</h3></div>
                    <p class="text-gray-600 mb-6 leading-relaxed">Nuestro equipo de ingenieros convierte la estrategia en tecnología robusta y escalable. Nos especializamos en automatización, IA conversacional y análisis predictivo. <strong>Código limpio, arquitectura sólida</strong>.</p>
                    <div class="flex flex-wrap gap-2"><span class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm">Automatización</span><span class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm">IA Conversacional</span><span class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm">Machine Learning</span></div>
                </div>
                <!-- Solution Card 3 -->
                <div class="card-hover bg-white rounded-xl shadow-lg p-8 border-l-4 border-green-500">
                    <div class="flex items-center mb-6"><i class="fas fa-plug text-green-500 text-3xl mr-4"></i><h3 class="text-2xl font-bold text-gray-800">Integración de Sistemas</h3></div>
                    <p class="text-gray-600 mb-6 leading-relaxed">Integramos las soluciones de IA con sus sistemas existentes (CRM, ERP, etc.) para asegurar un flujo de trabajo sin fricciones y maximizar la adopción por parte de su equipo. <strong>Integración perfecta</strong>.</p>
                    <div class="flex flex-wrap gap-2"><span class="bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm">Integración CRM</span><span class="bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm">Sistemas ERP</span><span class="bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm">APIs Nativas</span></div>
                </div>
                <!-- Solution Card 4 -->
                <div class="card-hover bg-white rounded-xl shadow-lg p-8 border-l-4 border-orange-500">
                    <div class="flex items-center mb-6"><i class="fas fa-chart-line text-orange-500 text-3xl mr-4"></i><h3 class="text-2xl font-bold text-gray-800">Mantenimiento y Optimización</h3></div>
                    <p class="text-gray-600 mb-6 leading-relaxed">Una solución de IA no es estática. Ofrecemos planes de soporte y optimización para asegurar que sus modelos sigan rindiendo al máximo nivel a lo largo del tiempo. <strong>Evolución constante</strong>.</p>
                    <div class="flex flex-wrap gap-2"><span class="bg-orange-100 text-orange-800 px-3 py-1 rounded-full text-sm">Monitoreo 24/7</span><span class="bg-orange-100 text-orange-800 px-3 py-1 rounded-full text-sm">Optimización de Modelos</span><span class="bg-orange-100 text-orange-800 px-3 py-1 rounded-full text-sm">Soporte Dedicado</span></div>
                </div>
            </div>
            <div class="text-center mt-12">
                <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="btn-primary text-white px-8 py-4 rounded-lg font-semibold text-lg">
                    <i class="fas fa-rocket mr-2"></i>Comenzar mi Transformación
                </a>
            </div>
        </div>
    </section>

    <!-- Methodology Section -->
    <section id="metodologia" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="section-fade text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-800">Nuestro <span class="gradient-text">Proceso Probado</span></h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Un enfoque sistemático que garantiza resultados excepcionales en cada proyecto.</p>
            </div>
            <div class="methodology-timeline max-w-4xl mx-auto">
                <!-- Timeline Item 1 -->
                <div class="timeline-item"><div class="timeline-content timeline-left"><div class="flex items-center mb-4"><i class="fas fa-search text-blue-500 text-2xl mr-3"></i><h3 class="text-xl font-bold text-gray-800">Fase 1: Descubrimiento y Estrategia</h3></div><p class="text-gray-600">Análisis profundo de sus procesos, identificación de oportunidades y definición de objetivos. Creamos un blueprint detallado que guía todo el proyecto.</p><div class="mt-4 text-blue-600 font-semibold"><i class="fas fa-clock mr-2"></i>2-3 semanas</div></div></div>
                <!-- Timeline Item 2 -->
                <div class="timeline-item"><div class="timeline-content timeline-right"><div class="flex items-center mb-4"><i class="fas fa-drafting-compass text-purple-500 text-2xl mr-3"></i><h3 class="text-xl font-bold text-gray-800">Fase 2: Diseño y Prototipado</h3></div><p class="text-gray-600">Diseñamos la arquitectura técnica y creamos prototipos funcionales para validar conceptos. Esto nos permite iterar rápidamente y asegurar que la solución cumple sus expectativas.</p><div class="mt-4 text-purple-600 font-semibold"><i class="fas fa-clock mr-2"></i>2-4 semanas</div></div></div>
                <!-- Timeline Item 3 -->
                <div class="timeline-item"><div class="timeline-content timeline-left"><div class="flex items-center mb-4"><i class="fas fa-code text-green-500 text-2xl mr-3"></i><h3 class="text-xl font-bold text-gray-800">Fase 3: Desarrollo Ágil</h3></div><p class="text-gray-600">Desarrollo iterativo con entregas frecuentes y feedback continuo. Usamos metodologías ágiles para asegurar transparencia y adaptabilidad.</p><div class="mt-4 text-green-600 font-semibold"><i class="fas fa-clock mr-2"></i>4-12 semanas</div></div></div>
                <!-- Timeline Item 4 -->
                <div class="timeline-item"><div class="timeline-content timeline-right"><div class="flex items-center mb-4"><i class="fas fa-rocket text-orange-500 text-2xl mr-3"></i><h3 class="text-xl font-bold text-gray-800">Fase 4: Despliegue y Soporte</h3></div><p class="text-gray-600">Lanzamiento controlado con formación completa de su equipo y soporte técnico. Monitoreamos el rendimiento y optimizamos para maximizar el ROI.</p><div class="mt-4 text-orange-600 font-semibold"><i class="fas fa-infinity mr-2"></i>Soporte continuo</div></div></div>
            </div>
        </div>
    </section>

    <!-- Case Studies Section -->
    <section id="casos" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="section-fade text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-800">Resultados que <span class="gradient-text">Hablan por Sí Mismos</span></h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Casos reales de transformación empresarial a través de soluciones de IA personalizadas.</p>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Case Study 1 -->
                <div class="case-study-card rounded-xl shadow-lg p-8"><div class="flex items-center mb-6"><i class="fas fa-truck text-blue-500 text-3xl mr-4"></i><div><h3 class="font-bold text-lg">Empresa Logística</h3><p class="text-gray-600">Automatización de Procesos</p></div></div><p class="text-gray-700 mb-6">Automatizamos el procesamiento de facturas mediante IA, reduciendo errores humanos y acelerando el flujo de trabajo.</p><div class="bg-blue-50 p-4 rounded-lg"><div class="metric-highlight">80%</div><p class="text-gray-600">Reducción en tiempo de procesamiento</p></div></div>
                <!-- Case Study 2 -->
                <div class="case-study-card rounded-xl shadow-lg p-8"><div class="flex items-center mb-6"><i class="fas fa-laptop-code text-purple-500 text-3xl mr-4"></i><div><h3 class="font-bold text-lg">Empresa SaaS</h3><p class="text-gray-600">Análisis Predictivo</p></div></div><p class="text-gray-700 mb-6">Implementamos un modelo predictivo para identificar clientes con riesgo de cancelación y personalizar estrategias de retención.</p><div class="bg-purple-50 p-4 rounded-lg"><div class="metric-highlight">35%</div><p class="text-gray-600">Aumento en retención de clientes</p></div></div>
                <!-- Case Study 3 -->
                <div class="case-study-card rounded-xl shadow-lg p-8"><div class="flex items-center mb-6"><i class="fas fa-store text-green-500 text-3xl mr-4"></i><div><h3 class="font-bold text-lg">Retail E-commerce</h3><p class="text-gray-600">IA Conversacional</p></div></div><p class="text-gray-700 mb-6">Desarrollamos un chatbot inteligente que maneja consultas de clientes 24/7, mejorando la experiencia del usuario.</p><div class="bg-green-50 p-4 rounded-lg"><div class="metric-highlight">60%</div><p class="text-gray-600">Reducción en tickets de soporte</p></div></div>
            </div>
            <div class="text-center mt-12">
                <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="btn-primary text-white px-8 py-4 rounded-lg font-semibold text-lg">
                    <i class="fas fa-comments mr-2"></i>Conversemos sobre su Proyecto
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-16 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="section-fade text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-gray-800">Inicie su <span class="gradient-text">Transformación</span></h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto">Conversemos sobre cómo la IA puede transformar su negocio. Nuestro equipo está listo para crear la solución perfecta para usted.</p>
            </div>
            <div class="max-w-4xl mx-auto">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                    <div class="bg-white rounded-2xl p-8 shadow-lg">
                        <h3 class="text-2xl font-bold mb-6 text-gray-800">¿Listo para comenzar?</h3>
                        <p class="text-gray-600 mb-8">Programe una consulta gratuita. Analizaremos su situación actual y le mostraremos las oportunidades de mejora con IA.</p>
                        <div class="space-y-6">
                            <div class="flex items-center"><i class="fas fa-calendar-check text-blue-500 text-xl mr-4"></i><div><h4 class="font-semibold">Consulta Gratuita</h4><p class="text-gray-600">45 minutos de análisis personalizado</p></div></div>
                            <div class="flex items-center"><i class="fas fa-chart-line text-purple-500 text-xl mr-4"></i><div><h4 class="font-semibold">Análisis de Oportunidades</h4><p class="text-gray-600">Identificamos áreas de mejora inmediata</p></div></div>
                            <div class="flex items-center"><i class="fas fa-road text-green-500 text-xl mr-4"></i><div><h4 class="font-semibold">Hoja de Ruta</h4><p class="text-gray-600">Plan estratégico personalizado</p></div></div>
                        </div>
                    </div>
                    <div class="bg-gradient-to-br from-blue-50 to-purple-50 rounded-2xl p-8">
                        <h3 class="text-2xl font-bold mb-6 text-gray-800">¿En qué fase se encuentra?</h3>
                        <div class="space-y-4">
                            <!-- Corrected: Replaced div with <a> tag for accessibility and semantics -->
                            <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="block bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                                <div class="flex items-center mb-4"><i class="fas fa-clipboard-check text-blue-500 text-2xl mr-4"></i><h4 class="font-semibold text-lg">Tengo un plan definido</h4></div>
                                <p class="text-gray-600 mb-4">Ya tengo requisitos claros y busco un equipo que pueda implementar mi visión de IA.</p>
                                <div class="text-blue-600 font-semibold"><i class="fas fa-arrow-right mr-2"></i>Programar Consulta Técnica</div>
                            </a>
                            <!-- Corrected: Replaced div with <a> tag for accessibility and semantics -->
                            <a href="https://app.flozy.com/#/bookings/invite-hdywye0aam41c5wrb" target="_blank" rel="noopener noreferrer" class="block bg-white p-6 rounded-lg shadow-md hover:shadow-lg transition-shadow">
                                <div class="flex items-center mb-4"><i class="fas fa-lightbulb text-purple-500 text-2xl mr-4"></i><h4 class="font-semibold text-lg">Tengo un objetivo de negocio</h4></div>
                                <p class="text-gray-600 mb-4">Sé qué quiero lograr pero necesito ayuda para definir la mejor estrategia y solución de IA.</p>
                                <div class="text-purple-600 font-semibold"><i class="fas fa-arrow-right mr-2"></i>Programar Consulta Estratégica</div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center space-x-3 mb-6">
                        <svg width="40" height="40" viewBox="0 0 40 40" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-8 w-8">
                            <path d="M20 5L30 25H10L20 5Z" fill="#667eea"/>
                            <path d="M15 20C15 20 20 25 20 25S25 20 25 20" stroke="#764ba2" stroke-width="2"/>
                        </svg>
                        <span class="text-xl font-bold">LeadBlueWhale</span>
                    </div>
                    <p class="text-gray-400 mb-6">Transformamos negocios con soluciones de IA personalizadas. Su socio tecnológico de confianza.</p>
                    <div class="flex space-x-4">
                        <a href="javascript:void(0);" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-linkedin text-xl"></i></a>
                        <a href="javascript:void(0);" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-twitter text-xl"></i></a>
                        <a href="javascript:void(0);" class="text-gray-400 hover:text-white transition-colors"><i class="fab fa-github text-xl"></i></a>
                    </div>
                </div>
                <div>
                    <h4 class="font-semibold text-lg mb-4">Servicios</h4>
                    <ul class="space-y-2">
                        <li><a href="#soluciones" class="text-gray-400 hover:text-white transition-colors">Estrategia de IA</a></li>
                        <li><a href="#soluciones" class="text-gray-400 hover:text-white transition-colors">Desarrollo Custom</a></li>
                        <li><a href="#soluciones" class="text-gray-400 hover:text-white transition-colors">Integración</a></li>
                        <li><a href="#soluciones" class="text-gray-400 hover:text-white transition-colors">Soporte y Optimización</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold text-lg mb-4">Recursos</h4>
                    <ul class="space-y-2">
                        <li><a href="#casos" class="text-gray-400 hover:text-white transition-colors">Casos de Éxito</a></li>
                        <li><a href="#metodologia" class="text-gray-400 hover:text-white transition-colors">Metodología</a></li>
                        <li><a href="javascript:void(0);" class="text-gray-400 hover:text-white transition-colors">Blog</a></li>
                        <li><a href="javascript:void(0);" class="text-gray-400 hover:text-white transition-colors">Documentación</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-semibold text-lg mb-4">Contacto</h4>
                    <address class="space-y-3 not-italic">
                        <p class="flex items-center"><i class="fas fa-envelope text-blue-400 mr-3"></i><span class="text-gray-400">info@leadbluewhale.com</span></p>
                        <p class="flex items-center"><i class="fas fa-phone text-blue-400 mr-3"></i><span class="text-gray-400">+1 (555) 123-4567</span></p>
                        <p class="flex items-center"><i class="fas fa-map-marker-alt text-blue-400 mr-3"></i><span class="text-gray-400">San Francisco, CA</span></p>
                    </address>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p class="text-gray-400">
                    © 2024 LeadBlueWhale. Todos los derechos reservados. | 
                    <a href="javascript:void(0);" class="hover:text-white transition-colors">Política de Privacidad</a> | 
                    <a href="javascript:void(0);" class="hover:text-white transition-colors">Términos de Servicio</a>
                </p>
            </div>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // --- Mobile Menu Functionality ---
            const mobileMenuBtn = document.getElementById('mobile-menu-btn');
            const closeMenuBtn = document.getElementById('close-menu');
            const mobileMenu = document.getElementById('mobile-menu');

            if (mobileMenuBtn && mobileMenu) {
                mobileMenuBtn.addEventListener('click', () => mobileMenu.classList.add('active'));
            }
            if (closeMenuBtn && mobileMenu) {
                closeMenuBtn.addEventListener('click', () => mobileMenu.classList.remove('active'));
            }
            // Close mobile menu when clicking on its links
            mobileMenu.querySelectorAll('a').forEach(link => {
                link.addEventListener('click', () => mobileMenu.classList.remove('active'));
            });

            // --- Intersection Observer for Fade-in Animations ---
            const observerOptions = {
                threshold: 0.1,
                rootMargin: '0px 0px -50px 0px'
            };
            const fadeInObserver = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('visible');
                        observer.unobserve(entry.target); // Stop observing once visible
                    }
                });
            }, observerOptions);
            document.querySelectorAll('.section-fade').forEach(section => {
                fadeInObserver.observe(section);
            });

            // --- Animate Counter Numbers on View ---
            function animateCounters() {
                const counters = document.querySelectorAll('.stats-counter');
                counters.forEach(counter => {
                    const target = parseInt(counter.textContent.replace(/[^0-9]/g, ''), 10);
                    const suffix = counter.textContent.replace(/[0-9]/g, '');
                    
                    // Prevent re-animation
                    if(counter.dataset.animated) return;
                    counter.dataset.animated = "true";

                    let count = 0;
                    const increment = Math.max(1, target / 100);
                    
                    const updateCounter = setInterval(() => {
                        count += increment;
                        if (count >= target) {
                            counter.textContent = target + suffix;
                            clearInterval(updateCounter);
                        } else {
                            counter.textContent = Math.floor(count) + suffix;
                        }
                    }, 20);
                });
            }

            const statsSection = document.getElementById('confianza');
            if (statsSection) {
                const statsObserver = new IntersectionObserver((entries, observer) => {
                    entries.forEach(entry => {
                        if (entry.isIntersecting) {
                            animateCounters();
                            observer.unobserve(entry.target); // Observe only once
                        }
                    });
                }, { threshold: 0.5 });
                statsObserver.observe(statsSection);
            }
        });
    </script>
</body>
</html>
