Metodo Integracion numerica

La integración numérica constituye una amplia gama de algoritmos para calcular el valor numérico de una integral definida y, por extensión, el término se usa a veces para describir algoritmos numéricos para resolver ecuaciones diferenciales. El término cuadratura numérica (a menudo abreviado a cuadratura) es más o menos sinónimo de integración numérica, especialmente si se aplica a integrales de una dimensión a pesar de que para el caso de dos o más dimensiones (integral múltiple) también se utiliza.
Hay varias razones para llevar a cabo la integración numérica. La principal puede ser la imposibilidad de realizar la integración de forma analítica. Es decir, integrales que requerirían de un gran conocimiento y manejo de matemática avanzada pueden ser resueltas de una manera más sencilla mediante métodos numéricos. Incluso existen funciones integrables pero cuya primitiva no puede ser calculada, siendo la integración numérica de vital importancia. La solución analítica de una integral nos arrojaría una solución exacta, mientras que la solución numérica nos daría una solución aproximada. El error de la aproximación, que depende del método que se utilice y de qué tan fino sea, puede llegar a ser tan pequeño que es posible obtener un resultado idéntico a la solución analítica en las primeras cifras decimales.
Los métodos de integración numérica pueden ser descritos generalmente como combinación de evaluaciones del integrando para obtener una aproximación a la integral. Una parte importante del análisis de cualquier método de integración numérica es estudiar el comportamiento del error de aproximación como una función del número de evaluaciones del integrando. Un método que produce un pequeño error para un pequeño número de evaluaciones es normalmente considerado superior. Reduciendo el número de evaluaciones del integrando se reduce el número de operaciones aritméticas involucradas, y por tanto se reduce el error de redondeo total. También, cada evaluación cuesta tiempo, y el integrando puede ser arbitrariamente complicado.

De todos modos, un modo de integración por «fuerza bruta» puede hacerse siempre, de un modo muy simplista, evaluando el integrando con incrementos muy pequeños.