# Reiniciar el modelo de cajas a través del selector universal `*`

Cuando modificamos las propiedades `padding` y `border`, el valor que le demos será sumado al ancho y alto (`width` y `height`) de nuestro elemento. Por ejemplo:

>

    div {
        width: 300px;
        height: 250px;
        padding: 5px;
        border: 2px solid black;
    }

Podríamos pensar que el tamaño de nuestro `<div>` es de 300x250, pero en realidad es de 314x264, ya que se le debe sumar el espacio que ocupa su `padding` y el que ocupa su `border` por cada lado del elemento.

Para evitar que el navegador realice este calculo, podemos reiniciar el [modelo de caja][1] creando el selector universal [`*`][2] para que los estilos colocados apliquen a todos los elementos en el HTML y dándole el valor `border-box` a su propiedad [`box-sizing`][3].

[1]: https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model
[2]: https://developer.mozilla.org/es/docs/Web/CSS/Universal_selectors
[3]: https://developer.mozilla.org/es/docs/Web/CSS/box-sizing
