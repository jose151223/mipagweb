<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Camiones Reward Emmanuel</title>
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <header>
        <h1>Camiones: Potencia y Versatilidad</h1>
        <nav>
            <ul>
                <li><a href="#descripcion">Descripción</a></li>
                <li><a href="#tipos">Tipos de Camiones</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="descripcion">
        <h2>¿Qué es un camión?</h2>
        <p><strong>Los camiones</strong> son vehículos diseñados para el transporte de mercancías. Se caracterizan por su <em>gran capacidad de carga</em> y su versatilidad en diferentes terrenos y aplicaciones.</p>
    </section>

    <section id="tipos">
        <h2>Tipos de Camiones</h2>
        <ul>
            <li>Camión de carga pesada</li>
            <li>Camión de reparto</li>
            <li>Camión cisterna</li>
            <li>Camión volquete</li>
            <li>Camión frigorífico</li>
        </ul>
    </section>

    <section id="galeria">
        <h2>Nuestro vehiculo mas versatil</h2>
        <img src="img/nhr.img.jpg" alt="Camión de carga pesada" width="500">
        <video controls width="500">
            <source src="img/video.mp4.mp4" type="video/mp4">
            Tu navegador no soporta la reproducción de videos.
        </video>
    </section>

    <section id="informacion">
        <h2>Comparativa de Camiones</h2>
        <table>
            <thead>
                <tr>
                    <th>Modelo</th>
                    <th>Capacidad de Carga (toneladas)</th>
                    <th>Consumo (km/l)</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Camión NHR</td>
                    <td>10</td>
                    <td>5</td>
                </tr>
                <tr>
                    <td>Camión NPR</td>
                    <td>15</td>
                    <td>4.5</td>
                </tr>
                <tr>
                    <td>Camión FVR</td>
                    <td>20</td>
                    <td>4</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="contacto">
        <h2>Contáctanos</h2>
        <form action="#" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required><br><br>

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="mensaje">Mensaje:</label><br>
            <textarea id="mensaje" name="mensaje" rows="5"></textarea><br><br>

            <input type="submit" value="Enviar">
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Camiones S.A. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
