# Propiedades `padding`, `border` y `overflow`

Cuando modificamos las propiedades `padding` y `border`, el valor que le demos será sumado al ancho y alto (`width` y `height`) de nuestro elemento. Por ejemplo:

>

    div {
        width: 300px;
        height: 250px;
        padding: 5px;
        border: 2px solid black;
    }

Podríamos pensar que el tamaño de nuestro `<div>` es de 300x250, pero en realidad es de 314x264, ya que se le debe sumar el espacio que ocupa su `padding` y el que ocupa su `border` por cada lado del elemento.

Una forma de evitar que calcule el tamaño de nuestro elemento de esta forma, es utilizando la propiedad [overflow][1]. Esta propiedad permite especificar si recortar contenido, dibujar barras de desplazamiento o mostrar el contenido excedente en un elemento a nivel de [bloque][2].

Uno de los valores que podemos dar a la propiedad `overflow` es `hidden`, con el cual el contenido es recortado y no se muestran barras de posición.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/overflow
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Block-level_elements
