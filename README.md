<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invernadero Inteligente NEJO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            width: 100%;
            text-align: center;
        }
        main {
            max-width: 900px;
            background-color: white;
            padding: 20px;
            margin: 20px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border-radius: 8px;
        }
        h1, h2, h3 {
            color: #333;
        }
        ul {
            list-style-type: disc;
            margin-left: 20px;
        }
        a {
            color: #4CAF50;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        footer {
            margin-top: 40px;
            padding: 10px;
            font-size: 0.9em;
            color: #777;
        }
    </style>
</head>
<body>
    <header>
        <h1>Invernadero Inteligente NEJO</h1>
    </header>
    <main>
        <section>
            <h2>Descripción del Proyecto</h2>
            <p>El <strong>Invernadero Inteligente NEJO</strong> es un prototipo desarrollado en el marco del proyecto de grado de la Universidad San Buenaventura, sede Bogotá. Su objetivo principal es mantener condiciones óptimas de temperatura y humedad para cultivos mediante un sistema automatizado.</p>
        </section>
        <section>
            <h2>Objetivo General</h2>
            <p>Mantener condiciones óptimas de temperatura y humedad para cultivos en un invernadero automatizado.</p>
        </section>
        <section>
            <h2>Componentes Principales</h2>
            <ul>
                <li><strong>Sensor DHT22</strong>: Captura temperatura y humedad con precisión.</li>
                <li><strong>Microcontrolador ESP32</strong>: Procesa datos y ejecuta la lógica de control.</li>
                <li><strong>Actuadores</strong>:
                    <ul>
                        <li>Ventilador/extractor para regulación térmica.</li>
                        <li>Bomba de agua para riego automático.</li>
                    </ul>
                </li>
                <li><strong>Pantalla táctil</strong>: Para monitoreo del usuario (en desarrollo).</li>
                <li><strong>Fuente de alimentación</strong>: Batería o fuente externa.</li>
                <li><strong>Repositorio GitHub</strong>: <a href="https://github.com/usuario/invernadero-inteligente-nejo" target="_blank" rel="noopener noreferrer">https://github.com/usuario/invernadero-inteligente-nejo</a></li>
            </ul>
        </section>
        <section>
            <h2>Evidencia de Conocimiento</h2>
            <h3>Infraestructura de hardware y software</h3>
            <ul>
                <li><strong>Hardware</strong>: ESP32, DHT22, bomba de agua, ventilador, pantalla táctil, fuente de alimentación.</li>
                <li><strong>Software</strong>: Comunicación entre ESP32 y envío de datos mediante programación.</li>
            </ul>
            <h3>Instrumentación y Sensores</h3>
            <ul>
                <li><strong>DHT22</strong>: Sensor digital de temperatura y humedad.
                    <ul>
                        <li>Rango: -40 a 80 °C</li>
                        <li>Humedad: 0–100% HR</li>
                        <li>Alimentación: 3.3 a 6V</li>
                        <li>Consumo: 2.5 mA</li>
                        <li>Frecuencia de muestreo: 2 Hz</li>
                    </ul>
                </li>
                <li><strong>Instrumentación adicional</strong>: Posible integración futura de sensores de luz o humedad del suelo.</li>
            </ul>
            <h3>Elementos de Potencia</h3>
            <ul>
                <li>Fuente de 5 V DC para ESP32 y pantalla táctil.</li>
            </ul>
        </section>
        <section>
            <h2>Conceptos de Control</h2>
            <p><strong>PLC</strong>: Dos ESP32 configurados como maestro y esclavo para distribuir tareas y mejorar la estabilidad.</p>
        </section>
        <section>
            <h2>Paradigma IoT</h2>
            <ul>
                <li><strong>Conectividad</strong>: El ESP32 envía datos a la nube mediante Bluetooth.</li>
                <li><strong>Visualización</strong>: Los datos se muestran en la pantalla táctil.</li>
            </ul>
        </section>
        <section>
            <h2>Conclusión</h2>
            <p>El prototipo integra conocimientos de IoT, sistemas de potencia, conceptos de PLC y gestión industrial para ofrecer soluciones seguras y prácticas en la automatización de invernaderos.</p>
        </section>
    </main>
    <footer>
        <p>© 2024 Invernadero Inteligente NEJO - Universidad San Buenaventura</p>
    </footer>
</body>
</html>
       

