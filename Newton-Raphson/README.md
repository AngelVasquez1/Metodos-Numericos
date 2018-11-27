Newton-Raphson

El método de Newton-Raphson “es un método iterativo que nos permite aproximar la solución de una ecuación del tipo f(x) = 0. Partimos de una estimación inicial de la solución x0 y construimos una sucesión de aproximaciones de forma recurrente mediante la fórmula:

xj+1 =xj − f(xj).

El método como entrada requiere tu aproximación inicial a la raíz (X0), la función a evaluar (f(x)), su derivada (f'(x)), el error absoluto (en nuestro caso sería Tolerancia) y como opcional el número máximo de iteraciones que hará el método.

Criterio de detención del método:

Caso 1: Si aproximación inicial (X0) sea tu raíz.

Caso2: Cuando el método encuentra la raíz dada una aproximación inicial válida.

Caso3 (Opcional): Cuando el programa no encuentra la raíz y se termina el número de iteraciones máximas que tiene el programa.

Caso 4: Si el método al buscar la raíz de una función que no es continua o tiene asíntota, no le es posible encontrar una raíz y se indetermina.

Caso 5: Dada una función se puede llegar a circular si se le da un valor inicial donde se en lugar de acercarse a la raíz, se aleje de ella y continué iterando un infinito número de veces.
