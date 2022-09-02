# Unidades de longitud absolutas y relativas

En CSS podemos utilizar varias [unidades de longitud][1] para dimensionar los elementos, estas se dividen en **absolutas** y **relativas**.

Las longitudes **absolutas** no varían sin importar el contexto en el cual se encuentre el elemento, siempre se mantendrá del mismo tamaño.

Las longitudes **relativas** pueden variar, por ejemplo, en función del tamaño de letra del elemento principal donde se encuentre contenido el elemento a aplicar los estilos. Podemos ver el siguiente ejemplo:

>

    <body>
        <p>Soy un parrafo</p>
    </body>

>

    body {
        font-size: 20px;
    }

    p {
        font-size: 1.2em;
    }

En este caso, el tamaño de la fuente del elemento `p` es calculado en función del tamaño de la fuente de su contenedor `body`, por defecto el navegador aplica el valor de `16px` como tamaño de las fuentes, en este caso, nuestro `body` tiene una fuente de `20px` y el tamaño de la fuente del párrafo sería algo de `24px` (20 \* 1.2).

[1]: https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/Values_and_units
