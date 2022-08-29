# Proyecto Marcadores de Colores con CSS

Otra manera de modificar la opacidad de un elemento es con el canal alfa (alpha channel). Similar a la propiedad `opacity`, el canal alfa controla qué tan transparente u opaco es un color.

Ya has asignado la opacidad de la etiqueta con un color que utiliza palabra clave y la propiedad opacity, pero puedes agregar un canal alfa a las demás propiedades de color en CSS.

Ya conoces el modo de uso de la función `rgb()` para asignar colores. Para agregar el canal alfa a un color rgb, debes utilizar la función `rgba()` en lugar de la rgb.

La función `rgba()` trabaja igual que la función `rgb()`, pero recibe un número adicional entre 0 y 1.0 para el canal alfa:

>

    rgba(valorRojo, valorVerde, valorAzul, valorCanalAlfa);

La etiqueta que agregaste luce bien, pero se vería mucho mejor si estuviese posicionada un poco más hacia el lado derecho del marcador. Una manera de lograr esto es agregando otro elemento antes de la etiqueta para empujarla hacia la derecha.

Parece que nuestra etiqueta desapareció, pero no te preocupes, sigue ahí. Lo que ocurrió es que nuestro nuevo elemento `<div>` está tomando todo el ancho del marcador y está desplazando nuestra etiqueta hacia abajo a la siguiente línea.

Esto se debe a que la propiedad [display][1] del elemento `<div>` es `block` por defecto. Cuando dos elementos con la propiedad `display block` están uno al lado del otro se apilan como bloques reales. Por ejemplo, tus elementos para los marcadores están apilados uno sobre otro.

Para posicionar dos elementos `<div>` en la misma línea, debes cambiar el valor de su propiedad `display` a `inline-block`.

En el ultimo proyecto, aprendiste un poco sobre bordes y la propiedad [border-color][2].

**Todos** los elementos HTML tienen bordes, aunque usualmente tienen el valor `none` por defecto. Con CSS, puedes controlar todos los aspectos de los bordes de un elemento y asignar sus valores en todos los lados, o solo un lado por independiente. Para que los bordes sean visibles, necesitas asignarles un valor a sus propiedades `width` y `style`.

Los bordes tienen multiples estilos para escoger. Puedes hacer que un borde sea una línea sólida o punteada, dependiendo de tu preferencia. Las líneas con borde sólido son, probablemente, las más comunes.

Tu borde debería ser visible ahora. Si no has asignado ningún color, se utiliza el negro por defecto.

Pero para hacer tu código más legible, es mejor asignar el color del borde explícitamente.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/display
[2]: https://developer.mozilla.org/es/docs/Web/CSS/border-color
