# Pseudo-clases y la pseudo-clase `:not()`

Una pseudoclase es una **palabra clave** que se añade a los selectores y que especifica un estado especial del elemento seleccionado. Estas, junto con los pseudoelementos, permiten aplicar un estilo a un elemento no sólo en relación con el contenido del árbol de documento ([DOM][2]), sino también en relación a factores externos como el historial del navegador, el estado de su contenido, o la posición del ratón.

El pseudo-selector [`:not`][1] puede ser utilizado para seleccionar todos los elementos que **no coincidan** con una regla CSS dada. Como evita que se seleccionen elementos específicos, se le conoce como la pseudoclase de negación.

>

    div:not(#ejemplo) {
        background-color: #303030;
    }

El ejemplo de arriba selecciona todos los elementos `<div>` que **no tengan** un id igual a `ejemplo` y cambia su color de fondo.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/:not
[2]: https://developer.mozilla.org/es/docs/Glossary/DOM
