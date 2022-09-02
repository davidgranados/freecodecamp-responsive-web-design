# Vincular estilos CSS y crear selectores de clase

Para vincular hojas de estilo CSS a nuestro HTML, debemos utilizar un elemento [`<link>`][1], el cual a través del atributo `href` indica la dirección URL donde se encuentra este recurso externo. Adicionalmente, contamos con el atributo `rel` el cual indica el tipo de relación que tiene este elemento externo con el documento HTML, en el caso de las hojas de estilo, el valor que se le asigna es `stylesheet`.

Agregar una [clase][2] a un elemento en HTML permite dar estilos específicos o particulares a los elementos que cuenten con este valor en su atributo `class`. Por ejemplo, un elemento `<span>` con la clase `clase-ejemplo` se vería de la siguiente manera:

>

    <span class="clase-ejemplo">Contenido del elemento</span>

Y para aplicar estilos unicamente a ese elemento con la clase `clase-ejemplo` se podría crear el siguiente selector de clase:

>

    .clase-ejemplo {
        font-size: 16px;
    }

Con esa regla, modificaríamos el tamaño de la fuente de los elementos que tengan como clase la `clase-ejemplo`.

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/link
[2]: https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes/class
