# Pr-ctica-HTML-Creaci-n-de-un-sitio-Web

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Juegos de Mesa - Inicio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Bienvenido a la Tienda de Juegos de Mesa</h1>
</header>

<nav>
    <a href="index.html" title="Página de inicio">Inicio</a>
    <a href="productos.html" title="Ver productos">Productos</a>
    <a href="acerca.html" title="Acerca de nuestra tienda">Acerca de</a>
    <a href="contacto.html" title="Contáctanos">Contacto</a>
</nav>

<main>
    <section>
        <h2>Explora nuestra selección de juegos de mesa</h2>
        <p><strong>Los mejores juegos para compartir con amigos y familia.</strong></p>
        <p>¡Descubre nuevos desafíos y horas de diversión!</p>
        <img src="img/juego-inicio.jpg" alt="Juegos de mesa" style="width:100%;max-width:600px;">
    </section>
</main>

<footer>
    <p>&copy; 2024 Tienda de Juegos de Mesa</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Juegos de Mesa - Productos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .product-list {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product {
            background-color: white;
            padding: 10px;
            border: 1px solid #ddd;
            text-align: center;
        }
        .product img {
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

<header>
    <h1>Productos Disponibles</h1>
</header>

<nav>
    <a href="index.html" title="Página de inicio">Inicio</a>
    <a href="productos.html" title="Ver productos">Productos</a>
    <a href="acerca.html" title="Acerca de nuestra tienda">Acerca de</a>
    <a href="contacto.html" title="Contáctanos">Contacto</a>
</nav>

<main>
    <section>
        <h2>Juegos Populares</h2>
        <div class="product-list">
            <div class="product">
                <h3>Catan</h3>
                <img src="https://github.com/manchito82/Pr-ctica-HTML-Creaci-n-de-un-sitio-Web/blob/main/catan.jfif" alt="Catan - Juego de mesa" />
                <p><strong>Precio:</strong> $29.99</p>
                <a href="#">Comprar</a>
            </div>
            <div class="product">
                <h3>Ticket to Ride</h3>
                <img src="img/ticket-to-ride.jpg" alt="Ticket to Ride - Juego de mesa" />
                <p><strong>Precio:</strong> $34.99</p>
                <a href="#">Comprar</a>
            </div>
            <div class="product">
                <h3>Monopoly</h3>
                <img src="img/monopoly.jpg" alt="Monopoly - Juego de mesa" />
                <p><strong>Precio:</strong> $19.99</p>
                <a href="#">Comprar</a>
            </div>
        </div>
    </section>
</main>

<footer>
    <p>&copy; 2024 Tienda de Juegos de Mesa</p>
</footer>

</body>
</html>


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Juegos de Mesa - Acerca de</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Acerca de nuestra Tienda</h1>
</header>

<nav>
    <a href="index.html" title="Página de inicio">Inicio</a>
    <a href="productos.html" title="Ver productos">Productos</a>
    <a href="acerca.html" title="Acerca de nuestra tienda">Acerca de</a>
    <a href="contacto.html" title="Contáctanos">Contacto</a>
</nav>

<main>
    <section>
        <h2>¿Quiénes somos?</h2>
        <p>En nuestra tienda online, ofrecemos una amplia variedad de juegos de mesa para todas las edades y gustos. Desde los clásicos más populares hasta los juegos más innovadores.</p>
        <p><strong>¡Diviértete, aprende y comparte con tus seres queridos!</strong></p>
    </section>
</main>

<footer>
    <p>&copy; 2024 Tienda de Juegos de Mesa</p>
</footer>

</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Juegos de Mesa - Contacto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Contáctanos</h1>
</header>

<nav>
    <a href="index.html" title="Página de inicio">Inicio</a>
    <a href="productos.html" title="Ver productos">Productos</a>
    <a href="acerca.html" title="Acerca de nuestra tienda">Acerca de</a>
    <a







