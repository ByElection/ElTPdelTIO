# Informe de Phyton #

## Funciones:

def fib(n):  # escribe la serie de Fibonacci hasta n  
"""Escribe la serie de Fibonacci hasta n."""  
     a, b = 0, 1  
     while a < n:  
          print(a, end=' ')  
          a, b = b, a+b  
         print()
La palabra reservada def se usa para definir funciones. Debe seguirle el nombre de la función y la lista de parámetros formales entre paréntesis.  
Las sentencias que forman el cuerpo de la función empiezan en la línea siguiente, y deben estar con sangría.

La primer sentencia del cuerpo de la función puede ser opcionalmente una cadena de texto literal; esta es la cadena de texto de documentación de la función, o docstring.

Hay herramientas que usan las docstrings para producir automáticamente documentación en línea o imprimible, o para permitirle al usuario que navegue el código en forma interactiva; es una buena práctica incluir docstrings en el código que uno escribe, por lo que se debe hacer un hábito de esto.

