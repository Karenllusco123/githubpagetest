# githubpagetest
github page
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Página sobre perfumes de alta calidad. Encuentra tu fragancia favorita aquí.">
    <meta name="author" content="Tu Nombre o Marca">
    <title>Perfumes Exclusivos</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link a un archivo de estilo CSS si tienes uno -->
    <link rel="icon" href="favicon.ico"> <!-- Icono de la página -->
</head>
<body>
    <!-- Header o cabecera -->
    <header>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#acerca">Acerca de</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <!-- Sección de bienvenida -->
    <section id="inicio">
        <h1>Bienvenido a Perfumes Exclusivos</h1>
        <p>Descubre una selección única de perfumes de lujo para cada ocasión.</p>
        <img src="perfume-banner.jpg" alt="Perfumes exclusivos" width="100%">
    </section>

    <!-- Acerca de nosotros -->
    <section id="acerca">
        <h2>¿Quiénes somos?</h2>
        <p>Somos una tienda especializada en perfumes de alta calidad. Nuestra misión es ofrecer fragancias únicas que resalten tu personalidad.</p>
    </section>

    <!-- Sección de productos -->
    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="producto">
            <h3>Perfume Floral</h3>
            <img src="perfume1.jpg" alt="Perfume Floral" width="200">
            <p>Un aroma fresco y suave, ideal para el día a día.</p>
        </div>
        <div class="producto">
            <h3>Perfume Amaderado</h3>
            <img src="perfume2.jpg" alt="Perfume Amaderado" width="200">
            <p>Un toque de elegancia y sofisticación para ocasiones especiales.</p>
        </div>
        <div class="producto">
            <h3>Perfume Cítrico</h3>
            <img src="perfume3.jpg" alt="Perfume Cítrico" width="200">
            <p>Refrescante y energizante, perfecto para el verano.</p>
        </div>
    </section>

    <!-- Galería de imágenes -->
    <section id="galeria">
        <h2>Galería</h2>
        <div class="galeria">
            <img src="galeria1.jpg" alt="Galería Perfume 1">
            <img src="galeria2.jpg" alt="Galería Perfume 2">
            <img src="galeria3.jpg" alt="Galería Perfume 3">
        </div>
    </section>

    <!-- Formulario de contacto -->
    <section id="contacto">
        <h2>Contáctanos</h2>
        <form action="enviar-formulario.php" method="POST">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="4" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- Footer o pie de página -->
    <footer>
        <p>&copy; 2024 Perfumes Exclusivos. Todos los derechos reservados.</p>
        <p><a href="https://www.instagram.com/tu-perfume" target="_blank">Síguenos en Instagram</a></p>
    </footer>

    <!-- Script de JavaScript -->
    <script src="script.js"></script>
</body>
</html>
