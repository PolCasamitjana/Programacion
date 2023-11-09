# EX_01

La clase "NegativeNumberException" hereda de la clase "Exception" y tiene dos constructores: uno sin parámetros y otro que recibe un mensaje personalizado.
En el "main" utilizamos un bloque "try-catch" para utilizar excepciones. El programa realiza los siguientes pasos:

- Solicita al usuario que ingrese un número entero.
- Si el número ingresado es negativo, se lanza la excepción "NegativeNumberException" con un mensaje que indica que el número es negativo.
- Si el usuario ingresa un valor que NO es numérico, se captura la excepción "InputMismatchException" y se muestra un mensaje indicando que hay un ERROR.
- Si no se producen excepciones, se imprime el número ingresado en la consola.

En el bloque "catch", se captura "NegativeNumberException" si se lanza, y se muestra un mensaje de ERROR que incluye el mensaje personalizado de la excepción.
