<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header con Logo de Limón</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        header {
            background: linear-gradient(to right, #4CAF50, #388E3C);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
        }
        .logo img {
            width: 50px;
            height: auto;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: #C8E6C9;
            font-size: 18px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #A5D6A7;
        }
    </style>
</head>
<body>
    <header>
        <a href="#" class="logo">
            <img src="img_header" alt="limón.jpg">
        </a>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
</body>
</html>
