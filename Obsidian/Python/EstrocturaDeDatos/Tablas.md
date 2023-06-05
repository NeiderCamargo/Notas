Una pequeña introducción a las tabas en Python

[[Diccionarios]]
[[Listas]]
Las tablas en Python se refieren a una estructura de datos que se utiliza para almacenar y organizar información en filas y columnas. También se les conoce como matrices o arrays en otros lenguajes de programación.

En Python, las tablas pueden ser creadas utilizando la lista o el módulo NumPy. Las listas son una forma simple de crear tablas, donde cada elemento de la lista representa una fila y los elementos dentro de esa fila representan las columnas.

El módulo NumPy es una biblioteca de Python que proporciona soporte para la creación y manipulación avanzada de tablas. Permite crear tablas multidimensionales que pueden tener cualquier número de filas y columnas, y también proporciona funciones para realizar cálculos matemáticos complejos en ellas.

Las tablas son útiles para almacenar grandes cantidades de datos estructurados, como información de ventas, resultados deportivos o datos científicos. Con Python, podemos realizar operaciones complejas en estos datos utilizando técnicas avanzadas como el análisis estadístico y el aprendizaje automático.
#SintaxisTablas
#FuncionesMatrices 
#RecorrerMatrices 
Sintaxis de las matrices en Python

En Python, una matriz se puede representar mediante una lista de listas. Cada lista interna representa una fila de la matriz y cada elemento de dicha lista representa un elemento de la columna correspondiente.

Por ejemplo, la siguiente matriz:

| 1 | 2 | 3 |
|---|---|---|
| 4 | 5 | 6 |

puede ser representada en Python de la siguiente manera:

```
matriz = [[1, 2, 3], [4, 5, 6]]
```

Para acceder a un elemento específico de la matriz se utilizan los índices correspondientes a la fila y columna. Por ejemplo, para acceder al elemento en la segunda fila y tercera columna (valor 6) se utiliza:

```
valor = matriz[1][2] # fila=1, columna=2
```

#FuncionesMatrices
Acceder, Modificar, Agregar y eliminar elementos de la matriz con ejemplos:

Acceder a elementos de la matriz:

Para acceder a un elemento específico de una matriz, se utiliza el índice correspondiente al elemento. Los índices en las matrices comienzan en cero y van hasta el número total de elementos menos uno.

Por ejemplo, si tenemos la siguiente matriz:

```
matriz = [[1, 2, 3],
          [4, 5, 6],
          [7, 8, 9]]
```

Podemos acceder al segundo elemento de la primera fila (el número 2) utilizando el siguiente código:

```
print(matriz[0][1])
```

Modificar elementos de la matriz:

Para modificar un elemento específico de una matriz, se utiliza el índice correspondiente al elemento y se asigna un nuevo valor.

Por ejemplo, si queremos cambiar el valor del tercer elemento de la segunda fila (el número 6) por el número 10, podemos hacerlo con el siguiente código:

```
matriz[1][2] = 10
print(matriz)
```

Esto imprimirá la matriz actualizada:

```
[[1, 2, 3],
 [4, 5, 10],
 [7, 8, 9]]
```

Agregar elementos a la matriz:

En Python no es posible agregar nuevos elementos a una matriz después de que ésta ha sido creada. Lo que se puede hacer es crear una nueva matriz con más elementos y copiar los valores existentes a ella.

Por ejemplo, si queremos agregar otra fila a nuestra matriz anterior para obtener lo siguiente:

```
matriz = [[1, 2, 3],
          [4, 5, 6],
          [7, 8, 9],
          [10 ,11 ,12]]
```

Podemos crear una nueva matriz y copiar los valores existentes utilizando el siguiente código:

```
matriz2 = [[1, 2, 3],
           [4, 5, 6],
           [7, 8, 9],
           [10 ,11 ,12]]

print(matriz2)
```

Eliminar elementos de la matriz:

Para eliminar un elemento específico de una matriz, es necesario crear una nueva matriz sin ese elemento.

Por ejemplo, si queremos eliminar la segunda fila de nuestra matriz anterior para obtener lo siguiente:

```
matriz = [[1, 2, 
```

#RecorrerMatrices
Recorrer Matrices en Python:

Para recorrer una matriz en Python, se pueden utilizar ciclos for anidados. El primer ciclo for recorrerá las filas de la matriz y el segundo ciclo for recorrerá las columnas de la fila actual. Por ejemplo:
```
matriz = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]

for i in range(len(matriz)):
    for j in range(len(matriz[i])):
        print(matriz[i][j])
```

Este código imprimirá los elementos de la matriz en orden: 1, 2, 3, 4, 5, 6, 7, 8 y 9.

También se puede utilizar un solo ciclo for con la función "enumerate" para recorrer los elementos de la matriz. Por ejemplo:
```
matriz = [[1, 2, 3], [4, 5, 6], [7, 8, 9]]
for i_fila in matriz:
    for j_columna in i_fila:
        print(j_columna)
```
Este código también imprimirá los elementos de la matriz en orden: 1, 2, 3, 4, 5,6 ,7 ,8 y9.