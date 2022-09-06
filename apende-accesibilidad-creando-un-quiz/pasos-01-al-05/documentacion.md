# Estructura básica del documento HTML

El atributo global [lang][1] permite definir el lenguaje del elemento, el lenguaje en que están escritos los elementos no editables o el lenguaje en el cual los elementos editables deberían de estar escritos.

El elemento [`<meta>`][2] es utilizado para especificar información relacionada con la página, como el título, descripción, palabras clave y autor.

Por ejemplo, el atributo `charset` especifica el set de caracteres con el que se codifica la página, y, actualmente, `utf-8` es el único soportado por la mayoría de los navegadores.

Continuando con los elementos `<meta>`, la definición para el `viewport` indica al navegador cómo renderizar la página. Incluyendo mejoras de visualización en móviles, mejoras para **SEO** (acrónimo para optimización de motores de búsqueda en inglés).

Otro elemento `<meta>` importante para el SEO es uno que defina la descripción de la página, esto se logra a través del tributo `name` con el valor `description`. Adicionalmente, el valor del atributo `content` es utilizado por los motores de búsqueda para proporcionar la descripción de la página web.

Por último, otro elemento que se utiliza dentro del [`<head>`][3], es el elemento [`<title>`][4]. Este es bastante útil para que los lectores de pantalla puedan _"entender"_ el contexto de la página. Además, es un elemento importante para el SEO.

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes/lang
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/meta
[3]: https://developer.mozilla.org/es/docs/Web/HTML/Element/head
[4]: https://developer.mozilla.org/es/docs/Web/HTML/Element/title
