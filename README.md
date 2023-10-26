# HTML-5-primer-juego-Tetris
Sintaxis básica de un juego de tetris 
juego de tetris 

La sintaxis básica de un juego de tetris en HTML consiste en usar los siguientes elementos:

Un elemento <canvas> para dibujar el tablero, las piezas, la puntuación y los mensajes del juego.
Un elemento <audio> para reproducir los sonidos del juego, como el movimiento, el rotar, el eliminar y el perder.
Un elemento <script> para incluir el código JavaScript que define la lógica y el comportamiento del juego, como las variables, las funciones, los eventos y las condiciones.
Un elemento <style> para definir el aspecto visual del juego, como los colores, las fuentes y las animaciones.
Un ejemplo de código HTML que usa estos elementos para crear un juego de tetris es el siguiente1:



<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Juego de Tetris en HTML</title>
    <style>
        /* Aquí se definen los estilos del juego */
    </style>
</head>
<body>
    <canvas id="canvas" width="400" height="600"></canvas>
    <audio id="sound-move" src="sound/move.wav" preload="auto"></audio>
    <audio id="sound-rotate" src="sound/rotate.wav" preload="auto"></audio>
    <audio id="sound-clear" src="sound/clear.wav" preload="auto"></audio>
    <audio id="sound-gameover" src="sound/gameover.wav" preload="auto"></audio>
    <script>
        // Aquí se define el código JavaScript del juego
    </script>
</body>
</html>

![Captura de pantalla 2023-10-26 140849](https://github.com/andresfelipeoq/HTML-5-primer-juego-Tetris/assets/105876623/5ded5e74-6801-4f08-a644-ce35c963d194)
