# Modelo de Cajas

Para crear un documento HTML se debe partir de la declaración [`!DOCTYPE`][1], la cual permite indicar al navegador el tipo de documento y versión del lenguaje que se está utilizando.

Seguido de esta declaración, se debe crear un elemento [`<html>`][2], dentro del cual se deben colocar los demás elementos que conformarán nuestra página y es la raíz principal del código.

Dos elementos importantes que se deben agregar dentro de nuestro `<html>` son el [`<head>`][3] y el [`<body>`][4]. El elemento `<head>` brinda información importante al navegador y los motores de búsqueda, que esté relacionada con nuestra página web. El `<body>` es el elemento que contiene el resto de los elementos que se mostrarán dentro de nuestra página (contenido) y que será mostrado en el navegador.

Un elemento que se coloca dentro del `<head>` es el [`<meta>`][5]. Este elemento puede brindar diferente información al navegador dependiendo del atributo que se coloque en la etiqueta. Por ejemplo, cuando se utiliza el atributo `charset` se indica el set de caracteres que se utilizará en la página web. El valor `utf-8` hace referencia a la codificación de caracteres más común en la red. El número de bytes que representan un carácter pueden ser desde uno hasta cuatro. UTF-8 es retrocompatible con ASCII y puede representar cualquier carácter Unicode estandar.

En el [modelo de cajas][6] de CSS, todos los elementos HTML son tratados como una caja con cuatro áreas. comprender estas cajas es clave para poder crear diseños con CSS o para alinear elementos con otros elementos.

En el siguiente diagrama podemos ver las propiedades con las que cuentan los elementos HMTL en el modelo de cajas. Podemos notar que desde la parte interna tenemos el **contenido**, el cual a su vez cuenta con un ancho y un alto ([height][7] y [width][8]).

![Diagrama 1](https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-1.png "Diagrama 1")

Luego, vemos que también contamos con las propiedades [padding][9], el cual representa el espacio que existe entre el contenido del elemento y el borde del mismo. La propiedad [border][10] es la que define las características del borde y a través de ella es que podemos aplicar estilos personalizados al mismo.

![Diagrama 2](https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-2.png "Diagrama 2")

Por último, contamos con la propiedad [margin][11], la cual representa el espacio que rodea al elemento a partir de su borde y lo separa del resto de los elementos que lo rodean en la página.

![Diagrama 3](https://cdn.freecodecamp.org/curriculum/css-box-model/diagram-3.png "Diagrama 3")

[1]: https://developer.mozilla.org/es/docs/Glossary/Doctype
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/html
[3]: https://developer.mozilla.org/es/docs/Web/HTML/Element/html
[4]: https://developer.mozilla.org/es/docs/Web/HTML/Element/body
[5]: https://developer.mozilla.org/es/docs/Web/HTML/Element/meta
[6]: https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model
[7]: https://developer.mozilla.org/es/docs/Web/CSS/height
[8]: https://developer.mozilla.org/es/docs/Web/CSS/width
[9]: https://developer.mozilla.org/es/docs/Web/CSS/padding
[10]: https://developer.mozilla.org/es/docs/Web/CSS/border
[11]: https://developer.mozilla.org/es/docs/Web/CSS/margin
