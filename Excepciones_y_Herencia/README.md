# EX_01

La clase "NegativeNumberException" hereda de la clase "Exception" y tiene dos constructores: uno sin parámetros y otro que recibe un mensaje personalizado.
En el "main" utilizamos un bloque "try-catch" para utilizar excepciones. El programa realiza los siguientes pasos:

- Solicita al usuario que ingrese un número entero.
- Si el número ingresado es negativo, se lanza la excepción "NegativeNumberException" con un mensaje que indica que el número es negativo.
- Si el usuario ingresa un valor que NO es numérico, se captura la excepción "InputMismatchException" y se muestra un mensaje indicando que hay un ERROR.
- Si no se producen excepciones, se imprime el número ingresado en la consola.

En el bloque "catch", se captura "NegativeNumberException" si se lanza, y se muestra un mensaje de ERROR que incluye el mensaje personalizado de la excepción.

# EX_02

La excepción del tipo "RuntimeException" es especial porque es una excepción no verificada en Java, lo que significa que no es necesario manejarla explícitamente en el código, aunque puede causar errores en la ejecución del programa si no se maneja adecuadamente.

# EX_03

El programa define un array de enteros "array" con una longitud de 5 elementos.
Los índices válidos para este array son; 0,1,2,3 y 4.
Dentro del bloque "try", se intenta acceder al elemento en la posición 10 del array "int valor = array[10]; " lo que está más allá de los límites válidos del array.
Como resultado se produce una excepción de tipo "ArrayIndexOutOfBoundsException", que es capturada en el bloque "catch".
En dicho bloque (catch), se muestra un mensaje que indica ERROR y que incluye info de la excepción capturada.

# EX_04

El programa comienza solicitando al usuario un número entero utilizando un objeto Scanner.
Se utiliza un bucle while para repetir el proceso hasta que se ingrese una entrada válida.
Dentro del bucle, se utiliza un bloque try-catch para manejar excepciones. El programa realiza lo siguiente:

- Solicita al usuario ingresar un número entero.
- Intenta calcular el cuadrado del número.
- Si el usuario ingresa un valor que no es un número entero, se captura la excepción InputMismatchException.
- Se muestra un mensaje de error y se limpia el buffer de entrada con scanner.nextLine() para evitar ciclos infinitos.
- Si se ingresa una entrada válida, se muestra el cuadrado del número y se establece entradaValida en true, lo que termina el bucle.

Finalmente, se cierra el objeto Scanner para liberar recursos.

# EX_05

El programa comienza solicitando al usuario ingresar dos números y un operador matemático.
Utilizamos un bloque "try-catch" para manejar excepciones. El programa realiza los siguientes pasos:

- Solicita al usuario ingresar el 1r número y verifica que sea válido.
- Solicita al usuario ingresar un operador matemático válido; (+,-,*,/).
- Solicita al usuario ingresar el 2ndo número y verifica que sea válido.
- Realiza la operación matemática correspondiente y muestra el resultado.
- Maneja excepciones como "InputMismatchException" si el usuario ingresa valores NO numéricos, "ArithmeticException" si el usuario ingresa valores NO numéricos, "ArithmeticException" si se intenta dividir por cero y "IllegalArgumentException" si el operador NO és válido.

El bloque "finally" garantiza que el objeto "Scanner" se cierre correctamente para liberar recursos.

