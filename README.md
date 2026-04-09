<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invernadero Inteligente NEJO</title>

    <!-- Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #0f172a;
            color: #f7f7f7;
            margin: 0;
        }

        header, footer {
            background-color: black;
            text-align: center;
            padding: 15px;
        }

        h1, h2 {
            color: #22c55e;
            font-family: cursive;
        }

        .section {
            background-color: #020617;
            padding: 30px;
            margin: 20px;
            border-radius: 10px;
        }

        img {
            max-width: 100%;
            border-radius: 10px;
        }

        .btn-custom {
            background-color: black;
            color: white;
            margin: 5px;
        }

        .btn-custom:hover {
            background-color: #22c55e;
            color: black;
        }

        .video-container {
            text-align: center;
        }
    </style>
</head>

<body>

<header>
    <!-- LOGO -->
    <img src="NEJO.jpeg" width="300" alt="Logo NEJO">
    <h1>Invernadero Inteligente NEJO</h1>
</header>

<!-- DESCRIPCIÓN -->
<div class="section">
    <h2>Descripción del Proyecto</h2>
    <p>
        Este proyecto busca mantener condiciones óptimas de temperatura y humedad 
        dentro de un invernadero mediante automatización e implementación de IoT.
    </p>
</div>

<!-- OBJETIVOS -->
<div class="container text-center">
    <div class="row">
        <div class="col section">
            <h2>Objetivo General</h2>
            <p>
                Mantener condiciones óptimas de temperatura y humedad para cultivos en un sistema automatizado.
            </p>
        </div>

        <div class="col section">
            <h2>Objetivos Específicos</h2>
            <ul>
                <li>Monitorear temperatura y humedad con sensor DHT22</li>
                <li>Automatizar riego con bomba de agua</li>
                <li>Controlar ventilación con extractor</li>
                <li>Visualizar datos en pantalla</li>
            </ul>
        </div>
    </div>
</div>

<!-- COMPONENTES -->
<div class="section">
    <h2>Componentes del Sistema</h2>
    <ul>
        <li>ESP32 (Microcontrolador)</li>
        <li>Sensor DHT22</li>
        <li>Bomba de agua</li>
        <li>Ventilador</li>
        <li>Pantalla táctil</li>
    </ul>
</div>

<!-- IMÁGENES -->
<div class="section text-center">
    <h2>Imágenes del Proyecto</h2>
    <img src="img/invernadero1.jpg" alt="Imagen 1">
    <br><br>
    <img src="img/invernadero2.jpg" alt="Imagen 2">
</div>

<!-- VIDEO -->
<div class="section video-container">
    <h2>Video del Prototipo</h2>
    <video width="600" controls>
        <source src="NEJO.mp4" type="video/mp4">
        Tu navegador no soporta video.
    </video>
</div>

<!-- DOCUMENTOS -->
<div class="section text-center">
    <h2>Documentación</h2>

    <a href="documentoInvernadero(2).docx" download>
        <button class="btn btn-custom">Descargar Documento 1</button>
    </a>

    <a href="Prototipo .docx" download>
        <button class="btn btn-custom">Descargar Documento 2</button>
    </a>
</div>

<footer>
    <p>© 2026 - Proyecto Invernadero Inteligente NEJO</p>
</footer>

</body>
</html>
