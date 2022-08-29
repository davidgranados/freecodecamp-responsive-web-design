# Proyecto Marcadores de Colores con CSS

Una forma muy común de aplicar color a un elemento usando CSS es con los valores hexadecimales o hex. Aunque los valores hex pueden sonar complicados, en realidad son otra forma de indicar los valores de RGB.

Los valores para colores en hex comienzan con el caracter # y toman seis caracteres numéricos del 0 al 9 y alfabéticos de al A a la F. El primer par de caracteres representan el color rojo, el segundo par el color verde y el tercero el color azul. Por ejemplo `#4B5320`.

Ya estarás familiarizado con los valores decimales o de base 10, que son los que usualmente utilizamos en nuestro día a día y los cuales van del 0 al 9. Los hexadecimales, o base 16, van del 0 al 9 y luego de la A a la F:

>

    0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

Con los colores hex, el valor `00` representa el 0% de ese color y el `FF` es el 100%. Así que `#00FF00` se traduce como 0% rojo, 100% verde y 0% azul y es lo mismo que `rgb(0, 255, 0)`.

El modelo de color HSL, o matiz, saturación y luminosidad (hue, saturation and lightness en inglés), es otra manera de representar colores.

La función CSS `hsl()` acepta tres valores: un número de 0 a 360 para el matiz (hue), un porcentaje de 0 a 100 para la saturación y un porcentaje de 0 a 100 para la luminosidad (lightness).

Si te imagínas el circulo cromático, el matiz del rojo está a 0 grados, el verde a 120 grados y el azul a 240 grados.

![Circulo Cromatico](https://www.blogdelfotografo.com/wp-content/uploads/2022/01/6.-Ci%CC%81rculo-Croma%CC%81tico_BDFGRAPH-edited-1.png "Circulo Cromático")

La saturación es la intensidad del color de 0% o gris a 100% de color puro.

La luminosidad es qué tan brillante se verá el color, de 0% o completamente negro a 100% o completamente blanco siendo el 50% neutral.

Has aprendido algunas formas de asignar colores planos en CSS, pero también puedes utilizar transición de colores, o degradado, en un elemento.

Un degradado es cuando un color transiciona en otro. La función de CSS [`linear-gradient()`][1] te permite controlar la dirección de la transición a lo largo de una línea, y cuales colores serán utilizados.

Una cosa que debes recordar es que la función `linear-gradient()` realmente crea un elemento image ([`<img>`][2]), y usualmente es emparejado con la propiedad [background][3], la cual puede aceptar una imagen como valor.

La función `linear-gradient()` es bastante flexible. Acá tienes la sitanxis básica que utilizarás en este tutorial:

>

    linear-gradient(direccion, color1, color2, ...);

El valor dirección indica hacia donde se aplicará la transición. color1 y color2 son los argumentos para los colores, los cuales serán utilizados para realizar la
transición como tal. Estos pueden ser cualquier tipo de color, incluyendo palabras clave, valores hex, rgb o hsl.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/gradient
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/img
[3]: https://developer.mozilla.org/es/docs/Web/CSS/background
