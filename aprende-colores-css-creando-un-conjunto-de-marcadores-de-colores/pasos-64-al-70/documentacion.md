# Proyecto Marcadores de Colores con CSS

Incluso sin las pausas de color, podrás haber notado que los colores en transición para el marcador verde en los mismos puntos que en el marcador rojo. El primer color está al inicio (0%), el segundo en el medio (50%) y el ultimo al final (100%) de la línea de degradado.

La función `linear-gradient()` automáticamente calcula estos valores por ti, y coloca los colores equitativamente a lo largo de la linea de degradado por defecto.

Si no se coloca el argumento dirección a la función `linear-gradient()`, por defecto toma los colores de la parte superior a la parte inferior, o a través de una línea de 180 grados, por defecto.
