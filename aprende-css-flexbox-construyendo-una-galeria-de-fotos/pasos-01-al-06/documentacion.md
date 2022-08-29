# Proyecto Aprende Flexbox creando una galería de fotos

Para crear un documento HTML se debe partir de la declaración [!DOCTYPE][1], la cual permite indicar al navegador el tipo de documento y versión del lenguaje que se está utilizando.

Seguido de esta declaración, se debe crear un elemento [`<html>`][2], dentro del cual se deben colocar los demás elementos que conformarán nuestra página y es la raíz principal del código.

Dos elementos importantes que se deben agregar dentro de nuestro `<html>` son el [`<head>`][3] y el [`<body>`][4]. El elemento `<head>` brinda información importante al navegador y los motores de búsqueda, que esté relacionada con nuestra página web. El `<body>` es el elemento que contiene el resto de los elementos que se mostrarán dentro de nuestra página (contenido) y que será mostrado en el navegador.

Un elemento que se coloca dentro del `<head>` es el [`<meta>`][5]. Este elemento puede brindar diferente información al navegador dependiendo del atributo que se coloque en la etiqueta. Por ejemplo, cuando se utiliza el atributo `charset` se indica el set de caracteres que se utilizará en la página web.

Cuando se utiliza el atributo `name` con el valor `viewport` se indica que deseamos que nuestra página pueda implementar un [diseño responsive][6], el cual se puede adaptar a diferentes dispositivos y tamaños de pantalla sin perder el diseño que hayamos dado a la página.

Para vincular hojas de estilo CSS a nuestro HTML, debemos utilizar un elemento [`<link>`][7], el cual a través del atributo `href` indica la dirección URL donde se encuentra este recurso externo.

[1]: https://developer.mozilla.org/es/docs/Glossary/Doctype
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/html
[3]: https://developer.mozilla.org/es/docs/Web/HTML/Element/html
[4]: https://developer.mozilla.org/es/docs/Web/HTML/Element/body
[5]: https://developer.mozilla.org/es/docs/Web/HTML/Element/meta
[6]: https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Responsive_Design
[7]: https://developer.mozilla.org/es/docs/Web/HTML/Element/link
