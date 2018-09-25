# Informe de Phyton #

*Python es un lenguaje de programación interpretado cuya filosofía hace hincapié en una sintaxis que favorezca un código legible. Se trata de un lenguaje de programación multiparadigma, ya que soporta orientación a objetos, programación imperativa y, en menor medida, programación funcional.*

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
l bloque de código se ejecutará mientras no acabe de recorrer la lista. El valor de variable será el item de la lista que está siendo tratado en el momento.  
Ejemplo de for:  
<pre>
for i in range(-9, 10):
    print i </pre>

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
