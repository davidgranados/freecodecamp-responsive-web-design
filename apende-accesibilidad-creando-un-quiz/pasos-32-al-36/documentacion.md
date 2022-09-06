# Botones `radio`, elemento `<select>` y pseudo-elemento `::before`

Uno de los tipos que se le puede dar a los elementos `<input>` es el `radio`, los cuales permiten agrupar un conjunto de opciones entre las cuales se pueda seleccionar **únicamente** una de ellas.

Podemos crear elementos desplegables con un grupo de opciones a elegir entre las posibles respuestas a una pregunta, utilizando la etiqueta [`<select>`][1]. Dentro de estas etiquetas estarán las respuestas posibles mostradas mediante elementos [`<option>`][2], de las cuales se podrá seleccionar solo una de ellas.

En CSS contamos también con [pseudo-elementos][3], los cuales permiten añadir estilos a una parte del documento HTML, añadiendose a los selectores de tipo y modificando al que cumpla con la descripción de dicho pseudo-elemento.

Por ejemplo, el pseudo-elemento [`::before`][4] toma el primer hijo del elemento seleccionado y aplica el contenido que se asigne a su propiedad [`content`][5].

El modo en el que se utiliza es el siguiente:

>

    a::before {
        content: "Nuevo contenido agregado en el elemento <a>".
    }

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/select
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Element/option
[3]: https://developer.mozilla.org/es/docs/Web/CSS/Pseudo-elements
[4]: https://developer.mozilla.org/es/docs/Web/CSS/::before
[5]: https://developer.mozilla.org/es/docs/Web/CSS/content
