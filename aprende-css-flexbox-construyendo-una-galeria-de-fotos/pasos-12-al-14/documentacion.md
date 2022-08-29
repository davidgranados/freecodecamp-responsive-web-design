# Proyecto Aprende Flexbox creando una galería de fotos

Podrás ver que Flexbox tiene **dos ejes**, el _eje principal_ y el _eje transversal_. El eje principal está determinado por la propiedad
[flex-direction][1]. Si esta propiedad tiene el valor `row` o `row-reverse`,
el eje principal es **horizontal**. Si su valor es `column` o `column-reverse`,
el eje principal es **vertical**.

![Ejes Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox/flex_terms.png "Ejes Flexbox")

Notarás que todas las imágenes se han movido a la misma fila. La propiedad [flex-wrap][2] es la que determina cómo deben comportarse los elementos cuando el contenedor es demasiado pequeño. Establecer esta propiedad a `wrap` permitirá que sus elementos se ajusten a la siguiente
fila/columna (dependiendo de cual sea el eje principal), y su valor
`nowrap` evitará que sus elementos se ajusten. Cuando se asigna el valor
`nowrap`, los elementos podrán encogerse para ajustarse o desbordarse del contenedor.

La propiedad [justify-content][3] determina cómo se van a posicionar los elementos dentro de un contenedor `flex` a lo largo de su eje principal, afectando su posición y el espacio alrededor de ellos.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/flex-direction
[2]: https://developer.mozilla.org/es/docs/Web/CSS/flex-wrap
[3]: https://developer.mozilla.org/es/docs/Web/CSS/justify-content
