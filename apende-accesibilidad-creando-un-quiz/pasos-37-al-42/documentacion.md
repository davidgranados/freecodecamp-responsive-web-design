# Elementos `<textarea>`, `<button>`, `<footer>` y `<address>`

## `<textarea>`

El elemento [`<textarea>`][1] representa un control para edición multilínea de texto, a diferencia de los `<input>`, se puede indicar un número de filas y columnas por defecto para este elemento, a través de sus atributos `rows` y `cols`. Este tipo de elementos se suele utilizar cuando necesitamos que el usuario ingrese una cantidad de texto considerable, como por ejemplo una sección de comentarios en un formulario.

## `<button>`

Para poder enviar los datos que se han ingresado en un formulario, nuestra interfaz necesita un elemento que permita realizar esta acción, por eso, HTML nos proporciona el elemento [`<button>`][3]. Este elemento es el encargado de hacer el envío de los datos cuando el usuario haga click en él para que esta información pueda ser procesada.

Pero para poder crear un botón de envío del formulario, este debe tener el atributo `type` con el valor `submit`, para indicar que esa es la finalidad de nuestro elemento `<button>`.

## `<footer>` y `<address>`

Los dos últimos elementos HTML con **importancia semántica** en este proyecto son el [`<footer>`][3] y el [`<address>`][4]. El elemento `<footer>` es un contenedor para una colección de contenido que está relacionado a la página, y el elemento `<address>` es un contenedor para información de contacto sobre el autor de la página.

Dentro del elemento `<footer>` se suele colocar información y/o enlaces relacionados con el contenido de la página, pero que no forman parte del contenido principal de la misma, así como información sobre los datos del autor o desarrolladores.

El elemento `<address>` no necesita contener una dirección física o ubicación geográfica. Puede ser utilizado para proporcionar un enlace relacionado al tema o asunto.

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/textarea
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/button
[3]: https://developer.mozilla.org/es/docs/Web/HTML/Element/footer
[4]: https://developer.mozilla.org/es/docs/Web/HTML/Element/address
