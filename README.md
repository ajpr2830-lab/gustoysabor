<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gusto y Sabor | Repostería Fina</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background-color: #fcfaf7;
            color: #333;
        }
        header {
            padding: 50px 20px;
            text-align: center;
            background-color: #ffffff;
            border-bottom: 1px solid #e0e0e0;
        }
        h1 {
            font-size: 3rem;
            letter-spacing: 5px;
            margin: 0;
            text-transform: uppercase;
            color: #1a1a1a;
        }
        nav {
            margin-top: 20px;
            word-spacing: 20px;
        }
        nav a {
            text-decoration: none;
            color: #888;
            font-size: 0.9rem;
            text-transform: uppercase;
        }
        .container {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
        }
        .receta-card {
            background: white;
            padding: 30px;
            margin-bottom: 30px;
            border: 1px solid #eee;
            transition: 0.3s;
        }
        .receta-card:hover {
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }
        .categoria {
            font-size: 0.7rem;
            color: #b08d57;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        h2 {
            font-size: 1.8rem;
            margin: 10px 0;
        }
        .boton {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 25px;
            background: #1a1a1a;
            color: white;
            text-decoration: none;
            font-size: 0.8rem;
        }
        footer {
            text-align: center;
            padding: 40px;
            font-size: 0.8rem;
            color: #aaa;
        }
    </style>
</head>
<body>

<header>
    <h1>GUSTO Y SABOR</h1>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Clásica</a>
        <a href="#">Moderna</a>
        <a href="#">Contacto</a>
    </nav>
</header>

<div class="container">
    <div class="receta-card">
        <span class="categoria">Repostería Clásica</span>
        <h2>Mousse de Chocolate al 70%</h2>
        <p>Una textura aireada con el balance perfecto de amargor y dulzura.</p>
        <a href="#" class="boton">VER RECETA</a>
    </div>

    <div class="receta-card">
        <span class="categoria">Repostería Moderna</span>
        <h2>Entremet de Frutos Rojos</h2>
        <p>Capas de gelatina ácida, bizcocho de almendra y glaseado espejo.</p>
        <a href="#" class="boton">VER RECETA</a>
    </div>
</div>

<footer>
    &copy; 2026 Gusto y Sabor - Un espacio exclusivo de Repostería.
</footer>

</body>
</html>
