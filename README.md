This program was made for solve this 9 problems 

Ejercicio 1: Lee lista y muestra
Diseña y codifica un programa en Python en el cual el usuario ingrese la cantidad de elementos que va a ingresar a la lista, posteriormente el programa debe leer cada uno de los elementos de la lista, uno por línea y se van agregando a la lista.

Importante: El programa debe validar que el número de elementos a ingresar sea mayor que cero, sino debe volver a pedir el valor hasta que cumpla.


Entradas

Número entero n que corresponde al número de elementos a ingresar a la lista. Debe ser mayor a 0 de lo contrario se solicitará de nuevo hasta que se cumpla la condición.

Posteriormente se reciben los n elementos de la lista, uno en cada renglón.

Salidas

El programa debe desplegar los elementos ingresados en formato de estructura de la lista:

lista[0] = 1

lista[1] = 2

lista[2] = 3

lista[3] = 4

lista[4] = 5

Posteriormente el programa debe desplegar el último elemento.

Después el programa debe desplegar la suma de todos los elementos de la lista.

Por último, el programa debe desplegar el promedio de todos los elementos de la lista.

Ejemplo de ejecución de un programa

>>> 5

>>> 1

>>> 2

>>> 3

>>> 4

>>> 5

lista[0] = 1

lista[1] = 2

lista[2] = 3

lista[3] = 4

lista[4] = 5

5

15

3.0

 

 

Ejercicio 2 : Lee lista y muestra invertida
Diseña y codifica un programa en Python en el cual el usuario ingrese la cantidad de n elementos que va a tener la lista, posteriormente el programa debe leer cada uno de los n elementos, línea por línea y se van agregando a la lista. El programa debe validar que n sea mayor que cero sino debe volver a pedir el valor hasta que cumpla.

 

Entradas

Número entero n que corresponde al número de elementos a ingresar a la lista. Debe ser mayor a 0 de lo contrario se solicitará de nuevo hasta que se cumpla la condición.

Posteriormente se reciben los n elementos de la lista (números enteros), uno en cada renglón.

Salidas

El programa debe desplegar los elementos ingresados en forma inversa, el indice mayor al menor y en el siguiente formato:

lista[-1] = 5

lista[-2] = 4

lista[-3] = 3

lista[-4] = 2

lista[-5] = 1

Posteriormente el programa debe desplegar el valor mayor de todos los elementos de la lista:

Después el programa debe desplegar el valor menor de todos los elementos de la lista:

Por último, el programa debe desplegar la lista ordenada de menor a mayor.

Ejemplo de ejecución del programa

>>> 5

>>> 1

>>> 2

>>> 3

>>> 4

>>> 5

lista[-1] = 5

lista[-2] = 4

lista[-3] = 3

lista[-4] = 2

lista[-5] = 1

5

1

[1, 2, 3, 4, 5]

 

 

Ejercicio 3: Contar pares o impares en una lista simple
Desarrolla el programa que determine el total de valores pares e impares de una lista de números enteros que recibirá en su entrada. Los valores los captura el usuario uno por uno, se van almacenando en una lista y posteriormente se analizará la lista para determinar cuantos valores pares e impares posee. Consideramos al 0 como par.

 

Entrada

Cero o más valores enteros, uno en cada renglón. Finaliza la captura con un *

Salida

Se despliega el número de pares e impares que tiene la lista con el siguiente formato: PARES=3 ó IMPARES=2, cada uno en un renglón. Es decir, la palabra PARES seguido de un = y luego un número que representa el número de pares en la lista, posteriormente la palabra IMPARES, seguido de un = y luego el número que representa el número de impares que hay en la lista. Cada mensaje en un renglón y en ese orden.

Ejemplo de ejecución del programa

>>> 6

>>> 0

>>> 1

>>> 2

>>> *

PARES=3

IMPARES=1

 

>>> *

PARES=0

IMPARES=0

 

Ejercicio 4 : Lista al cuadrado
Escribe un programa que reciba del usuario un número entero que representa la cantidad de números que va a ingresar. El programa deberá recibir esa cantidad de números enteros, los colocará en una lista y la desplegará a pantalla. Posteriormente deberá construir una nueva lista, con el cuadrado de cada uno de los elementos de la lista del usuario.

 

Entradas

Un número entero que representa la cantidad de números enteros que quiere ingresar.

Números enteros, uno en cada línea y de acuerdo a la cantidad anterior.

Salida

