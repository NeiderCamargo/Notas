Introducción a los diccionarios en Python:
[[Tablas]]
[[Listas]]
Los diccionarios son una estructura de datos en Python que permiten almacenar información en pares clave-valor. Cada clave debe ser única y se utiliza para acceder al valor asociado con ella. Los diccionarios son mutables, es decir, se pueden modificar añadiendo o eliminando elementos.
#SintaxisDiccionarios
#FuncionesDiccionarios
Para crear un diccionario en Python, se utiliza la sintaxis de llaves {}. Dentro de las llaves se especifican los pares clave-valor separados por dos puntos (:), y cada par está separado por comas (,). Por ejemplo:

```
mi_diccionario = {"nombre": "Juan", "edad": 30, "ciudad": "Madrid"}
```

En este ejemplo, el diccionario tiene tres pares clave-valor: "nombre" con el valor "Juan", "edad" con el valor 30 y "ciudad" con el valor "Madrid".

Para acceder a un valor en un diccionario, se utiliza la clave correspondiente dentro de corchetes []. Por ejemplo:

```
print(mi_diccionario["edad"])
```

Este código imprimirá el valor 30.

También es posible modificar o añadir elementos a un diccionario utilizando la misma sintaxis. Por ejemplo:

```
mi_diccionario["profesión"] = "programador"
mi_diccionario["edad"] = 31
```

El primer código añade un nuevo par clave-valor al diccionario con la clave "profesión" y el valor "programador". El segundo código modifica el valor asociado a la clave "edad" a 31.

Los diccionarios son muy útiles para almacenar información estructurada y acceder a ella de forma eficiente mediante claves únicas.
#FuncionesDiccionarios
Funciones de los diccionarios en Python con ejemplos:

1. Acceder a un valor: Los diccionarios en Python permiten acceder a un valor asociado con una clave específica. Esto se realiza mediante el uso de corchetes y la clave correspondiente.

Ejemplo:

```
datos = {"nombre": "Ana", "edad": 25, "ciudad": "Madrid"}
print(datos["nombre"]) # salida: Ana
```

2. Añadir elementos: También es posible agregar nuevos elementos a un diccionario existente simplemente asignándoles una nueva clave y valor.

Ejemplo:

```
datos = {"nombre": "Ana", "edad": 25, "ciudad": "Madrid"}
datos["telefono"] = "123456789"
print(datos) # salida: {"nombre": "Ana", "edad": 25, "ciudad": "Madrid", "telefono":"123456789"}
```

3. Actualizar elementos: Si se desea actualizar uno o varios valores de un diccionario, basta con asignar el nuevo valor a la clave correspondiente.

Ejemplo:

```
datos = {"nombre": "Ana", "edad": 25, "ciudad" : "Madrid"}
datos["edad"] = 26
print(datos) # salida: {"nombre":"Ana","edad":26,"ciudad":"Madrid"}
```

4. Eliminar elementos: Se puede eliminar elementos de un diccionario utilizando la palabra reservada `del` seguida de la clave que se desea eliminar.

Ejemplo:

```
datos = {"nombre":"Ana","edad":26,"ciudad":"Madrid"}
del datos["ciudad"]
print(datos) # salida: {"nombre":"Ana","edad":26}
```

5. Iterar sobre los elementos del diccionario: Es posible iterar sobre los elementos de un diccionario utilizando un bucle `for`. En cada iteración, la variable de control tomará el valor de una clave del diccionario.

Ejemplo:

```
datos = {"nombre":"Ana","edad":26,"ciudad":"Madrid"}
for clave in datos:
  print(clave, datos[clave])
# salida: 
# nombre Ana
# edad 26
# ciudad Madrid
```

6. Obtener todas las claves o valores del diccionario: Se pueden obtener todas las claves o valores de un diccionario utilizando

los métodos keys() y values() respectivamente.

Ejemplo:

```
mi_diccionario = {'nombre': 'Juan', 'edad': 25, 'ciudad': 'Madrid'}
print(mi_diccionario.keys()) # ['nombre', 'edad', 'ciudad']
print(mi_diccionario.values()) # ['Juan', 25, 'Madrid']
```

También se puede obtener una lista de tuplas que contienen ambas cosas utilizando el método items():

```
print(mi_diccionario.items()) # [('nombre', 'Juan'), ('edad', 25), ('ciudad', 'Madrid')]
```

De esta manera se pueden acceder a todas las claves y valores del diccionario para realizar operaciones o manipulaciones con ellos.