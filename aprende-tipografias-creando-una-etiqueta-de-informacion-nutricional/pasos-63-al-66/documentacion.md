# La propiedad `text-indent`

Esta propiedad asigna la longitud del espacio vacío o en blanco (indentación) que se debe colocar antes del texto en un bloque.
Los valores que se pueden ser asignados en las medidas de longitud válidas de CSS (absolutas y relativas), además de dos valores adicionales: `each-line`, el cual afecta la primera línea del bloque contenedor así como la siguiente línea que venga luego de un _break line_ y el `hanging`, que invierte las líneas que serán indentadas. **Todas** las líneas _excepto_ la primera serán indentadas.

Un ejemplo de uso de esta propiedad puede ser el siguiente:

>

    #elemento1 {
        text-indent: 0;
    }

    #elemento2 {
        text-indent: 25%;
    }

    #elemento3 {
        text-indent: 4em each-line;
    }
