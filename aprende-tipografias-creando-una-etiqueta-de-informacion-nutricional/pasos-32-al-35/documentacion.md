# Propiedad `overflow`

Cuando el contenido de un elemento sobrepasa sus límites o bordes, se conoce como un desbordamiento o excedencia. Este comportamiento se puede controlar a través de la propiedad de CSS [`overflow`][1], la cual tiene varios valores posibles para tratar estos desbordamientos. Podemos recortar el contenido, crear barras de desplazamiento en el contenedor o mostrar todo el contenido que se desborda del elemento en un bloque de la página.

Algunos ejemplos de uso de esta propiedad son los siguientes:

>

    #elemento1 {
        overflow: hidden;
    }

    #elemento2 {
        overflow: scroll;
    }

    #elemento3 {
        overflow: auto;
    }

[1]: https://developer.mozilla.org/es/docs/Web/CSS/overflow
