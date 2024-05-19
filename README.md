<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FashionMagic - Tienda de Moda</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>FashionMagic</h1>
            <nav>
                <ul>
                    <li><a href="#inicio">Inicio</a></li>
                    <li><a href="#productos">Productos</a></li>
                    <li><a href="#nosotros">Nosotros</a></li>
                    <li><a href="#contacto">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="inicio">
        <div class="container">
            <!-- Slider de imágenes -->
            <h2>Descubre la Magia de la Moda</h2>
            <p>¡Transforma tu estilo con FashionMagic!</p>
            <a href="#productos" class="btn">Ver Productos</a>
        </div>
    </section>

    <section id="productos">
        <div class="container">
            <h2>Nuestros Productos</h2>
            <!-- Catálogo de productos -->
            <div class="product">
                <img src="camiseta1.jpg" alt="Camiseta 1">
                <h3>Camiseta Mágica</h3>
                <p>¡Dale vida a tu armario con nuestra camiseta exclusiva!</p>
                <span class="price">$XX</span>
                <a href="#" class="btn">Agregar al Carrito</a>
            </div>
            <!-- Repite este bloque para más productos -->
        </div>
    </section>

    <section id="nosotros">
        <div class="container">
            <h2>Nuestra Historia</h2>
            <p>En FashionMagic, nos apasiona la moda y la creatividad. Fundada en XXXX, nuestra empresa se ha dedicado a...</p>
            <h3>Nuestro Equipo</h3>
            <!-- Equipo de la empresa -->
            <div class="team-member">
                <img src="miembro1.jpg" alt="Miembro del Equipo">
                <h4>Nombre del Miembro</h4>
                <p>Descripción breve del rol del miembro en la empresa.</p>
            </div>
            <!-- Repite este bloque para más miembros del equipo -->
        </div>
    </section>

    <section id="contacto">
        <div class="container">
            <h2>Contacto</h2>
            <p>¿Tienes alguna pregunta o comentario? ¡Contáctanos!</p>
            <!-- Formulario de contacto -->
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Nombre" required>
                <input type="email" name="email" placeholder="Correo Electrónico" required>
                <textarea name="message" placeholder="Mensaje" required></textarea>
                <button type="submit" class="btn">Enviar Mensaje</button>
            </form>
            <div class="contact-info">
                <h3>Información de Contacto</h3>
                <p>Dirección: XX Calle, Ciudad, País</p>
                <p>Teléfono: +XX-XXXX-XXXX</p>
                <p>Correo Electrónico: info@fashionmagic.com</p>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 FashionMagic. Todos los derechos reservados.</p>
            <ul>
                <li><a href="#">Términos y Condiciones</a></li>
                <li><a href="#">Política de Privacidad</a></li>
            </ul>
        </div>
    </footer>
</body>
</html>
