# Requerimientos

## 1. Características Generales del Proyecto

+ 10 x 10 celdas de longitud fija.
+ Ubicación cartesiana de celdas (letra: columna, número: fila).
+ Operaciones de suma y resta entre celdas.
+ Operaciones de producto y división entre celdas.
+ Función `SUMA(celda:celda);`.
+ Función `PROMEDIO(celda:celda)`.
+ Función `CONTAR.SI(celda:celda;condición)`.
+ Soporte de fórmulas matemáticas.

## 2. Historias de usuario.

+ [ ] Como usuario, quiero ver una tabla de 11 celdas por 11 celdas de longitud fija y rectangular (de 12 píxeles de alto). La primera fila estará identificada con letras alusivas a las columnas (de la A a la J) y la primera columna estará identificada con números alusivos a las filas (del 1 al 10). La celda de la esquina superior izquierda no estará identificada.
+ [ ] Como usuario, quiero que no sea permitida la selección de letras o de números en la fila y la columna identificadora de las celdas.
+ [ ] Como usuario, quiero que cada celda no identificadora contenga un campo editable (con 100% de ancho por defecto no modificable), cuyo texto estará alineado siempre a la derecha de la celda.
+ [ ] Como usuario, quiero que en cada celda sólo se puedan ingresar los caracteres de la A a la Z en mayúsculas, los números del 0 al 9, un caracter de punto `.` y paréntesis `()` así como el símbolo `=` y los símbolos de operaciones aritméticas `+`, `-`, `*`, `/`.
+ [ ] Como usuario, quiero poder realizar operaciones aritméticas básicas (suma, resta, producto y división) entre celdas, valiéndose de reglas matemáticas formales, así como también la modificación de la precedencia de dichas operaciones usando sólo paréntesis `()`, para lograr dicho comportamiento, se debe indicar explícitamente que se trata de una operación matemática, precediendo la expresión con el signo de `=`.
+ [ ] Como usuario, quiero poder ejecutar la suma de un rango de celdas especificando la siguiente expresión: `=SUMA(celda:celda)` y que al presionar la tecla enter, dicha operación sea realizada.
+ [ ] Como usuario, quiero poder ejecutar el promedio de un rango de celdas especificando la siguiente expresión: `=PROMEDIO(celda:celda)` y que al presionar la tecla enter, dicha operación sea realizada.
+ [ ] Como usuario, quiero poder ejecutar el conteo de un patrón especificado dentro de un rango de celdas determinado, usando la siguiente expresión: `=CONTAR.SI(celda:celda;patron)` y que al presionar la tecla enter, dicha operación sea realizada.
+ [ ] Como usuario, quiero poder escribir las funciones anteriores con sus expresiones especificadas, y que cada rango de celdas sea tomado independientemente de la posición, siempre en la misma fila o en la misma columna.
+ [ ] Como usuario, quiero poder especificar las operaciones aritméticas empleando la identificación de las celdas como en una hoja de cálculo (ej. Microsoft Excel), de tal manera que la columna sea una letra y la fila sea un número, esto es aplicable a todas las operaciones posibles. Ej.: `A1`, `J10`, `C4:C9`.
