# Atributos `WAI-ARIA Roles`

Como esto es un quiz, vas a necesitar un formulario para que los usuarios puedan enviar sus respuestas. Puedes separar semánticamente el contenido dentro del formulario utilizando elementos [`<section>`][1].

Para incrementar la accesibilidad de la página, se puede utilizar el atributo `role` para indicar el propósito de un elemento en la página para efectos de tecnologías de asistencia. El atributo `role` es parte de la **Iniciativa de Accesibilidad Web** (WAI en inglés) y acepta valores preestablecidos.

Todo elemento con el atributo `role region` necesita una etiqueta visible, la cual debe ser referenciada a través del atributo `aria-labelledby`. El atributo `role` con el valor `region` es utilizado para identificar áreas del documento que el autor considere importantes. Es una marca genérica disponible para ayudar en la navegación cuando ninguna otra marca para el `role` es la adecuada.

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/section
