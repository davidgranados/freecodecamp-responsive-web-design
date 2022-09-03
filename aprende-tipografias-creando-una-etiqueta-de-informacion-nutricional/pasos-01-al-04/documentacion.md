# Elemento `<link>` y vincular estilos al HTML

Dentro del elemento `<head>` suelen colocar elementos que brindan información adicional al navegador y motores de búsqueda (conocida también como metainformación), pero también se utiliza para agregar elementos que permiten vincular recursos externos como hojas de estilo CSS. El elemento que ayuda con este propósito es el [`<link>`][1], en el cual se utiliza el atributo `href` para indicar la dirección URL en la cual se encuentra este recurso que deseamos vincular con nuestro HTML.

Por ejemplo, podemos vincular la hoja de estilos `styles.css` en la raíz de nuestro proyecto de la siguiente manera:

>

    <link rel="stylesheet" href="./styles.css" />

[1]: https://developer.mozilla.org/es/docs/Web/HTML/Element/link
