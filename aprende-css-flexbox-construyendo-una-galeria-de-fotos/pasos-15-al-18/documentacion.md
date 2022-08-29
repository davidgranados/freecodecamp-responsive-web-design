# Proyecto Aprende Flexbox creando una galería de fotos

Puedes notar como algunas de tus imágenes se ven un poco distorsionadas.
Esto se debe a que las imágenes tienen diferentes dimensiones. En lugar de asignarle a cada imagen una dimensión de manera individual, puedes utilizar la propiedad [object-fit][1] para determinar cómo deberían comportarse las imágenes.

Utilizando el valor `cover` el contenido reemplazado se dimensiona para mantener su relación de aspecto mientras llena el cuadro de contenido completo del elemento. Si la relación de aspecto del objeto no coincide con la relación de aspecto de su caja, entonces el objeto se recortará para que se ajuste.

La propiedad [align-items][2] posiciona el contenido a lo largo del eje transversal. En este caso, con la propiedad `flex-direction` en `row`, tu eje transversal debería ser el vertical.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/object-fit
[2]: https://developer.mozilla.org/es/docs/Web/CSS/align-items
