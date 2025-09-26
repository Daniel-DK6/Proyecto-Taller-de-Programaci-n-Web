<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="Tienda DK" content="width-device-width, initial-scale-1.0">
    <title>Mi Perfil - UTP</title>
</head>

<body>
    <h1> Hola soy daniel </h1>
    <img src="" alt="Mi foto">
    <p class="descripcion"> Estudiante de la UTP, apasionado por la tecnologia .</p>

    <h2> Mis hobbies:</h2>
    <ul>
        <li>Programar</li>
        <li>Jugar videojuegos</li>
        <li>Ver animes</li>
        <li>Ver peliculas</li>
    </ul>

    <a href="https://github.com/Daniel-DK6/Proyecto-Taller-de-Programaci-n-Web.git">Mi GitHub</a>
</body>

</html>

<html lang="es">
<head>
<meta charset="=UTF-8">
<title>Tienda DK</title>
<link rel="stylesheet" href="estilos.css">
</head>

<body>
    <head>
        <img src="logo.png" alt="logo">
        <nav>
            <a href="index.html">Inicio</a>
            <a href="servicios.html">servicios</a>
            <a href="contacto.html">contacto</a>
        </nav>
    </head>

    <main>
        <h1>Bienvenidos a la tienda web DK</h1>
        <p>Este es el contenido principal.</p>
    </main>

    <footer>
        <p>&copy; 2025 Mi empresa </p> | <a href="privacidad.html">privacidad</a>
    </footer>
</body>
</html>

<form action="/procesar-formulario" method="POST">
    
    <input type="text" name="nombre" placeholder="Daniel" required>

    <input type="email" name="email" placeholder="danielsaavedracanchanya@email.com" required>

    <input type="tel" name="telefono" pattern="[0-9]{9}" placeholder="992576550">

    <input type="password" name="contrasena" minlength="123456" required>

    <textarea name="mensaje" rows="5" placeholder="Tu mensaje aqui..."></textarea>

    <input type="date" name="=07/09/25">

<select name="asunto">
    <option value="">Selecciona un asunto</option>
    <option value="consulta">Consulta</option>
    <option value="sugerencia">Sugerencia</option>
    <option value="queja">Queja</option>
</select>

<input type="checkbox" name="newsletter" id="newsletter">
<label for="newsletter">Suscribirse al newsletter</label>

<input type="radio" name="genero" value="masculino" id="masculino">
<label for="masculino">Masculino</label>
<input type="radio" name="genero" value="femenino" id="femenino">
<label for="femenino">Femenino</label>

<button type="submit">Enviar Mensaje</button>

<img src="imagen.jpg" alt="Descripción de la imagen" width="300" height="200">

<img src="imagen.jpg" alt="Descripción de la imagen" class="img-responsive">

<picture>
    <source media="(max-width: 768px)" srcset="imagen-small.jpg">
    <source media="(max-width: 1200px)" srcset="imagen-medium.jpg">
    <img src="imagen-large.jpg" alt="Descripción">
</picture>

<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    <source src="audio.ogg" type="audio/ogg">
    Tu navegador no soporta el elemento de audio.
</audio>

<audio autoplay loop>
    <source src="background-music.mp3" type="audio/mpeg">
</audio>

<video controls width="100%" poster="miniatura.jpg">
    <source src="video.mp4" type="video/mp4">
    <source src="video.webm" type="video/webm">
    Tu navegador no soporta el elemento de video.
</video>

<video controls width="640" height="360">
    <source src="video.mp4" type="video/mp4">
    <source src="video.webm" type="video/webm">
    <track kind="subtitles" src="subtitulos.vtt" srclang="es" label="Español">
</video>

</form>
