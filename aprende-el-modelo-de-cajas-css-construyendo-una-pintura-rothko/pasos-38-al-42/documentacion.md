# Propiedades `border-radius` y `box-shadow`

Podemos modificar las esquínas o vértices de los elementos HTML a través de la propiedad `border-radius`, la cual permite redondear este aspecto de nuestros elementos en función del valor que le asignemos. Podemos darle un valor para crear esquinas circulares o a partir de dos valores para crear esquinas elípticas.

Un ejemplo de uso de esta propiedad sería:

>

    #elemento1 {
        border-radius: 25px;
    }

    #elemento2 {
        border-radius: 15% 25%;
    }

    #elemento3 {
        border-radius: 10% 30% 25% 40%;
    }

En el primer caso, se aplica el mismo valor a las 4 esquinas de el `#elemento1`, en en `#elemento2` se modificarían las esquinas superior izquierda e inferior derecha en `15%` y las esquinas opuestas en `25%`. Por último, se modifican las esquias superior izquierda, superior derecha, inferior derecha e inferior izquierda (sentido de las agujas del reloj) para el `#elemento3` con los valores correspondientes.

Otra propiedad que vamos a utilizar es [box-shadow][1], la cual permite añadir efectos de sombra alrededor del marco de un elemento.

Esta propiedad puede recibir varios valores, dependiendo de la forma en cómo se desee aplicar el estilo. Los cuales pueden ser palabras clave (`none`, `inherit`, `initial` y `unset`), unidades de longitud absolutas y relativas e incluso funciones como `rgb()` / `rgba()` y `hsl()` / `hsla()` para el color que se desee aplicar a la sombra.

>

    #elemento1 {
        box-shadow: none;
    }

    #elemento2 {
        box-shadow: 3px 5px 7px black;
    }

    #elemento3 {
        box-shadow: 5px 5px 8px 3px rgba(0, 0, 0, 0.3);
    }

En este ejemplo, para el `#elemento1` no se estaría aplicando la propiedad.

En el caso del `#elemento2` se pasan tres valores de longitud y el valor para el color de la propiedad. Estos tres valores, el primero corresponde al eje X o eje horizontal (desplazamiento de la sombra en este eje), y el segundo corresponde al eje Y o eje vertical. El segundo valor corresponde al `blur-radius`, el cual indica la difuminación de la sombra, mientras mayor sea este valor, más grande será la sombra, si no se indica por defecto se asigna `0`.

En el último caso del `#elemento3` se asigna un cuarto valor adicional, el cual representa el `spread-radius`. Este valor se encarga de indicar qué tanto se expande o reduce el efecto de sombra dependiendo de la magnitud del valor (positiva expande, negativa reduce), al igual que el `blur-radius`, si no se indica su valor, por defecto es `0`.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/box-shadow
