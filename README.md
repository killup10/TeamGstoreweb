<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TeamG Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #18191A;
            color: #E4E6EB;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #242526;
            padding: 20px;
            font-size: 24px;
        }
        .logo {
            max-width: 150px;
            height: auto;
            margin-bottom: 10px;
        }
        section {
            padding: 20px;
        }
        .button {
            background-color: #1877F2;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            display: inline-block;
            border-radius: 5px;
            margin: 10px;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 20px;
        }
        .testimonios {
            background-color: #242526;
            padding: 20px;
            border-radius: 10px;
            margin: 20px;
        }
        .testimonio {
            margin-bottom: 15px;
            font-style: italic;
        }
        .theme-toggle {
            position: fixed;
            top: 10px;
            right: 10px;
            background-color: #444;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .light-mode {
            background-color: white;
            color: black;
        }
    </style>
</head>
<body>
    <button class="theme-toggle" onclick="toggleTheme()">Modo Claro/Oscuro</button>
    <header>
        <img src="https://dl.dropboxusercontent.com/scl/fi/ntmhjhlwr4xoo9wmyqlex/logoteamg.png?rlkey=fnfi1z0e3pd5ho7aw9um6sb4m" alt="TeamG Store Logo" class="logo">
        <h1>Bienvenido a TeamG Store</h1>
    </header>
    <section>
        <h2>Nuestros Servicios</h2>
        <p>OttPlayer, Streaming y más...</p>
        <p>Ofrecemos servicios desde el 2016</p>
    </section>
    <section>
        <h2>Nuestros Planes</h2>
        <p>Elige el plan que mejor se adapte a ti.</p>
        <img src="https://dl.dropboxusercontent.com/scl/fi/ir2mytpbvdbiyuc29clta/DE-80-CANALES-EN-VIVO.png?rlkey=1dwinl8yh93hc1cyt4qww07es" alt="Planes de TeamG Store">
    </section>
    <section>
        <h2>Únete a nuestra comunidad</h2>
        <p>Forma parte de nuestro grupo de clientes en Facebook.</p>
        <a class="button" href="https://www.facebook.com/groups/teamgstor" target="_blank">Grupo de Clientes</a>
    </section>
    <section>
        <h2>Contáctanos</h2>
        <p>WhatsApp: <a href="https://wa.me/912194777" target="_blank">912194777</a></p>
        <a class="button" href="https://www.facebook.com/teamgstorperu" target="_blank">Facebook</a>
    </section>
    <section>
        <h2>Formulario de Contacto</h2>
        <p>Envíanos un mensaje sin salir de la web.</p>
        <a class="button" href="https://wa.me/912194777" target="_blank">WhatsApp</a>
        <a class="button" href="https://m.me/teamgstorperu" target="_blank">Messenger</a>
    </section>
    <section>
        <h2>Botón de Pago Directo</h2>
        <p>Paga de manera rápida y segura a través de Yape, Plin o PayPal.</p>
        <p>Yape/Plin: <strong>938993594 - Rosa Tirado</strong></p>
    </section>
    <section>
        <h2>Experiencia Real</h2>
        <p>Disfruta del mejor contenido en tu Smart TV con nuestra plataforma.</p>
        <img src="https://statics.forbesargentina.com/2022/07/62e1574d13664.jpg" alt="Personas viendo Smart TV">
    </section>
    <section>
        <h2>Preguntas Frecuentes (FAQ)</h2>
        <p><strong>¿Cómo funciona el servicio?</strong></p>
        <p>Nuestro servicio funciona mediante OttPlayer, una aplicación disponible en todos los dispositivos. Ofrecemos 1 hora de prueba gratuita.</p>
        <p><strong>¿Qué velocidad de internet necesito?</strong></p>
        <p>Recomendamos tener al menos 50 Mbps de velocidad en tu conexión de internet para una experiencia óptima.</p>
    </section>
    <section class="testimonios">
        <h2>Testimonios de Clientes</h2>
        <p class="testimonio">"Increíble servicio, nunca falla y la calidad es excelente." - Juan Pérez</p>
        <p class="testimonio">"Me encanta, lo uso todos los días en mi Smart TV." - María López</p>
        <p class="testimonio">"Rápido y fácil de usar, lo recomiendo." - Carlos Sánchez</p>
        <p class="testimonio">"El mejor servicio de streaming que he probado." - Ana Torres</p>
    </section>
    <script>
        function toggleTheme() {
            document.body.classList.toggle("light-mode");
        }
    </script>
</body>
</html>
