# Informe de Phyton #

*Python es un lenguaje de programación interpretado cuya filosofía hace hincapié en una sintaxis que favorezca un código legible. Se trata de un lenguaje de programación multiparadigma, ya que soporta orientación a objetos, programación imperativa y, en menor medida, programación funcional.*

## If:

Puede haber cero o más bloques elif, y el bloque else es opcional. La palabra reservada ‘elif‘ es una abreviación de ‘else if’, y es útil para evitar un sangrado excesivo. Una secuencia if ... elif ... elif ... sustituye las sentencias switch o case encontradas en otros lenguajes.

Ejemplo:  
<pre>x = int(input("Ingresa un entero, por favor: "))
Ingresa un entero, por favor: 42
    if x < 0:
      x = 0
      print('Negativo cambiado a cero')
    elif x == 0:
      print('Cero')
    elif x == 1:
      print('Simple')
    else:
      print('Más')

'Mas'</pre>

## Funciones:

<pre>def fib(n):  # escribe la serie de Fibonacci hasta n  
"""Escribe la serie de Fibonacci hasta n."""  
     a, b = 0, 1  
     while a < n:  
          print(a, end=' ')  
          a, b = b, a+b  
         print()</pre>
La palabra reservada def se usa para definir funciones. Debe seguirle el nombre de la función y la lista de parámetros formales entre paréntesis.  
Las sentencias que forman el cuerpo de la función empiezan en la línea siguiente, y deben estar con sangría.

La primer sentencia del cuerpo de la función puede ser opcionalmente una cadena de texto literal; esta es la cadena de texto de documentación de la función, o docstring.

Hay herramientas que usan las docstrings para producir automáticamente documentación en línea o imprimible, o para permitirle al usuario que navegue el código en forma interactiva; es una buena práctica incluir docstrings en el código que uno escribe, por lo que se debe hacer un hábito de esto.

## Ciclos:  
En python hay solo dos tipos de loops o ciclos y son los ciclos while y los ciclos for.  
## While:
El bloque de código se ejecutará mientras se cumpla la condición (mientras sea verdadera).  
Ejemplo de while:  
<pre> 
x = 0
while x < 10:
    x = x + 1
print x </pre>  
El código hará que aumente x hasta ser 10 y lo imprima.

## For:
El bloque de código se ejecutará mientras no acabe de recorrer la lista. El valor de variable será el item de la lista que está siendo tratado en el momento.  
Ejemplo de for:  
<pre>
for i in range(-9, 10):
    print i </pre>
=======

## Imprimir En Pantalla

*En Informática, la "salida" de un programa son los datos que el programa proporciona al exterior.  
Aunque en los incios de la informática la salida más habitual era una impresora, hace muchos años que el dispositivo de salida más habitual es la pantalla del ordenador.*

### La Funcion **print()**

En los programa, para mostrar texto o variables hay que utilizar la función **print()**.

La función **print()** permite mostrar texto en pantalla. El texto a mostrar se escribe como argumento de la función:

`print("Hola Mundo")`

**NOTA**: Las cadenas se pueden delimitar tanto por comillas dobles (") como por comillas simples (').

La función **print()** admite varios argumentos seguidos. En el programa, los argumentos deben separarse por comas.  
Los argumentos se muestran en el mismo orden y en la misma línea, separados por espacios:

`print("Hola", "Adios")`

Al final de cada **print()**, Python añade automáticamente un salto de línea:

<pre>print("Hola")
print("Adios")</pre>

Para generar una línea en blanco, se puede escribir una orden **print()** sin argumentos.

<pre>print("Hola")
print()
print("Adios")</pre>

Si no se quiere que Python añada un salto de línea al final de un **print()**, se debe añadir al final el argumento end="":

<pre>print("Hola", end="")
print("Adios")</pre>

En el ejemplo anterior, las dos cadenas se muestran pegadas. Si se quieren separar los argumentos en la salida, hay que incluir los espacios deseados (bien en la cadena, bien en el argumento end):

<pre>print("Hola. ", end="")
print("Adios")</pre>

<pre>print("Hola", end=" ")
print("Adios")</pre>
