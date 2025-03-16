<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Limpieza Total - Servicios Profesionales</title>
    <style>
        /* Estilos CSS personalizados */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        /* Header */
        header {
            background: #2D3E50;
            padding: 20px;
            color: white;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 20px;
        }

        /* Sección Hero */
        .hero {
            background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://ejemplo.com/tu-imagen-de-fondo.jpg');
            background-size: cover;
            height: 80vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            padding: 20px;
        }

        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        /* Servicios */
        .servicios {
            padding: 50px 20px;
            background: #F5F5F5;
            text-align: center;
        }

        .servicios-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .servicio-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        /* Botones */
        .boton {
            background: #2ECC71;
            color: white;
            padding: 12px 30px;
            border-radius: 25px;
            text-decoration: none;
            display: inline-block;
            margin-top: 20px;
        }

        /* Footer */
        footer {
            background: #2D3E50;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="logo">Limpieza Total 🧼</div>
        <nav>
            <a href="#inicio">Inicio</a>
            <a href="#servicios">Servicios</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <!-- Sección Hero -->
    <section class="hero">
        <div>
            <h1>Transformamos tus espacios en lugares impecables</h1>
            <p>Servicios profesionales para hogares, vehículos y empresas</p>
            <a href="#contacto" class="boton">¡Solicita un Presupuesto!</a>
        </div>
    </section>

    <!-- Servicios -->
    <section class="servicios" id="servicios">
        <h2>Nuestros Servicios</h2>
        <div class="servicios-grid">
            <div class="servicio-card">
                <h3>🏠 Limpieza Residencial</h3>
                <p>Casas, apartamentos y más.</p>
            </div>
            <div class="servicio-card">
                <h3>🏢 Limpieza Comercial</h3>
                <p>Oficinas, edificios y locales.</p>
            </div>
            <div class="servicio-card">
                <h3>🚗 Limpieza de Autos</h3>
                <p>Interior y exterior profundo.</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>📞 Llámanos: +1 234 567 890</p>
        <p>📧 Email: contacto@limpiezatotal.com</p>
        <p>© 2024 Limpieza Total. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
