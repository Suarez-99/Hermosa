# Hermosa
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Regalo de San Valentín</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #ffcccc; /* Color de fondo rosa claro */
            font-family: 'Arial', sans-serif;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            text-align: center;
        }

        .regalo {
            background-color: #ffffff; /* Fondo blanco del regalo */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            cursor: url('corazon.cur'), pointer; /* Utiliza un cursor personalizado en forma de corazón */
        }

        h1 {
            color: #ff4d4d; /* Color rojo claro para el título */
        }

        p {
            font-size: 18px;
            color: #333333; /* Color de texto oscuro */
        }

        .corazon {
            color: #ff4d4d; /* Color rojo claro para el corazón */
            font-size: 24px;
        }

        #carta {
            background-color: rgba(255, 255, 255, 0.8); /* Fondo semitransparente de la carta */
            padding: 20px;
            border-radius: 10px;
            margin-top: 20px;
            overflow: hidden;
        }

        #imagenes {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
        }

        #imagenes img {
            max-width: 45%; /* Ajusta el ancho máximo de las imágenes a tu preferencia */
            border-radius: 10px;
        }
  
         #imagenes img {
    width: 150px; /* Tamaño específico para las imágenes */
    border-radius: 10px;
        }
        #carta.mostrar {
            display: block; /* Muestra el contenido de la carta cuando tiene la clase 'mostrar' */
        }
    </style>
</head>
<body>
    <div class="regalo" id="regalo">
        <h1>¡Feliz Día de San Valentín!</h1>
        <p>Te envío este regalo especial con todo mi amor.</p>
        <p>Espero que tengas un día lleno de amor y alegría.</p>
        <p class="corazon" onclick="mostrarCarta()">&#10084;</p>
    </div>

    <div id="carta">
        <h2>Hermosa</h2>
        <p>Hola hermosa,</p>
            <p>Te escribo esta carta para recordarte que este 14 de febrero es nuestro primer día importante...</p>
            <p>Tengo preparada una linda sorpresa para vos. Espero que te guste. Te amo demasiado y sinceramente sos una persona grandiosa para mí.</p>
            <p>Te quiero con toda el alma y te amo muchísimo. No quiero nunca que te alejes de mi lado.</p>
            <p>Ya quiero pedirte que seas mi novia para que podamos estar juntos 25/7. Yo nunca me voy a cansar de vos y quiero que sepas que podés contar conmigo para lo que sea.</p>
            <p>Ya que soy tu compañero para todo, hermosa. Esto es poquito lo que te puedo dar, pero espero que lo disfrutes muchísimo y que esta carta te llegue al más profundo de tu corazón ya que la hice con mucho amor y esfuerzo.</p>
            <p>Quiero amarte y respetarte todos los días de mi vida, amor hermoso. Todos los días con vos son 14 de febrero.</p>
            <p>Atte: Tu loquito</p>
        
        <div id="imagenes">
            <img src="Fotos/WhatsApp Image 2024-02-15 at 09.25.26 (1).jpeg" alt="Imagen Izquierda">
            <img src="Fotos/WhatsApp Image 2024-02-15 at 09.25.26.jpeg" alt="Imagen Derecha">
        </div>

    <script>
        function mostrarCarta() {
            var carta = document.getElementById("carta");
            carta.classList.toggle("mostrar"); // Alternar la clase 'mostrar' para mostrar u ocultar la carta
        }
    </script>
</body>
</html>
