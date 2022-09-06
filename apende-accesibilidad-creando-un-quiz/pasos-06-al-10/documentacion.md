# Importancia semántica de los elementos HTML y manipulación de imágenes con `CSS`

La navegación es parte fundamental de la accesibilidad, y los lectores de pantalla se apoyan en que tú, como desarrollador, proporciones la estructura necesaria a tu página. Esto se logra con los elementos HTML que proporcionan la semántica, esto quiere decir, que tienen importancia y/o significado dentro de la estructura de nuestra página, lo que permite organizar de mejor manera el contenido.

Un elemento semántico de HTML, por ejemplo, es el [`<header>`][1], el cual es utilizado comunmente para presentar la página y darle un menú de navegación. O también el elemento [`<main>`][2] en el cual se coloca el contenido principal de la página y es único en el documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda.

Una propiedad útil de los [SVG][3] (acrónimo de _Scalable Vector Graphics_) es que contienen un atributo path, que permite a la imagen ser escalada sin afectar la resolución del resultado.

La propiedad `aspect-ratio` indica cual es el radio de aspecto preferido para ser aplicado al elemento HTML (caja), el cual es utilizado para realizar el cálculo de la modificación del tamaño dinámico y otras funciones relacionadas con el diseño. En este proyecto, nuestro logo debería mantener un radio de `16 / 9` en su aspecto, y un `padding` alrededor del texto.

Por último, vamos hacer uso de [`flexbox`][4], el cual es un método de diseño para organizar los elementos de una manera responsiva dentro de nuestra página.

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/header
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/main
[3]: https://developer.mozilla.org/es/docs/Web/SVG
[4]: https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Flexbox
