<!DOCTYPE html>
<html lang="es">
<head>
<link rel="icon" href="corazon.png" type="image/png">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz San Valentin Martin <3</title>
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('fondo.jpeg'); /* Cambia 'fondo.jpg' por tu imagen de fondo */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            display: flex;
            width: 90%;
            max-width: 1200px;
            background-color: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            padding: 20px;
        }

        /* Estilos para las secciones */
        .section {
            flex: 1;
            padding: 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .section img, .section video {
            max-width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        /* Estilos para el título */
        h1 {
            text-align: center;
            font-size: 2.5rem;
            color: #ff6b6b;
            margin-bottom: 20px;
        }

        h1::after {
            content: " ";
        }

        /* Estilos responsivos */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .section {
                margin-bottom: 20px;
            }

            h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Sección de imágenes (izquierda) -->
        <div class="section">
            <h1>FELIZ SAN VALENTIN</h1>
            <div class="image-slider">
                <img src="foto1.jpeg" alt="Foto 1" class="active">
                <img src="foto2.jpeg" alt="Foto 2">
                <img src="foto3.jpeg" alt="Foto 3">
            </div>
        </div>

        <!-- Video (centro) -->
        <div class="section">
            <video controls>
                <source src="martinv.mp4" type="video/mp4">
                Tu navegador no soporta el elemento de video.
            </video>

    <p style="text-align: center; font-size: 1.2rem; color: #ff6b6b; margin-top: 10px;">
        No sé como decirte sin que suene demasiado, pero te lo digo "TE QUIERO", me gusta hablar contigo aunque ultimamente te he sentido distante pero aun así quiero saber cómo estás, cómo te sientes o qué hiciste durante el día, así como esa notita que esta al final nunca olvides que eres una persona increible e importante, te mando besitos tu sabras donde y abracitos de oso. Capaz a lo que te envie el link has de pensado y esto yo hubiera preguntado es virus? o no se si te preguntarias ajajaj estaba pensando capaz piensas que estoy loquitaaaaa jajajaj   
   	
	</p>


        </div>

        <!-- Sección de videos (derecha) -->
        <div class="section">
            <div class="video-slider">
                <video controls class="active">
                    <source src="video2.mp4" type="video/mp4">
                    Tu navegador no soporta el elemento de video.
                </video>
                <video controls>
                    <source src="video1.mp4" type="video/mp4">
                    Tu navegador no soporta el elemento de video.
                </video>
                <video controls>
                    <source src="video3.mp4" type="video/mp4">
                    Tu navegador no soporta el elemento de video.
                </video>
            </div>
        </div>
    </div>

    <script>
        // Script para cambiar las imágenes automáticamente
        let imageIndex = 0;
        const images = document.querySelectorAll('.image-slider img');

        function changeImage() {
            images.forEach(img => img.classList.remove('active'));
            imageIndex = (imageIndex + 1) % images.length;
            images[imageIndex].classList.add('active');
        }

        setInterval(changeImage, 3000); // Cambia la imagen cada 3 segundos

        // Script para cambiar los videos automáticamente
        let videoIndex = 0;
        const videos = document.querySelectorAll('.video-slider video');

        function changeVideo() {
            videos.forEach(video => video.classList.remove('active'));
            videoIndex = (videoIndex + 1) % videos.length;
            videos[videoIndex].classList.add('active');
        }

        setInterval(changeVideo, 5000); // Cambia el video cada 5 segundos
    </script>
</body>
</html>
