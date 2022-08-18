# Estructura-de-datos-y-Algoritmos

- Big Os-

O(1) - Constantes (No loops)
O(log N) -  Logaritmico - Usualmente se usa para buscar algoritmos que tienen log n si ellos son sorted (Ordenados) (Binary Search)
O(n) - Lineales - (For, loops, while, loops que contengan n items)
O(n log(n)) -  Log lineal - Usualmente operaciones para clasificar
O(n¨2) - Cuadrático: cada elemento de una colección debe compararse con cualquier otro elemento. Dos bucles anidados
O(2¨n) -  Exponenciales - Algoritmos recursivos que resuelven un problema de tamaño N
O(n!) - Factorial: está agregando un bucle para cada elemento

1) Iterar a través de la mitad de una colección sigue siendo O (n)
2) Dos colecciones separadas: O(a * b)

-¿Qué puede causar el tiempo en una función?-

Operaciones (+, -, *, /) 
Comparadores (<, >, ==)
Bucles (for, while) 
Llamada de función externa (function())

-Rule Book-
Regla 1: Siempre en el peor de los casos
Regla 2: Eliminar constantes
Regla 3: Diferentes entradas deben tener diferentes variables. O(a+b). 
Los arreglos A y B anidados serían O(a*b) + para los pasos en orden * para los pasos anidados
Regla 4: Elimina los términos no dominantes

-¿Qué causa la complejidad del espacio?-
Variables
Estructuras de datos
Funciones de llamada
Allocations