Se imprime la lista con los números ingresados por el usuario.

Se imprime la lista creada con los números del usuario al cuadrado

Ejemplos de ejecución del programa

>>> 5

>>> 2

>>> 4

>>> 5

>>> 8

>>> 10

[2, 4, 5, 8, 10]

[4, 16, 25, 64, 100]

 

>>> 0  ---- o algún negativo

[ ]

[ ]

 

Ejercicio 5 : Cuántas empiezan con...
Escribe un programa determine cuántas palabras de una lista empiezan con una determinada letra.

 

Entrada

5 palabras y una letra, en ese orden y cada una en un renglón.

Salida

Un número entero que represente la cantidad de palabras que empiezan con la letra ingresada. Debe contabilizar sin importar si la palabra está en mayúsculas o minúsculas.

Ejemplo de ejecución del programa

>>> Hola

>>> Mundo

>>> hermoso

>>> Estamos

>>> listos

>>> h

2

 

Ejercicio 5 : Suma dos listas por posición
Desarrolla un programa que permita realizar la suma elemento a elemento de dos listas de números enteros y con la misma cantidad de elementos.

 

Entradas

Un número entero que indica cuántos elementos tendrá cada lista. El número debe ser mayor a 0.

Posteriormente el ingreso de los números enteros correspondientes a los elementos de las dos listas. Por ejemplo, si en la primera entrada se ingresa un 5, después del 5 se reciben 10 números más (uno en cada renglón) 5 para conformar cada lista.

Salida

Si el número inicial ingresado es 0 o menor, deberá desplegar el mensaje "Error"

Una lista donde los elementos corresponde a la suma de los elementos de las dos listas de acuerdo con su posición, es decir los elementos de la posición 0 de las dos listas se suman y se ponen en la posición 0 de la lista resultado y así consecutivamente para todos los datos de la lista.

Ejemplo de ejecución del programa:

>>> 2

>>> 5

>>> 3

>>> 4

>>> 2

[9, 5]

 

>>> -3

Error

 

 

Ejercicio 6 : Sublistas de pares e impares
Desarrolla un programa que permitirá obtener a partir de una lista que recibirá del usuario, crear y desplegar una sublista con valores pares y otra sublista con valores impares.

 

Entrada

Cero o más valores enteros, uno en cada renglón. Finaliza la captura con un *

Salida

Se muestra la salida que deberá mostrar tu programa, tal como se ilustra a continuación:

PARES

[2, 4, 8]

IMPARES

[1, 5]

(Es decir, la palabra PARES en mayúscula en un renglón y posteriormente el despliegue la lista de pares y de manera similar los impares, tal como se muestra en el ejemplo) Respeta el orden.

Ejemplos de ejecución del programa

>>> 2

>>> 4

>>> 1

>>> 8

>>> 5

>>> *

PARES

[2, 4, 8]

IMPARES

[1, 5]

 

>>> *

PARES

[]

IMPARES

[]

 

 

Ejercicio 7 : Pares y posición
Escribe un programa que lea la cantidad de elementos que vas a ingresar de la lista,

posteriormente cada uno de los elementos de la lista que son números enteros.

El programa después debe revisar la lista y para cada uno de los valores pares que encuentre mostrar un mensaje que contenga la posición y el valor del numero par. Observa los ejemplos.

 

Entrada

Un número entero que representa la cantidad de valores que tiene la lista

Cada uno de los valores de la lista

Salida

Un mensaje para cada uno de los valores pares encontrados en la lista. El mensaje debe tener el formato:

pos XX, valor XX      <--- Observa que va la palabra pos seguida de un número, después una coma, luego la palabra valor y luego otro número

Ejemplo de ejecución del programa:

>>>5

>>>1

>>>2

>>>3

>>>4

>>>5

pos 1, valor 2

pos 3, valor 4

 

 

Ejercicio 8 : Sin duplicados
Escribe un programa que reciba del usuario una lista y devuelva otra con los elementos de la lista original, pero sin elementos duplicados.

 

Entradas

Se recibe un número entero positivo correspondiente al número de elementos que el usuario ingresará.

Se reciben uno a uno y por renglón, los elementos de la lista (strings y de acuerdo al número recibido anteriormente).

Salidas

Si el valor correspondiente al número de elementos que tendrá la lista es 0 o negativo se deberá mandar el mensaje “Error”. Si el valor recibido es mayor a 0, se despliega la lista original (después de haber recibido los datos). Posteriormente se despliega la lista, pero sin duplicados.

