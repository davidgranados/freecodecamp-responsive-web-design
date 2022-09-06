# Elementos `<input>`, `<label>` y tipografía.

Los elementos [`<input>`][1] se utilizan para crear controles interactivos para formularios basados en la web con el fin de recibir datos del usuario. Es importante vincular cada `<input>` con su elemento [`<label>`][2] correspondiente. Esto proporciona a los usuarios de tecnologías asistivas referencias visuales para las entradas de datos.

Esto se logra dándole al atributo `for` del elemento `<label>` el valor del atributo `id` del `<input>`.

Adicionalmente, cada elemento `<input>` cuenta también con otros atributos como `type` y `name`. A través del `type` podemos indicar al navegador el tipo de dato que estamos esperando recibir en ese campo e incluso algunos tipos cuentan con validaciones nativas en el navegador, para asegurarse que el formato de datos ingresado en el campo coincida con el tipo que se está indicando antes de realizar el envío del formulario. También existe el atributo `placeholder`, que se utiliza para brindar al usuario información sobre el tipo de dato o el formato en el que esperamos recibir ese dato en el campo especificado a través de un texto provisional que es mostrado en el elemento `<input>` donde se haya aplicado el atributo.

La [tipografía][3] juega un rol importante en la accesibilidad de una página. Algunas fuentes son más fáciles de leer que otras, y esto es especialmente notable en pantallas de baja resolución. Se puede controlar los tipos de letra que se aplican en el HTML con la propiedad [`font-family`][4]. Este atributo toma uno o más nombres familias de fuentes y el navegador recorre esta lista hasta que encuentra un tipo de letra disponible en el sistema en el que se ejecuta.

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/input
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/label
[3]: https://developer.mozilla.org/es/docs/Learn/CSS/Styling_text/Web_fonts
[4]: https://developer.mozilla.org/es/docs/Web/CSS/font-family
