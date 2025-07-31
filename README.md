

# ACTIVIDADES CURSO PYTHON FUNDACION UNIVERSITARIA INTERNACIONAL DE LA RIOJA
# ACTIVIDAD 1

## Ejercicio 1
Completa la siguiente función para que dado un número de documento nacional de identidad (DNI), se devuelva una letra. Esta letra se obtiene calculando el resto del DNI entre 23 y a partir de ese valor asignarle una letra de la siguiente tabla:

Tabla letras de control DNI

El valor DNI será un número entero y la letra debe ser una cadena de carateres que contendrá una única letra en mayúsculas.

## Ejercicio 3
Completa la siguiente función para que dado el diámetro de una circunferencia, se calcule el área del círculo que contiene dicha circunferencia. Como valor de PI se usará 
**3,1415**

## Ejercicio 4
Completar la función para que dado dos números entéros y dos números enteros, se calcula el cociente y el resto de hacer la división entera entre n y m.

## Ejercicio 5
Completar la función para que dado el número de unidades que ha comprado un usuario de 2 productos diferentes, devolver el peso total del paquete para enviar su compra por mensajería. 
El peso de cada unidad del producto1 es de 147 unidades y el peso de cada unidad del producto2 es de 2400 unidades. La función debe devolver únicamente el peso total.

## [SOLUCIÓN ACTIVIDAD 1](https://github.com/gjrangel2/CursoPythonFUNIR/blob/main/Actividad_1.ipynb)

---------------------------------------------------------------------------------------------------------------------------------------------------------------

# ACTIVIDAD 2

## Ejercicio 1
Escribe una función llamada ejercicio1 que genere una lista con 15 valores enteros aleatorios que vayan de 1 a 100. La función debe devolver la lista con todos los valores.

## Ejercicio 2
Escribe una función llamada ejercicio2 que recibe 2 argumentos: el primero será la lista que hemos implementado en el Ejercicio 1 y el segundo un número por elque se dividirá cada uno de los elementos de la lista. El resultado será una nueva lista.

## Ejercicio 3
Asigna a una variable llamada ejercicio3 una función anónima que cree una nueva lista que contenga únicamente los valores enteros de cada uno de los elementos de la lista que ha devuelto la función implementada para el ejercicio 2.

## Ejercicio 4
Implementa una función, llamada ejercicio4, que reciba como argumentos dos números enteros y devuelva en una tupla los siguientes valores: el factorial del primer argumento y el máximo común divisor de ambos argumentos.

## Ejercicio 5
Crea una función ejercicio5 que devuelva una lista con todos los valores contenidos en una lista que se pasa por argumento pero eliminando los valores repetidos. Prueba el funcionamiento de esta función con la lista obtenida en el Ejercicio 1.

## [SOLUCIÓN ACTIVIDAD 2]([https://github.com/gjrangel2/CursoPythonFUNIR/blob/main/Actividad_1.ipynb](https://github.com/gjrangel2/CursoPythonFUNIR/blob/main/Actividad_2.ipynb))
---------------------------------------------------------------------------------------------------------------------------------------------------------------

# ACTIVIDAD 3

## Ejercicio 1
Escribe una clase llamada Numero. Esta clase debe tener una constructora que reciba un número y almacene ese número en 2 atributos: romano que almacenará el número en el formato de número romanos como una cadena de caracteres y normal que guardará el número que nos han dado en la constructora.

## Ejercicio 2
Crea dos nuevos métodos en la clase Numero. El primer método, llamado imprime(), imprime un mensaje mostrando el valor de ambos atributos; el segundo método, llamado suma_romano(), tendrá como parámetros una cadena de caracteres que representará otro número romano y que sumaremos a los atributos que ya teníamos.

NOTA: si necesita convertir el número romano a número normal para realizar las operaciones implemente un nuevo método.

## Ejercicio 3
Define una función llamada is_romano() dentro de la clase Numero que a partir de una cadena de caracteres, devuelve True si esa cadena de caracteres corresponde con un número romano y falso en caso contrario. Después, modifica el método para que lance un error en el caso de que el valor que nos pasan por parámetro no se corresponde con el patrón de un número romano.

## Ejercicio 4
Implementa una clase llamada MejorNumero. Esta clase heredará las propiedades de Numero e incluirá dos métodos nuevos, llamados resta() y multiplica(), para restar y multiplicar los atributos recibiendo por parámetro otro número romano.

## Ejercicio 5
En la clase MejorNumero, crea un nuevo método llamado iterar() que reciba una lista con 3 números romanos. A continuación, iterando sobre los elementos de la lista llamará a la función suma_romano(). Los posibles errores se tendrán que gestionar con excepciones (try...except...) para mostrar un mensaje y seguir ejecutando el siguiente número.

**NOTA:** el mensaje de error ha de seguir el siguiente formato --> print('Ha fallado el número', 5).

## [SOLUCIÓN ACTIVIDAD 3](https://github.com/gjrangel2/CursoPythonFUNIR/blob/main/Actividad_3.ipynb)
---------------------------------------------------------------------------------------------------------------------------------------------------------------
# ACTIVIDAD 4

## Ejercicio 1
Crea una función llamada ejercicio1, que recibe la ruta donde se encuentra un dataset y devuelve una DataFrame con los datos que hay en el dataset. Para comprobar esta función utiliza el dataset titanic.csv que se incluye en esta actividad.

## Ejercicio 2
Crea otra función llamada ejercicio2. Esta función recibe un único argumento que es un dataframe. En concreto debe recibir el dataframe que se ha obtenido de leer el dataset titanic.csv. Esta función devolverá otro dataset que incluya únicamente a los pasajeros menores de 35 años y que viajaban en 3ª clase.

## Ejercicio 3
Crea una función llamada ejercicio3, que recibiendo como argumento el dataframe del dataset titanic.csv, calcule el porcentaje de persona que sobrevieron. Redondee el resultado al segundo decimal.

## Ejercicio 4
Implementa una función llamada ejercicio4 que recibiendo el dataframe con los datos del Titanic, devuelva en una tupla el porcentaje de hombres y mujeres que viajaban en el Titanic, redondeados al segundo decimal.

## Ejercicio 5
Implementa una función llamada ejercicio5 que recibiendo el dataframe con los datos del Titanic, devuelva en una lista el número de pasajeros que viajaban en 1ª, 2ª y 3ª clase.

## [SOLUCIÓN ACTIVIDAD 4](https://github.com/gjrangel2/CursoPythonFUNIR/blob/main/Actividad_4.ipynb)


---------------------------------------------------------------------------------------------------------

Desarrollado por:  **Geyson Rangel**
[LinkedIn](https://www.linkedin.com/in/geyson-jair-rangel-ortega-79a022233/) 
