<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INTERA | Consultoría Estratégica en Automatización e IA</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { 
            background-color: #07090e; 
            color: #cbd5e1; 
            font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; 
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between selection:bg-slate-700 selection:text-white">

    <!-- HEADER EJECUTIVO -->
    <header class="w-full max-w-6xl mx-auto px-6 py-8 flex justify-between items-center border-b border-slate-800">
        <div class="flex items-center space-x-3">
            <span class="text-lg font-bold tracking-[0.25em] text-white">INTERA</span>
            <span class="w-1.5 h-1.5 bg-slate-400 rounded-full inline-block"></span>
        </div>
        <nav class="hidden md:flex items-center space-x-8 text-xs font-medium uppercase tracking-widest text-slate-400">
            <span class="text-slate-200">Diagnóstico Operativo B2B</span>
        </nav>
        <a href="#diagnostico" class="text-xs uppercase tracking-widest font-semibold text-slate-950 bg-slate-100 hover:bg-white px-5 py-2.5 rounded transition-all">
            Acceso a Evaluación
        </a>
    </header>

    <!-- HERO CORPORATIVO -->
    <main class="w-full max-w-4xl mx-auto px-6 py-24 text-center">
        <div class="text-[11px] font-mono uppercase tracking-[0.3em] text-slate-400 mb-6">
            Inteligencia Operativa &bull; México
        </div>
        <h1 class="text-3xl md:text-5xl font-light tracking-tight text-white mb-6 leading-tight">
            Ingeniería de procesos y automatización <br><span class="font-normal text-slate-200">para organizaciones industriales y corporativas</span>
        </h1>
        <p class="text-sm md:text-base text-slate-400 max-w-2xl mx-auto mb-12 font-normal leading-relaxed">
            Identificamos fricciones estructurales en flujos administrativos y logísticos. Desarrollamos arquitecturas de software e Inteligencia Artificial orientadas a la reducción de costos operativos y mitigación de errores humanos.
        </p>
        <div>
            <a href="#diagnostico" class="inline-block border border-slate-700 hover:border-slate-500 text-slate-200 font-medium px-8 py-3 rounded text-xs uppercase tracking-widest transition-all">
                Iniciar Evaluación Técnica
            </a>
        </div>
    </main>

    <!-- FORMULARIO INSTITUCIONAL -->
    <section id="diagnostico" class="w-full max-w-2xl mx-auto px-6 py-12 mb-24">
        <div class="bg-[#0b0f17] border border-slate-800 p-8 md:p-12 rounded-lg shadow-2xl">
            <div class="mb-10 border-b border-slate-800 pb-6">
                <h2 class="text-sm font-semibold text-white uppercase tracking-widest">Cuestionario de Diagnóstico Preliminar</h2>
                <p class="text-slate-400 text-xs mt-2 leading-relaxed">La información proporcionada permite a nuestro equipo técnico modelar el impacto financiero y el potencial de optimización previo a la sesión ejecutiva.</p>
            </div>
            
            <form action="https://formsubmit.co/tu-correo@empresa.com" method="POST" class="space-y-6">
                <!-- Datos Directivos -->
                <div class="grid md:grid-cols-2 gap-5">
                    <div>
                        <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">Nombre y Apellido</label>
                        <input type="text" name="nombre" required placeholder="Ej. Ing. Carlos Mendoza" class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                    </div>
                    <div>
                        <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">Razón Social o Empresa</label>
                        <input type="text" name="empresa" required placeholder="Ej. Manufacturas del Norte S.A." class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                    </div>
                </div>

                <div class="grid md:grid-cols-2 gap-5">
                    <div>
                        <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">Correo Corporativo</label>
                        <input type="email" name="email" required placeholder="carlos.mendoza@empresa.com" class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                    </div>
                    <div>
                        <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">Teléfono Directo</label>
                        <input type="text" name="telefono" required placeholder="+52 (477) 000 0000" class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                    </div>
                </div>

                <!-- Métricas Operativas -->
                <div class="border-t border-slate-800/80 pt-6 space-y-5">
                    <div class="text-[11px] font-semibold text-slate-300 uppercase tracking-widest">Parámetros Operativos del Proceso</div>
                    
                    <div>
                        <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">1. Área o cuello de botella principal</label>
                        <input type="text" name="area_problema" placeholder="Ej. Facturación, control de inventario, conciliación bancaria..." required class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                    </div>

                    <div class="grid md:grid-cols-2 gap-5">
                        <div>
                            <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">2. Volumen transaccional mensual</label>
                            <input type="text" name="volumen_transaccional" placeholder="Ej. 1,500 documentos/mes" required class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                        </div>
                        <div>
                            <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">3. Horas/hombre invertidas semanalmente</label>
                            <input type="text" name="horas_perdidas" placeholder="Ej. 40 horas semanales" required class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                        </div>
                    </div>

                    <div class="grid md:grid-cols-2 gap-5">
                        <div>
                            <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">4. Personal asignado al flujo</label>
                            <input type="text" name="personas_involucradas" placeholder="Ej. 5 operadores/administrativos" required class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                        </div>
                        <div>
                            <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">5. Margen estimado de error o incidencias</label>
                            <input type="text" name="margen_error" placeholder="Ej. 5% a 8% de errores manuales" required class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                        </div>
                    </div>

                    <div>
                        <label class="block text-[11px] uppercase tracking-widest font-medium text-slate-400 mb-2">6. Infraestructura de software actual</label>
                        <input type="text" name="herramientas_actuales" placeholder="Ej. Excel, correo electrónico, SAP Business One..." required class="w-full bg-[#07090e] border border-slate-800 rounded px-4 py-3 text-slate-200 text-xs focus:outline-none focus:border-slate-500">
                    </div>
                </div>

                <!-- ACCIÓN -->
                <div class="pt-6 border-t border-slate-800">
                    <button type="submit" class="w-full bg-slate-200 hover:bg-white text-slate-950 font-semibold uppercase tracking-widest text-xs py-3.5 rounded transition-all">
                        Transmitir Información para Análisis
                    </button>
                    <p class="text-[10px] text-slate-500 text-center mt-3 tracking-wide">Confidencialidad absoluta regulada bajo acuerdo de no divulgación estándar (NDA).</p>
                </div>
            </form>
        </div>
    </section>

    <!-- FOOTER -->
    <footer class="w-full max-w-6xl mx-auto px-6 py-8 border-t border-slate-800 flex flex-col sm:flex-row justify-between items-center text-slate-500 text-xs">
        <div class="flex items-center space-x-2 mb-4 sm:mb-0">
            <span class="font-bold tracking-widest text-slate-300">INTERA</span><span class="w-1.5 h-1.5 bg-slate-500 rounded-full inline-block"></span>
            <span>— Consultoría B2B en Automatización e Inteligencia Artificial</span>
        </div>
        <div class="text-[11px]">&copy; 2026 INTERA. Todos los derechos reservados.</div>
    </footer>

</body>
</html>
