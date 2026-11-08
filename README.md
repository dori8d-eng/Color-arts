# Color Arts

Juego de colorear en el navegador. Arma el paisaje como rompecabezas y vuelve a pintarlo con los colores que tú mezcles.

## Pantallas

- **Inicio**: Jugar, Biblioteca, Tienda y Configurar, con tus monedas.
- **Jugar**: el tablero con herramientas (pincel, plumón, cubeta, borrador, regla y pinceles especiales), paleta e inventario de mezclas.
- **Biblioteca**: tus dibujos, animaciones y mezclas guardadas.
- **Tienda**: paisajes y dibujos, mapas del modo amigable, pinceles, marcos y música, que se compran con monedas.
- **Configurar**: modo de juego, sonido, música, dificultad, paisaje, pistas y más.

## Modos de juego

- **Rompecabezas**: arma el paisaje (3×3 a 9×9) y píntalo.
- **Creativo**: dibujo libre con calificación.
- **Pixel**: cuadritos con número.
- **Sin color**: pinta en blanco y negro y descubre los colores al final.
- **Animación**: dibuja fotogramas y reprodúcelos.
- **Amigable**: dos jugadores en el mismo dispositivo.

Cada dibujo tiene muchas partes para colorear (de 11 a 22). Hay 38 paisajes y dibujos (14 gratis y 24 en la Tienda) y 24 mapas para dos jugadores. Los colores se descubren mezclando (hasta 150).

## Jugar

Abre `index.html` en cualquier navegador. No necesita instalación. El progreso (monedas, colores, compras y guardados) se queda en el navegador.

## Calificación

La IA recibe el dibujo, su nombre, cada parte con su color original y las partes que quedaron sin pintar. La nota final combina lo que dice la IA con lo que mide el juego:

- **Rompecabezas y Sin color:** se mezcla con los colores medidos parte por parte (las partes chicas cuentan casi igual que las grandes).
- **Amigable:** se mezcla con cuánto se pintó.
- **Creativo y Animación:** un dibujo hecho en pocos segundos no puede sacar la nota más alta.
- Solo cuenta como garabato si la IA lo dice y el juego también ve poco esfuerzo o trazos sin sentido.

La calificación con IA solo funciona dentro de Claude; fuera de ahí el juego califica por su cuenta.
