# Contraste entre elementos y `aspect-ratio`

## Contraste

Sobre el tema de accesibilidad visual, el [contraste][1] entre elementos es un factor clave. Por ejemplo, el contraste entre el texto y el color de
fondo de un encabezado debe ser por lo menos 4.5:1.

Esto es debido a que así garantizamos la legibilidad entre el contenido en primer plano (habitualmente texto) y su fondo.

Las relaciones de contraste recomendadas por las directrices de la WCAG (acrónimo de Web Content Accessibility Guidelines), es el siguiente:

| Tipo de Contenido                                                                       | Relación mínima (nivel AA) | Relación mejorada (nivel AAA) |
| --------------------------------------------------------------------------------------- | :------------------------: | :---------------------------: |
| Cuerpo de texto                                                                         |          4.5 : 1           |             7 : 1             |
| Texto a gran escala (120-150% mayor que el cuerpo de texto)                             |           3 : 1            |            4.5 : 1            |
| Componentes activos de la interfaz de usuario y objetos gráficos como iconos y gráficos |           3 : 1            |          No definido          |

## `aspect-ratio`

La propiedad de CSS `aspect-ratio` indica el radio de aspecto principal a aplicar al elemento (caja), el cual será utilizado a partir del calculo de redimensionamiento y otras funciones de diseño.

Este es especificado como un valor `<ratio>`, que representa el radio de aspecto en medida ancho por alto del `viewport`. Es una medida de rango, lo que significa que
también puedes utilizar variantes prefijadas como `min-aspect-ratio` y `max-aspect-ratio` para asignar valores mínimos y máximos, respectivamente.

Algunos de valores utilizados comunmente para esta propiedad son, 1:1 (cuadrado), 4:3 (pantalla estándar), 14:9 y 16:10 (estándar) y 16:9 (pantallas amplias).

[1]: https://developer.mozilla.org/es/docs/Web/Accessibility/Understanding_WCAG/Perceivable/Color_contrast
