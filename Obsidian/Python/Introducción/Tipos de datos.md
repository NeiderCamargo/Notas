[[Funciones]]

- #Datos
- #Escriba 
- #Variables
- #Operadores
- #ConversiónDeDatos
1. Quiero que generes una tabla con los tipos de datos de Python

| Tipo de dato | Descripción |
|--------------|-------------|
| int          | Entero      |
| float        | Decimal     |
| complex      | Complejo    |
| bool         | Booleano    |
| str          | Cadena de caracteres |
| list         | Lista       |
| tuple        | Tupla       |
| set          | Conjunto    |
| dict         | Diccionario |

Nota: existen otros tipos de datos en Python, pero estos son los más utilizados.

#Escriba
2. Cómo se ingresan datos en Python

En Python, se pueden ingresar datos utilizando la función input(). Esta función solicita al usuario que ingrese un valor y lo devuelve como una cadena de caracteres. Por ejemplo:

```
nombre = input("Ingrese su nombre: ")
```

En este ejemplo, la función input() solicita al usuario que ingrese su nombre y lo devuelve como una cadena de caracteres que se asigna a la variable nombre. Para ingresar valores numéricos, es necesario convertirlos al tipo de dato correspondiente utilizando las funciones int() o float(). Por ejemplo:

```
edad = int(input("Ingrese su edad: "))
```

En este caso, la función input() devuelve una cadena de caracteres que se convierte a un valor entero utilizando la función int() y se asigna a la variable edad.
#Variables 
3. Cómo trabajar con Variables en Python
En Python, las variables se pueden definir y asignar valores de la siguiente manera:

```
nombre_de_variable = valor_de_variable
```

Por ejemplo, para asignar el valor 10 a una variable llamada "x", se puede escribir:

```
x = 10
```

Las variables pueden contener diferentes tipos de datos, como números enteros, números decimales, cadenas de texto, listas, diccionarios y más. El tipo de dato que contiene una variable se determina automáticamente en función del valor que se le asigna.

Para acceder al valor almacenado en una variable, simplemente se puede llamar por su nombre. Por ejemplo:

```
print(x)
```

Esto imprimirá el valor 10 en la pantalla.

También es posible realizar operaciones con variables. Por ejemplo:

```
y = x + 5
print(y)
```

Esto primero suma 5 a la variable "x" y luego asigna el resultado a la variable "y". Luego imprime el valor de "y" en la pantalla (que sería 15).

En resumen, trabajar con variables en Python es muy sencillo: solo hay que definirlas y asignarles valores adecuados para luego realizar operaciones con ellas según sea necesario.
#String
Para manejar cadenas de texto o String en Python, se pueden utilizar diversas funciones y métodos. Algunas de las más comunes son:

- len(): devuelve la longitud de la cadena.
- upper(): convierte la cadena a mayúsculas.
- lower(): convierte la cadena a minúsculas.
- split(): divide la cadena en una lista de subcadenas separadas por un delimitador.
- join(): concatena una lista de cadenas utilizando un delimitador.
- replace(): reemplaza todas las ocurrencias de una subcadena por otra subcadena.
- find(): busca la posición en que aparece una subcadena dentro de otra cadena.

Por ejemplo:

```
texto = "Hola Mundo"
print(len(texto)) # 10
print(texto.upper()) # HOLA MUNDO
print(texto.split()) # ['Hola', 'Mundo']
print("-".join(texto.split())) # Hola-Mundo
print(texto.replace("Mundo", "Python")) # Hola Python
print(texto.find("Mundo")) # 5
```

También se pueden acceder a los caracteres individuales de una cadena utilizando índices:

```
texto = "Hola"
print(texto[0]) # H
print(texto[-1]) # a
```

Y se pueden realizar operaciones aritméticas con cadenas, como concatenarlas utilizando el operador +:

```
texto1 = "Hola"
texto2 = "Mundo"
saludo = texto1 + " " + texto2
print(saludo) # Hola Mundo
```

#Operadores 
4. Operadores matemáticos y lógicos de Python
#Logicos
Python cuenta con una gran variedad de operadores matemáticos y lógicos que permiten realizar diferentes operaciones. A continuación, se detallan algunos de ellos:

Operadores matemáticos:
- Suma (+): realiza la suma de dos valores.
- Resta (-): realiza la resta de dos valores.
- Multiplicación (*): realiza la multiplicación de dos valores.
- División (/): divide el valor del primer operando por el del segundo operando.
- División entera (//): devuelve el resultado entero de la división entre dos valores.
- Módulo (%): devuelve el resto de la división entre dos valores.
- Potencia (**): eleva un valor a una potencia determinada.

#Logicos 
Operadores lógicos:
- Igualdad (==): comprueba si dos valores son iguales.
- Diferencia (!= o <>): comprueba si dos valores son diferentes.
- Mayor que (>), menor que (<), mayor o igual que (>=), menor o igual que (<=): comprueban si un valor es mayor, menor, mayor o igual, o menor o igual a otro valor respectivamente.
- Y (and): devuelve True si ambos operandos son verdaderos.
- O (or): devuelve True si al menos uno de los operandos es verdadero.
- No (not): niega el valor del operando.

Estos son solo algunos ejemplos de los operadores matemáticos y lógicos disponibles en Python. Existen otros como los operadores bitwise (&, |, ^) y los operadores de asignación extendida (+=, -=, *=, /=). Es importante conocerlos para poder utilizarlos adecuadamente en nuestros programas.

#ConversiónDeDatos 
4. Convertir tipos de datos en Python

En Python, se pueden convertir los tipos de datos utilizando las siguientes funciones:

1. int(): convierte un valor en un número entero.
2. float(): convierte un valor en un número de punto flotante.
3. str(): convierte un valor en una cadena de caracteres.
4. list(): convierte un valor en una lista.
5. tuple(): convierte un valor en una tupla.
6. set(): convierte un valor en un conjunto.
7. dict(): convierte un valor en un diccionario.

Por ejemplo, para convertir una cadena de caracteres a un número entero se puede utilizar la función int():

```
numero = "10"
numero_entero = int(numero)
print(numero_entero)
```

Este código imprimirá el número 10, que es el resultado de convertir la cadena "10" a un número entero utilizando la función int().
