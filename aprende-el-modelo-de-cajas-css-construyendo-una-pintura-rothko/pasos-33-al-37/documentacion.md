# Función `blur()` de CSS

En CSS contamos con algunas funciones para aplicar estilos o cambios a las propiedades. Una función no es más que una porción de código reutilizable que se encarga de realizar alguna tarea o cálculo por nosotros y muchas veces estas ya vienen implementadas en el lenguaje.

Una de estas funciones es la función [blur][1], la cual permite crear un efecto de desenfoque o difuminado sobre el elemento. Esta función se aplica como valor a la propiedad [filter][2] y debe recibir un valor (medida de longitud) sobre el cual se realiza el cálculo y aplica el estilo.

Por ejemplo:

>

    #mi-elemento {
        background-color: #404040;
        width: 300px;
        height: 300px;
        filter: blur(4px);
    }

Estaríamos creando un efecto de desenfoque en el elemento con el id `mi-elemento` en `4px`.

También podríamos crear una lista de selectores para aplicar esta propiedad a más de un elemento:

>

    h1, p {
        filter: blur(3px);
    }

Con esta regla CSS, estaríamos aplicando este estilo a los elementos `h1` y `p` en la página.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/filter-function/blur
[2]: https://developer.mozilla.org/es/docs/Web/CSS/filter
