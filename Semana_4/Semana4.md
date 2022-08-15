# Portafolio de evidencias.

## Semana 4.

Operaciones Matemáticas
Las operaciones matemáticas básicas se pueden aplicar a los tipos de datos int, double y float:

+ adición
- resta
* multiplicación
/ división
% módulo (da el resto)
Estas operaciones no son compatibles con otros tipos de datos.

int a = 20;
int b = 10;

resultado int;

resultado = a + b; // 30

resultado = a - b; // 10

resultado = a * b; // 200

resultado = a/b; // 2

resultado = a % b; // 0
Operadores de comparación
Los operadores de comparación se pueden utilizar para comparar dos valores:

> mayor que
< menos que
>= mayor o igual que
<= menor o igual que
== igual a
!= no igual a
Se admiten para tipos de datos primitivos y el resultado de una comparación es un valor booleano verdadero o falso.

int a = 5;
int b = 3;

resultado booleano = a > b;
// el resultado ahora mantiene el valor booleano verdadero
Operadores de asignación compuesta
Los operadores de asignación compuesta se pueden usar para cambiar y reasignar el valor de una variable usando una línea de código. Los operadores de asignación compuestos incluyen +=, -=, *=, /= y %=.

número entero = 5;

número += 3; // El valor ahora es 8
número -= 4; // El valor ahora es 4
número *= 6; // El valor ahora es 24
número /= 2; // El valor ahora es 12
número %= 7; // El valor ahora es 5
Operadores de incremento y decremento
El operador de incremento, (++), puede aumentar el valor de una variable basada en números en 1, mientras que el operador de disminución, (--), puede disminuir el valor de una variable en 1.

int numeroManzanas = 5;
numManzanas++; // El valor ahora es 6

int numeroNaranjas = 5;
numeroNaranjas--; // El valor ahora es 4
Orden de operaciones
El orden en que se evalúa una expresión con múltiples operadores está determinado por el orden de las operaciones: paréntesis -> multiplicación -> división -> módulo -> suma -> resta

