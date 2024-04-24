# Typing app

CSS
Se definen variables de color utilizando --green, --yellow, --red, --black y --gray.
Se aplican estilos de diseño general para el cuerpo, como el fondo, la fuente y el espaciado.
Se establecen estilos específicos para las secciones, el temporizador, las palabras, las letras y los resultados.
Se definen animaciones para el parpadeo del cursor y la transición del borde inferior de las palabras.

JavaScript

Se importa un conjunto inicial de palabras desde un archivo externo llamado data.js.
Se definen constantes y variables para elementos del DOM y valores iniciales del juego.
La función initGame() inicializa el juego estableciendo las palabras, el temporizador y configurando eventos.
La función initEvents() inicializa los eventos del teclado y el botón de recarga.
Se definen las funciones para manejar eventos de teclado (onKeyDown() y onKeyUp()) que controlan el progreso del juego y la entrada del usuario.
Cuando el temporizador llega a cero, se llama a la función gameOver() para finalizar el juego y mostrar los resultados.
En resumen, este código combina HTML para la estructura, CSS para el diseño y JavaScript para la funcionalidad de una aplicación de mecanografía que evalúa la velocidad y precisión de escritura del usuario.
