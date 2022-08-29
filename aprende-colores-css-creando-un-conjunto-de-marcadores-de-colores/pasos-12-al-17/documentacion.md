# Proyecto Marcadores de Colores con CSS

Parecerá que el marcador no tiene ningún color. El cambio a la propiedad [background-color][1] fue aplicado correctamente, pero ya que el elemento [`<div>`][2] está vacío, no ocupa ningún espacio en la página (sus propiedades [width][3] y [height][4] por defecto no existen).

Tu marcador podría verse mejor si estuviese centrado en la página. Una manera fácil de hacer esto es con la abreviatura para la propiedad margin.

En el proyecto anterior, cambiaste el margen de los elementos por separado, utilizando propiedades como `margin-top` y `margin-bottom`. La abreviatura de la propiedad [margin][5] hace más fácil asignar multiples valores a los diferentes margenes al mismo tiempo.

A pesar de que tienes tres elementos `<div>` separados, pareciera que fuesen un solo rectángulo. Deberías agregar algo de espacio entre ellos para que sea más fácil identificar cada elemento.

Hay una abreviatura para la propiedad `margin` que toma dos valores, el primer valor se asigna al `margin-top` y `margin-bottom` y el segundo valor para el `margin-left` y `margin-right`. Por ejemplo:

>

    div {
        margin: 15px 10px;
    }

Le estaría dando 15px a los márgenes superior e inferior y 10px a los márgenes laterales de los elementos `<div>`.

Habrás aprendido en la escuela que los colores primarios son: amarillo, azul y rojo, y aprendiste como crear nuevos colores a partir de sus combinaciones. Sin embargo, esto es algo anticuado.

Ahora, hay dos modelos de color principales: el aditivo RGB (acrónimo de rojo, verde y azul en inglés) que es utilizado en los dispositivos electrónicos y el sustractivo CMYK (de cian, magenta, amarillo y negro) utilizado en las impresoras. En este proyecto, trabajaremos con el modelo [RGB][6].

[1]: https://developer.mozilla.org/es/docs/Web/CSS/background-color
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/div
[3]: https://developer.mozilla.org/es/docs/Web/CSS/width
[4]: https://developer.mozilla.org/es/docs/Web/CSS/height
[5]: https://developer.mozilla.org/es/docs/Web/CSS/margin
[6]: https://developer.mozilla.org/es/docs/Glossary/RGB