Ejemplos de ejecución del programa

>>> 4

>>> Pedro

>>> Gerardo

>>> Hugo

>>> Pedro

['Pedro', 'Gerardo', 'Hugo', 'Pedro']

['Pedro', 'Gerardo', 'Hugo']

 

>>> 0

"Error"

 

 

RETO 1 : Serie de fibonacci en una lista
Diseña y codifica un programa en Python que lea la cantidad de n elementos que desea tener en la lista.

El programa debe validar que n sea mayor o igual que 0, de lo contrario lo vuelve a solicitar. Como resultado, se debe desplegar la lista con los primeros n elementos de la serie de Fibonacci.

 

Entrada

Un número entero positivo que corresponde al número de términos de la serie de Fibonacci que queremos en la lista. Si el dato recibido es menor que 0, se debe volver a solicitar.

Salidas

La lista con el número de términos de la serie de Fibonacci solicitados.

Ejemplos de ejecución del programa

>>> 5

[0, 1, 1, 2, 3]

 

>>> 9

[0, 1, 1, 2, 3, 5, 8, 13, 21]

 

>>> 0

[ ]

 

 

RETO 2: Mezcla y ordena listas
Desarrolla un programa que permitirá obtener una lista ordenada de menor a mayor a partir de dos listas. Los valores individuales de las listas de entrada los captura el usuario uno por uno y posteriormente se unirán ambas listas para obtener una sola lista ordenada de menor a mayor.

 

Entradas

Cero o más valores enteros, uno en cada renglón por cada lista. Finaliza la captura de cada lista individual con un *

Salidas

Se despliegan las dos listas iniciales y la lista final ordenada con el siguiente formato:

L1=

[3, 1, 4, 5]

L2=

[2, 9, 6, 1, 3]

LORDENADA=

[1, 1, 2, 3, 3, 4, 5, 6, 9]

Ejemplo de ejecución del programa

>>>3

>>>1

>>>4

>>>5

>>>*

>>>2

>>>9

>>>6

>>>1

>>>3

>>>*

L1=

[3, 1, 4, 5]

L2=

[2, 9, 6, 1, 3]

LORDENADA=

[1, 1, 2, 3, 3, 4, 5, 6, 9]

 

>>> *

>>> *

L1=

[]

L2=

LORDENADA=

[]

 

 

RETO 3 : Combina listas
Escribe un programa que combine dos listas de strings que recibas del usuario. El programa debe funcionar de la siguiente manera:

 

- Recibe un numero entero correspondiente a la cantidad de elementos que el usuario va a agregar en la primera lista.

- Recibe un número entero correspondiente a la cantidad de elementos que el usuario va a agregar en la segunda lista.

- Ambos números deben ser mayores a 0, en caso de no serlo, se imprime el mensaje “Error”

- En caso de que si sean mayores a 0:

----Imprime 5 guiones

----Recibe la cantidad de datos necesaria para la primera lista.

----Imprime 5 guiones

----Recibe la cantidad de datos necesaria para la segunda lista.

----Imprime 5 guiones

----Imprime la lista 1

----Imprime la lista 2

----Imprime la lista combinada

 

Es importante que consideres que siempre se empieza a combinar por la lista 1 y recuerda que las listas pueden ser de distintos tamaños

 

Entradas

Revisa la descripción del problema.

Salidas

Revisa la descripción del problema.

Ejemplos de ejecución del programa

>>> 5

>>> 3

-----

>>> Fernando

>>> Gloria

>>> Pedro

>>> Angela

>>> Laura

-----

>>> 23

>>> 45

>>> 12

-----

[‘Fernando’, ‘Gloria’, ‘Pedro’, ‘Angela’, ‘Laura’]

[‘23’, ‘45’, ‘12’]

[´Fernando’, ‘23’, ‘Gloria’, ‘45’, ‘Pedro’, ‘12’, ‘Angela’, ‘Laura’]

 

>>> 3

>>> 5

-----

>>> Fernando

>>> Gloria

>>> Pedro

-----

>>> 23

>>> 45

>>> 12

>>> 6

>>> 1

-----

[‘Fernando’, ‘Gloria’, ‘Pedro’]

[‘23’, ‘45’, ‘12’,’6’, ‘1’]

[´Fernando’, ‘23’, ‘Gloria’, ‘45’, ‘Pedro’, ‘12’, ‘6, ‘1’]

 

>>> -1

>>> 7

“Error”
