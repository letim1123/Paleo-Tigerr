<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paleo Tiger</title>
    <style>
        body {
            background-color: rgb(201, 177, 150);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            text-align: center;
        }
     .logo img { width: 400px; /* Ajusta este valor para cambiar el tamaño del logo */ display: block;
        display: block; margin: 0 auto;
        }
        .main-content {
            background-color: hsl(36, 51%, 73%);
            border: 1px solid rgb(216, 181, 141);
            padding: 15px;
            margin-bottom: 20px;
        }
        .section {
            background-color: #d6b89a;
            border: 1px solid rgb(127, 185, 112);
            padding: 10px;
            margin-bottom: 10px;
            cursor: pointer;
        }
        .section img {
            display: none;
            margin-top: 10px;
            width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">
            <img src="images/BackgroundEraser_20240726_081822653.png" alt="Paleo Tiger Logo">
        </div>
        <h1>Paleo Tiger</h1>
        <h2>La historia en la vida de nuestro planeta</h2>
        <div class="main-content">
            <p>
                Somos un grupo de jóvenes Latinoamericanos que buscamos la divulgación científica respecto a la paleobiología en Latinoamérica y otras partes del mundo.
                Nos dedicamos al paleoarte y dictar talleres, en su mayoría gratuitos, pues el conocimiento es algo que debe estar al alcance de todo el mundo.
                ¡Acá podrás encontrar información respecto a talleres de paleoarte, paleontología en la región y sobre todo las noticias recientes sobre la Paleontología o biología!
            </p>
        </div>
        <div class="section">
            Paleontología Venezuela
            <img src="images/WhatsApp Image 2024-11-01 at 5.46.36 PM.jpeg" alt="Paleontología Venezuela1">
            <img src="images/PEPE.jpeg" alt="Paleontología Venezuela2">
        </div>
        <div class="section">
            Paleontología América
            <img src="tu-imagen-america.png" alt="Paleontología América">
        </div>
        <div class="section">
            Noticias
            <img src="tu-imagen-noticias.png" alt="Noticias">
        </div>
    </div>

    <script>
        document.querySelectorAll('.section').forEach(section => {
            section.addEventListener('click', () => {
                const img = section.querySelector('img');
                img.style.display = img.style.display === 'none' ? 'block' : 'none';
            });
        });
    </script>
</body>
</html>
