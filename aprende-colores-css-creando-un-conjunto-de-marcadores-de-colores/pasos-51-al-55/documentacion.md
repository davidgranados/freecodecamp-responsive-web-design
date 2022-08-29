# Proyecto Marcadores de Colores con CSS

No vas a notar el degradado debido a que la función `linear-gradient()` necesita **al menos dos** argumentos de color para funcionar.

Como puedes ver, la función `linear-gradient()` produjo un degradado rojo-verde bastante fluido. Si bien esta función necesita un minimo de dos argumentos de color para funcionar, **puede aceptar varios** argumentos de este tipo.

Las pausas de color (color stops) te permiten ajustar donde se van a mostrar los colores a lo largo del degradado. Son **unidades de longitud** en pixeles o porcentajes que siguen después del valor para el color en la función `linear-gradient()`.

Por ejemplo, en este degradado rojo-negro, la transición de rojo a negro se lleva a cabo al llegar al 90% de la línea de degradado, así que el rojo ocupa la mayor parte del espacio disponible:

>

    linear-gradient(90deg, red 90%, black);

Ahora que sabes los básico sobre cómo crear una función `linear-gradient()` y cómo funcionan las pausas de color, puedes utilizarlas para hacer que los marcadores se vean más realistas.
