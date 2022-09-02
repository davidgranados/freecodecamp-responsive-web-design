# Propiedad `transform` y función `rotate()`

Podemos modificar las coordenadas de los elementos HTML a través de la propiedad [`transform`][1], la cual permite trasladar, rotar, escalar o sesgar el elemento donde se aplique, dependiendo de del valor que se le aplique.

Entre los valores que puede recibir esta propiedad, están funciones como `translate()`, `scale()` o `rotate()`.

En estos pasos estaremos utilizando la función `rotate()`.

La función `rotate()` define una rotación 2D de un elemento, específicando la cantidad de grados (`deg`) que se rotará en sentido de las agujas del reloj (o en sentido inverso, dependiendo de la magnitud del valor en grados).

Por ejemplo:

>

    #elemento1 {
        transform: rotate(90deg);
    }

    #elemento2 {
        transform: rotate(-45deg);
    }

En este ejemplo, el `#elemento1` estaría siendo rotado 90 grados en sentido de las agujas del reloj, mientras que el `#elemento2` se rotaría 45 grados en sentido contrario a las agujas del reloj.

[1]: https://developer.mozilla.org/es/docs/Web/CSS/transform
