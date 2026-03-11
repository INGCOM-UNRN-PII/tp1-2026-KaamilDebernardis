# Similitudes y diferencias entre C y Java

## 1. Sintaxis general y tipos de datos
En cuanto a la sintaxis general, Java presenta grandes similitudes con C. Se mantiene:
* El uso de llaves para delimitar bloques.
* El punto y coma al final de las instrucciones.
* El formato de los comentarios.
* Los mismos tipos de datos primitivos, con la excepción del tipo `boolean`, el cual Java incorpora de forma nativa.

## 2. Gestión de librerías y memoria
A diferencia de C:
* En Java no se utilizan las directivas `#include` ni `#define`; se usa la instrucción `import` para la inclusión de librerías.
* Java maneja la memoria de forma automática y no hace uso de punteros explícitos.

## 3. Entrada y salida estándar
Respecto a las operaciones por consola:
* La función de impresión `printf` de C tiene su equivalente en `System.out.println` dentro de Java.
* Por su parte, la lectura de datos que en C se realiza con `scanf`, en Java se implementa mediante métodos como `Scanner.nextInt()`.