# Proyecto Aprende Flexbox creando una galería de fotos

Todos los elementos en HTML son tratados como una caja por el CSS, y por defecto el navegador aplica ciertos valores a estos elementos en sus propiedades del [modelo de cajas][1]. Cuando reiniciamos o eleminamos estos valores por defecto en los elementos, se conoce como _normalizar_ el modelo de cajas, para lograr esto, debemos asignar el valor `border-box` a la propiedad [box-sizing][2].

Podemos modificar todos los elementos dentro de nuestro código HTML a través del selector universal de CSS que es representado por el caracter [\*][3].

También podemos seleccionar elementos que estén contenidos dentro de otros elementos de una manera más específica a través del [selector de descendientes][4]. Por ejemplo, si tuviesemos elementos `<p>` dentro de un `<div>` con el id `#ejemplo`, podríamos seleccionar únicamente estos párrafos a través del siguiente selector de descendientes:

>

    #ejemplo p {
        propiedad: valor;
    }

Estos selectores son especialmente útiles cuando queremos seleccionar elementos específicos de una sección de nuestra página, sin modificar o aplicar esos estilos a otros elementos del mismo tipo.

[Flexbox][5] es un enfoque de diseño unidimensional de CSS, que se centra en el flujo del contenido. Ofrece la capacidad de controlar la forma en la que los elementos se alínean y distribuyen dentro de un contenedor.

Para configurar un elemento como Flexbox, se le asigna a su propiedad `display` el valor `flex`.

[1]: https://developer.mozilla.org/es/docs/Learn/CSS/Building_blocks/The_box_model
[2]: https://developer.mozilla.org/es/docs/Web/CSS/box-sizing
[3]: https://developer.mozilla.org/es/docs/Web/CSS/Universal_selectors
[4]: https://developer.mozilla.org/es/docs/Web/CSS/Descendant_combinator
[5]: https://developer.mozilla.org/es/docs/Learn/CSS/CSS_layout/Flexbox
