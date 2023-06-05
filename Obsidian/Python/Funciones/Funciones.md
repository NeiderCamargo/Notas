[[Tipos de datos]]
Las funciones son bloques de código que se pueden reutilizar en un programa para realizar una tarea específica. En Python, las funciones se definen utilizando la palabra clave "def" seguida del nombre de la función y los parámetros de entrada entre paréntesis. Las funciones pueden devolver un valor utilizando la palabra clave "return". 

Las funciones en Python son muy útiles ya que permiten modularizar el código y hacerlo más legible y fácil de mantener. Además, las funciones también pueden ser utilizadas para reducir la repetición de código y mejorar la eficiencia del programa.

En general, las funciones en Python se utilizan para realizar tareas como cálculos matemáticos, manipulación de cadenas de texto, operaciones con archivos, entre otras.
#Parametros
#LlamadoDeFunciones

Las funciones en Python siguen la siguiente sintaxis general:

```
def nombre_funcion(parametro1, parametro2, ...):
    # Cuerpo de la función
    # Puede incluir uno o más comandos
    return resultado
```

Donde:

- `def` es la palabra clave para definir una función.
- `nombre_funcion` es el nombre que le das a la función. Debe seguir las reglas de nomenclatura de Python.
- `parametro1`, `parametro2`, etc. son los parámetros que puede recibir la función. Pueden ser opcionales y tener un valor por defecto.
- El cuerpo de la función incluye los comandos que deben ejecutarse cada vez que se llama a la función.
- La palabra clave `return` indica el valor que debe devolver la función. Si no se especifica, la función devuelve `None`.

Ejemplo:

```python
def suma(a, b):
    resultado = a + b
    return resultado
```

Esta función recibe dos parámetros (`a` y `b`) y devuelve su suma.

#Parametros
#LlamadoDeFunciones 
funciones con parámetros y sin parámetros:

Las funciones son bloques de código que se utilizan para realizar una tarea específica dentro de un programa. Pueden tomar uno o varios parámetros, o no tomar ninguno. 

Una función sin parámetros es aquella que no recibe ningún tipo de dato al ser llamada. Su sintaxis es la siguiente:

```
func nombreDeLaFuncion() {
    // código a ejecutar
}
```

Por ejemplo, una función sin parámetros podría ser:

```
func imprimirHola() {
    print("Hola")
}
```

Esta función simplemente imprime en consola la palabra "Hola".

Por otro lado, una función con parámetros es aquella que recibe uno o varios valores al ser llamada. Su sintaxis es la siguiente:

```
func nombreDeLaFuncion(parametro1: TipoDeDato, parametro2: TipoDeDato) {
    // código a ejecutar
}
```

Por ejemplo, una función con parámetros podría ser:

```
func multiplicar(_ numero1: Int, por numero2: Int) -> Int {
    return numero1 * numero2
}
```

Esta función recibe dos valores enteros y devuelve su multiplicación. El primer parámetro se llama "_ numero1" para indicar que no tiene etiqueta externa al llamar a la función (es decir, se utiliza directamente el valor), mientras que el segundo parámetro se llama "por numero2" para indicar que al llamar a la función se debe especificar qué valor corresponde a cada parámetro.

En resumen, las funciones pueden tener o no tener parámetros y su sintaxis varía según los mismos. 

#LlamadoDeFunciones 
Cómo se llama una función en Python

Una función en Python se llama mediante su nombre, seguido de paréntesis, que pueden o no contener argumentos. Por ejemplo:

```
def mi_funcion(argumento1, argumento2):
    # Código de la función
    return resultado

mi_funcion(valor1, valor2)
``` 

En este caso, `mi_funcion` es el nombre de la función.