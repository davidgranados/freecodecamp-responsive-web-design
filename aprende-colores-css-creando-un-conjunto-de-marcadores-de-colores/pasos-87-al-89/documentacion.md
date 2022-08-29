# Proyecto Marcadores de Colores con CSS

Como puedes notar, agregaste una simple sombra roja al rededor de tu marcador, 5 pixeles a la derecha y 5 pixeles abajo.

Pero, ¿y si quiseras que la posición de la sombra estuviese en el lado opuesto? Puedes hacerlo cambiando los valores de los ejes X e Y por valores negativos.

Observa que las esquinas de la sombra son puntiagudas. Esto se debe a que hay un valor opcional para la propiedad [box-shadow][1], el valor `blurRadius`.

Su sintaxis es la siguiente:

>

    box-shadow: ejeX ejeY blurRadius color;

Si el valor del blurRadius no está incluido, por defecto se le asigna 0 y esto produce esquinas puntiagudas. Mientras más alto sea el valor del `blurRadius`, mayor será el efecto de difuminación.

Pero ¿Y si quiseras expandir la sombra un poco más? Puedes hacerlo con el valor opcional `spreadRadius`:

>

    box-shadow: ejeX ejeY blurRadius spredRadius color;


Al igual que el blurRadius, el valor de `spreadRadius` es 0 por defecto si no se especifica.

Practica agregando 5 pixeles de sombra directamente al rededor del marcador azul.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/box-shadow
