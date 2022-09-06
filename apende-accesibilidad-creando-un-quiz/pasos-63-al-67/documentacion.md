# media queries, `scroll-behavior` y atajos de teclado

## media queries y `scroll-behavior`

Hacer click en los enlaces de navegación debería cambiar el `viewport` a una sección relevante. Sin embargo, este salto puede desorientar a algunos
usuarios.

La propiedad [`scroll-behavior`][1] especifica el comportamiento del desplazamiento para un elemento con desplazamiento, cuando éste se produce debido a la navegación. Otros desplazamientos, como aquellos realizados por el usuario, no se ven afectados por esta propiedad. Si esta propiedad está especificada en el elemento raíz, se aplica a todo el `viewport`.

Las [media queries][2] se utilizan para aplicar estilos condicionales o indicar medios específicos a elementos. Son especialmente útiles cuando se desea modificar la página web o aplicación en función de un tipo de dispositivo o de alguna característica específica. Para aplicar los estilos condicionales, se utilizan reglas como `@import` y [`@media`][3].

### La regla `@media`

Esta regla asocia un grupo de declaraciones anidadas, en un bloque CSS delimitado por llaves, con una condición definida por un media query. La regla-at `@media` puede ser usada no solo en el nivel superior de la hoja de estilos, sino también dentro de cualquier grupo de reglas conditionales.

Cuando dentro de ella se aplica el valor adicional `no-preference` a su propiedad `prefers-reduced-motion`, se solicita al sistema que se minimice la cantidad de movimiento no esencial aplicado como efectos o estilos CSS a algunos elementos.

## Atajos de teclado en HTML

El atributo [`accesskey`][4] acepta una lista, separada por espacios, de claves de acceso y así provee un indicio para generar un atajo de teclado para el elemento actual. El explorador usa el primero que existe en la distribución del teclado de la computadora . Por ejemplo:

>

    <button type="submit" accesskey="s">Enviar</button>

[1]: https://developer.mozilla.org/es/docs/Web/CSS/scroll-behavior
[2]: https://developer.mozilla.org/es/docs/Web/CSS/Media_Queries/Using_media_queries
[3]: https://developer.mozilla.org/es/docs/Web/CSS/@media
[4]: https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes/accesskey
