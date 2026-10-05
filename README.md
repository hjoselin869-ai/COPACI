<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sistema de Gestión Ciudadana - COPACI Granjas Guadalupe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- ==============================================
       ENCABEZADO PRINCIPAL
       ============================================== -->
    <header>
        <div class="contenedor-encabezado">
            <h1>🏛️ Sistema de Gestión Ciudadana</h1>
            <p class="subtitulo">COPACI de Granjas Guadalupe 💜</p>
        </div>
    </header>

    <!-- ==============================================
       BARRA DE NAVEGACIÓN — AHORA FUNCIONAL
       Cada enlace llama a la función para mostrar su pantalla
       ============================================== -->
    <nav>
        <ul>
            <li><a href="#" onclick="mostrarPantalla('inicio'); return false">🏠 Inicio</a></li>
            <li><a href="#" onclick="mostrarPantalla('tramites'); return false">📋 Trámites y Servicios</a></li>
            <li><a href="#" onclick="mostrarPantalla('avisos'); return false">📢 Avisos Importantes</a></li>
            <li><a href="#" onclick="mostrarPantalla('nosotros'); return false">👥 Sobre Nosotros</a></li>
            <li><a href="#" onclick="mostrarPantalla('contacto'); return false">📞 Contacto</a></li>
        </ul>
    </nav>

    <!-- ==============================================
       PANTALLA: INICIO
       ============================================== -->
    <main id="inicio" class="pantalla activa">
        <section class="seccion">
            <h2>✨ Bienvenido a tu Plataforma de Gestión</h2>
            <p>Este es el espacio oficial del COPACI de Granjas Guadalupe, donde podrás consultar información, realizar trámites y mantenerte informado sobre las acciones de nuestra comunidad 💜.</p>
            <img src="gobierno-ciudadano.jpg" alt="Gestión ciudadana" class="imagen-principal">
            <p>Trabajamos juntos por un mejor entorno para todos 💜.</p>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: TRÁMITES Y SERVICIOS
       Incluye los 3 botones que también funcionan
       ============================================== -->
    <main id="tramites" class="pantalla">
        <section class="seccion">
            <h2>📋 Trámites y Servicios Disponibles</h2>
            <p>Aquí puedes conocer los servicios que ofrecemos a la ciudadanía:</p>
            
            <div class="contenedor-tarjetas">
                <article class="tarjeta">
                    <h3>📄 Registro de Ciudadanos</h3>
                    <p>Actualización y consulta de datos del padrón comunitario.</p>
                    <button class="boton" onclick="mostrarPantalla('registro')">Saber más →</button>
                </article>

                <article class="tarjeta">
                    <h3>🛠️ Solicitud de Servicios</h3>
                    <p>Reportes de mantenimiento, limpieza y mejoras en espacios públicos.</p>
                    <button class="boton" onclick="mostrarPantalla('solicitud')">Solicitar →</button>
                </article>

                <article class="tarjeta">
                    <h3>📊 Transparencia</h3>
                    <p>Consulta de informes, presupuestos y avances de obras.</p>
                    <button class="boton" onclick="mostrarPantalla('transparencia')">Consultar →</button>
                </article>
            </div>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: REGISTRO DE CIUDADANOS
       ============================================== -->
    <main id="registro" class="pantalla">
        <section class="seccion">
            <h2>📄 Registro de Ciudadanos</h2>
            <p>En esta sección podrás actualizar y consultar tus datos del padrón comunitario.</p>
            <ul>
                <li>✅ Actualización de datos personales</li>
                <li>✅ Consulta de inscripción vigente</li>
                <li>✅ Constancia de residencia</li>
            </ul>
            <button class="boton" onclick="mostrarPantalla('tramites')">← Volver a Trámites</button>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: SOLICITUD DE SERVICIOS
       ============================================== -->
    <main id="solicitud" class="pantalla">
        <section class="seccion">
            <h2>🛠️ Solicitud de Servicios</h2>
            <p>Reporta o solicita atención en los espacios públicos de nuestra comunidad.</p>
            <ul>
                <li>🧹 Limpieza de áreas comunes</li>
                <li>🔧 Mantenimiento de alumbrado</li>
                <li>🌿 Mejoras en parques y jardines</li>
                <li>🚧 Reparación de calles</li>
            </ul>
            <button class="boton" onclick="mostrarPantalla('tramites')">← Volver a Trámites</button>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: TRANSPARENCIA
       ============================================== -->
    <main id="transparencia" class="pantalla">
        <section class="seccion">
            <h2>📊 Transparencia</h2>
            <p>Información clara y abierta sobre el manejo de recursos en nuestra comunidad.</p>
            <ul>
                <li>💰 Presupuesto anual asignado</li>
                <li>📑 Informes de egresos e ingresos</li>
                <li>🏗️ Avance de obras y proyectos</li>
                <li>📋 Actas de reuniones</li>
            </ul>
            <button class="boton" onclick="mostrarPantalla('tramites')">← Volver a Trámites</button>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: AVISOS IMPORTANTES
       ============================================== -->
    <main id="avisos" class="pantalla">
        <section class="seccion">
            <h2>📢 Avisos Importantes</h2>
            
            <aside class="aviso-destacado">
                <h3>⚠️ Atención Comunidad</h3>
                <p>Próxima reunión general: <strong>15 de octubre a las 18:00 hrs</strong> en el salón de usos múltiples 💜.</p>
            </aside>

            <ul class="lista-avisos">
                <li>✅ Inicio de obras de mantenimiento en calle principal — 05/10/2026</li>
                <li>✅ Entrega de apoyos alimentarios — 12/10/2026</li>
                <li>✅ Campaña de limpieza comunitaria — 18/10/2026</li>
            </ul>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: SOBRE NOSOTROS
       ============================================== -->
    <main id="nosotros" class="pantalla">
        <section class="seccion">
            <h2>👥 Sobre Nosotros</h2>
            <p>El COPACI de Granjas Guadalupe es el órgano de participación ciudadana que vigila, propone y colabora en el desarrollo de nuestra comunidad.</p>
            <p>Nuestra misión es servir con transparencia, cercanía y respeto a cada familia del territorio 💜.</p>
            <h3>🎯 Nuestros Valores</h3>
            <ul>
                <li>💜 Transparencia</li>
                <li>🤝 Participación</li>
                <li>❤️ Respeto</li>
                <li>⚡ Compromiso</li>
            </ul>
        </section>
    </main>

    <!-- ==============================================
       PANTALLA: CONTACTO
       ============================================== -->
    <main id="contacto" class="pantalla">
        <section class="seccion">
            <h2>📞 Contacto</h2>
            <p>¿Tienes dudas, propuestas o comentarios? Escríbenos:</p>
            
            <form class="formulario-contacto">
                <label>👤 Nombre completo:</label>
                <input type="text" name="nombre" required>

                <label>📧 Correo electrónico:</label>
                <input type="email" name="correo" required>

                <label>💬 Mensaje:</label>
                <textarea rows="4" name="mensaje" required></textarea>

                <button type="submit" class="boton">Enviar Mensaje ✉️</button>
            </form>
        </section>
    </main>

    <!-- ==============================================
       PIE DE PÁGINA
       ============================================== -->
    <footer>
        <p>© 2026 COPACI de Granjas Guadalupe — Sistema de Gestión Ciudadana 💜</p>
        <p>Todos los derechos reservados | Página oficial</p>
    </footer>

    <!-- ==============================================
       SCRIPT: Cambiar de pantalla
       Oculta todas y muestra solo la seleccionada
       ============================================== -->
    <script>
        function mostrarPantalla(idPantalla) {
            // Ocultar todas las pantallas
            document.querySelectorAll('.pantalla').forEach(pantalla => {
                pantalla.classList.remove('activa');
            });
            // Mostrar la pantalla elegida
            document.getElementById(idPantalla).classList.add('activa');
        }
    </script>

</body>
</html>