# Actividad #2 
#### Ejercicio 1
¿Cuántos estados se pueden representar usando *N* bits?
La cantidad de datos que se pueden representar es igual a $2^N$. Si tenemos $2^1$ será igual a 2, hasta $2^{64}$ que es $1.844e^{+19}$ y es la cantidad de bits que tienen los sistemas operativos modernos. 

## Para la bitácora:
### 1. Escribe un párrafo explicando como se representan los datos en una computadora.

Los datos que se ingresan en una computadora están codificados en código binario y cada dato requiere una diferente cantidad de *bits* para ser interpretado. 

#### Letras
Estas se encuentran dadas por un código númerico único como sería el sistema ASCII.

#### Números
Normalmente representados por archivos *.int* también son codificados en código binario.

#### Imágenes
Se componen de un gran número de píxeles que se llama resolución, en esta, cada pixel es un conjunto de bits que representa las diferentes características que tienen la imagen, como el color, la tonalidad, etc. En el caso de las computadoras se usa el sistema *RGB* [$Red, Green, Blue$] en donde los valores binarios, hacen referencia a una cantidad de esos 3 colores para dar forma a la imagen.

### 2. Luego de realizar el ejercicio 1, escribe tus conclusiones acerca de la pregunta planteada en la Figura 2. ¿Cuántos estados diferentes pueden ser representados por N variables binarias?
Cada bit que tenemos puede representar 2 estados, 0 y 1, de forma que dependiendo de cuantas variables binarias tengamos, tendremos ese número elevando los 2 posibles estados: $2^N$

### 3. ¿Cuáles son las unidades de almacenamiento de datos que se utilizan en computación? Crea una tabla donde muestres estas unidades con sus prefijos. En este caso me refiero a KiloByte, MegaByte, etc.
| Unidad | Simbolo | Prefijo | Cantidad en bytes |
|--------------|--------------| ------------ |--------------|
| Byte | B | -| 1 byte |
| Kilobyte | KB | Kilo | 1,024 bytes |
| Megabyte | MB | Mega | 1,024 KB (1,048,576 bytes) |
| Gigabyte | GB | Giga | 1,024 MB (1,073,741,824 bytes) |
| Terabyte | TB | Tera | 1,024 GB (1,099,511,627,776 bytes) |
| Petabyte | PB | Peta | 1,024 TB (1,125,899,906,842,624 bytes) |

### 4. Incluye un pequeño resumen, de un par de renglones, donde menciones la importancia del trabajo de George Bool en este tópico.
El trabajo de George Boole permitió el desarrollo del álgebra binaria, permitiendo de esta forma la codificación de datos en sistema binario y las operaciones aritméticas de dicho sistema que se emplearon más adelante para el almacenamiento, procesamiento y transmisión de la información en los computadores.

### Ejercicio 2
Actividad de investigación para la bitácora: Investiga los diferentes tipos de datos que se utilizan en varios lenguajes de programación (por ejemplo, C, Java, Python). Ten en cuenta cómo cada lenguaje define los números enteros, los decimales (o flotantes), las letras del alfabeto, las cadenas de texto, valores booleanos, entre otros. Investiga qué nombres se asignan y qué abreviaciones se utilizan en cada lenguaje.

| Datos | Python | C | Java | C++ |
|--------------|--------------|-------|---|---|
| Void | | x|x|
| Char | | x||x|
| int  |  |x | x|x|
| float|  x| x|x|x|
| str | x|
| Bool|x ||x|x|
| Long|||x|x|
| complex| x|||
| Double| | x|x|x|

**Python**
 
 |Dato|Tamaño|
 |---|---|
 |int|
 |float|
 |str|
 |Bool|
 |complex|

 **C**

 |Dato|Tamaño|
 |---|---|
|void|2byte|
|char|1byte|
|int|2byte|
|float|4bytes|
|double|8bytes|

 **Java**

 |Dato|Tamaño|
 |---|---|
 |void|
 |int|
 |float|
 |Bool|
 |Long|
 |double|

 **C++**

 |Dato|Tamaño|
 |---|---|
 |char|1byte|
 |int|4bytes|
 |float|4bytes|
 |bool|1byte|
 |long|8 bytes|
 |double|8bytes|

### Ejercicio 3. Se almacena la información cada 10 segundos durante 24 horas. Calcula cuánto espacio total se requiere en memoria para almacenar estos datos. Describe el procedimiento y muestra el resultado final.
Realizamos el cálculo en clase y lo realizamos en el tablero, de forma que no lo incluyo aquí.
Pero por si acaso, describo el procedimiento, primero cambiamos las horas a minutos, esos minutos a segundos y los dividimos entre 10 para obtener la cantidad de datos generados, finalmente multiplicamos ese número por la cantidad de espacio que ocupa nuestro archivo y ya tenemos listo el peso que tendrá. Para abreviar esto, podemos empezar a dividir entre *1024* que es la manera de pasar de *bytes* a *Kilobytes* y así sucecivamente.

# Gracias por su atención.
