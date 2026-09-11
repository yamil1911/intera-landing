<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INTERA | Auditoría de Automatización e IA para PYMES</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { 
            background-color: #0b0f19; 
            color: #f3f4f6; 
            font-family: system-ui, -apple-system, sans-serif; 
        }
        /* Estilo de fondo corporativo tipo malla tecnológica */
        .bg-grid-pattern {
            background-image: radial-gradient(rgba(6, 182, 212, 0.1) 1px, transparent 1px);
            background-size: 32px 32px;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col justify-between bg-grid-pattern">

    <!-- HEADER CON LOGOTIPO INTERA -->
    <header class="w-full max-w-6xl mx-auto px-6 py-6 flex justify-between items-center">
        <div class="flex items-center space-x-2">
            <span class="text-2xl font-black tracking-wider text-white">INTERA</span><span class="w-2.5 h-2.5 bg-cyan-400 rounded-full inline-block"></span>
        </div>
        <a href="#auditoria" class="bg-cyan-500 hover:bg-cyan-400 text-slate-950 font-semibold px-5 py-2.5 rounded-lg transition-all text-sm shadow-lg shadow-cyan-500/10">
            Solicitar Auditoría ($900 USD)
        </a>
    </header>

    <!-- HERO SECTION -->
    <main class="w-full max-w-5xl mx-auto px-6 py-16 text-center">
        <div class="inline-block bg-cyan-950/80 text-cyan-400 border border-cyan-800/80 text-xs font-medium px-4 py-1.5 rounded-full mb-6 tracking-wide">
            Consultoría B2B de Automatización e IA en México
        </div>
        <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight text-white mb-6 leading-tight">
            Descubre cuánto dinero pierdes <br><span class="text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500">en cuellos de botella operativos</span>
        </h1>
        <p class="text-lg md:text-xl text-slate-400 max-w-2xl mx-auto mb-10">
            Completa tu perfil operativo, realiza el pago de la auditoría y recibe un reporte financiero con el plan exacto para automatizar tu empresa mediante Inteligencia Artificial.
        </p>
        <div class="flex flex-col sm:flex-row justify-center gap-4">
            <a href="#auditoria" class="bg-cyan-500 hover:bg-cyan-400 text-slate-950 font-bold px-8 py-4 rounded-xl text-base transition-all shadow-xl shadow-cyan-500/20">
                Iniciar Diagnóstico y Auditoría ($900 USD)
            </a>
        </div>
    </main>

    <!-- SECCIÓN DE FORMULARIO DE AUDITORÍA Y PAGO -->
    <section id="auditoria" class="w-full max-w-2xl mx-auto px-6 py-16">
        <div class="bg-slate-900/90 border border-slate-800 p-8 md:p-10 rounded-3xl shadow-2xl backdrop-blur-sm">
            <div class="text-center mb-8">
                <span class="text-xs font-bold uppercase tracking-widest text-cyan-400">Paso Único</span>
                <h2 class="text-2xl font-bold text-white mt-1">Formulario de Auditoría Operativa</h2>
                <p class="text-slate-400 text-sm mt-2">Tus respuestas nos permitirán calcular el costo oculto en sueldos, el impacto de errores humanos y el flujo de automatización previo a nuestra sesión.</p>
            </div>
            
            <form id="auditForm" class="space-y-6">
                <!-- Datos de Contacto Directivo -->
                <div class="grid md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-medium text-slate-300 mb-1">Nombre del Directivo</label>
                        <input type="text" id="nombre" required placeholder="Ej. Carlos Mendoza" class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                    </div>
                    <div>
                        <label class="block text-xs font-medium text-slate-300 mb-1">Empresa</label>
                        <input type="text" id="empresa" required placeholder="Ej. Manufacturas del Bajío" class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                    </div>
                </div>

                <div class="grid md:grid-cols-2 gap-4">
                    <div>
                        <label class="block text-xs font-medium text-slate-300 mb-1">Correo Corporativo</label>
                        <input type="email" id="email" required placeholder="carlos@empresa.com" class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                    </div>
                    <div>
                        <label class="block text-xs font-medium text-slate-300 mb-1">Teléfono / WhatsApp</label>
                        <input type="text" id="telefono" required placeholder="477 000 0000" class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                    </div>
                </div>

                <!-- Bloque de Preguntas Clave para el Análisis Financiero -->
                <div class="border-t border-slate-800/80 pt-6 space-y-5">
                    <h3 class="text-xs font-bold text-cyan-400 uppercase tracking-wider">Métricas de Fricción Operativa</h3>
                    
                    <div>
                        <label class="block text-xs font-medium text-slate-300 mb-1">1. ¿Qué área o proceso consume más tiempo en tareas manuales y captura en Excel?</label>
                        <input type="text" id="area_problema" placeholder="Ej. Facturación, control de inventarios, reportes de logística..." required class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                    </div>

                    <div class="grid md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">2. Volumen mensual de documentos/transacciones</label>
                            <input type="text" id="volumen_transaccional" placeholder="Ej. 1,500 facturas/pedidos al mes" required class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                        </div>
                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">3. Horas semanales invertidas por el equipo</label>
                            <input type="text" id="horas_perdidas" placeholder="Ej. 35 horas semanales" required class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                        </div>
                    </div>

                    <div class="grid md:grid-cols-2 gap-4">
                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">4. ¿Cuántas personas participan en este proceso?</label>
                            <input type="text" id="personas_involucradas" placeholder="Ej. 4 personas" required class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                        </div>
                        <div>
                            <label class="block text-xs font-medium text-slate-300 mb-1">5. Margen de error o retrabajos estimados</label>
                            <input type="text" id="margen_error" placeholder="Ej. 8% de errores o devoluciones" required class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                        </div>
                    </div>

                    <div>
                        <label class="block text-xs font-medium text-slate-300 mb-1">6. ¿Qué software, ERP o herramientas utilizan actualmente?</label>
                        <input type="text" id="herramientas_actuales" placeholder="Ej. Excel avanzado, correo, SAP Business One básico..." required class="w-full bg-slate-950 border border-slate-800 rounded-lg px-4 py-3 text-white text-sm focus:outline-none focus:border-cyan-400">
                    </div>
                </div>

                <!-- CONTENEDOR DEL BOTÓN DE PAYPAL -->
                <div class="pt-6 border-t border-slate-800/80">
                    <div class="text-xs text-slate-300 mb-3 text-center font-medium">Inversión de la Auditoría: <span class="text-cyan-400 font-bold">$900 USD</span>. Completa los campos para habilitar el pago seguro:</div>
                    <div id="paypal-button-container"></div>
                </div>
            </form>
        </div>
    </section>

    <!-- FOOTER CON IDENTIDAD INTERA -->
    <footer class="w-full max-w-6xl mx-auto px-6 py-8 border-t border-slate-900 flex flex-col sm:flex-row justify-between items-center text-slate-500 text-xs">
        <div class="flex items-center space-x-2 mb-4 sm:mb-0">
            <span class="font-bold text-slate-400">INTERA</span><span class="w-2 h-2 bg-cyan-400 rounded-full inline-block"></span>
            <span>— Automatización e Inteligencia Artificial B2B</span>
        </div>
        <div>&copy; 2026 INTERA. Todos los derechos reservados.</div>
    </footer>

    <!-- SCRIPT DE PAYPAL Y RECOLECCIÓN DE DATOS -->
    <script src="https://www.paypal.com/sdk/js?client-id=sb&currency=USD"></script>
    <script>
        paypal.Buttons({
            onClick: function(data, actions) {
                const nombre = document.getElementById('nombre').value;
                const empresa = document.getElementById('empresa').value;
                const email = document.getElementById('email').value;
                const telefono = document.getElementById('telefono').value;
                const area = document.getElementById('area_problema').value;
                const volumen = document.getElementById('volumen_transaccional').value;
                const horas = document.getElementById('horas_perdidas').value;
                const personas = document.getElementById('personas_involucradas').value;
                const error = document.getElementById('margen_error').value;
                const herramientas = document.getElementById('herramientas_actuales').value;

                if (!nombre || !empresa || !email || !telefono || !area || !volumen || !horas || !personas || !error || !herramientas) {
                    alert('Por favor completa todas las preguntas del formulario antes de proceder al pago.');
                    return actions.reject();
                }
                return actions.resolve();
            },
            createOrder: function(data, actions) {
                return actions.order.create({
                    purchase_units: [{
                        amount: { value: '900.00' },
                        description: 'INTERA - AI Automation Audit ($900 USD)'
                    }]
                });
            },
            onApprove: function(data, actions) {
                return actions.order.capture().then(function(details) {
                    const auditData = {
                        payerName: details.payer.name.given_name,
                        payerEmail: details.payer.email_address,
                        nombre: document.getElementById('nombre').value,
                        empresa: document.getElementById('empresa').value,
                        email: document.getElementById('email').value,
                        telefono: document.getElementById('telefono').value,
                        area: document.getElementById('area_problema').value,
                        volumen: document.getElementById('volumen_transaccional').value,
                        horas: document.getElementById('horas_perdidas').value,
                        personas: document.getElementById('personas_involucradas').value,
                        error: document.getElementById('margen_error').value,
                        herramientas: document.getElementById('herramientas_actuales').value,
                        orderId: details.id,
                        fecha: new Date().toISOString()
                    };

                    // Registro de los datos listos para tu análisis en Excel
                    console.log("Datos de la auditoría pagada listos para reporte:", auditData);

                    alert('¡Pago exitoso y cuestionario registrado con éxito! Nos pondremos en contacto contigo en menos de 24 horas con tu reporte financiero y mapa de automatización.');
                    document.getElementById('auditForm').reset();
                });
            }
        }).render('#paypal-button-container');
    </script>

</body>
</html>
