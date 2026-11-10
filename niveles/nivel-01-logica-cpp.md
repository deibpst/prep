# Nivel 1: Lógica y manejo de datos (C++)

## Objetivo del nivel

Que Deib pueda leer y escribir programas pequeños en C++ con variables, decisiones, ciclos, funciones y arreglos, y explicar qué hace cada línea.

## Prerrequisitos

Ninguno. Requiere un compilador (g++ o clang) y un editor.

## Pasos

Cada paso empieza con el repaso del paso anterior (una o dos preguntas) y termina con la pregunta de comprensión por escrito.

### Paso 1.1: Cómo funciona un programa y las variables

- **Repaso del paso anterior:** ninguno (primer paso).
- **Teoría:** qué es compilar, qué es `main`, qué es una variable y un tipo (`int`, `double`, `char`, `bool`, `string`), entrada y salida con `cin` y `cout`.
- **Ejercicio guiado:** se explica un programa que lee dos números y muestra su suma; Deib predice la salida antes de correrlo.
- **Ejercicio sin guía:** leer el precio y la cantidad de un producto y mostrar el total.
- **Pregunta de comprensión:** ¿qué pasa si guardas 7 dividido entre 2 en un `int`? ¿Por qué?

### Paso 1.2: Condicionales

- **Repaso del paso anterior:** 1.1 (tipos, `cin`/`cout`, división entera).
- **Teoría:** `if`, `else`, `else if`, operadores de comparación y lógicos (`&&`, `||`, `!`).
- **Ejercicio guiado:** clasificar una calificación en aprobado o reprobado.
- **Ejercicio sin guía:** dado un número, decir si es positivo, negativo o cero, y si es par o impar.
- **Pregunta de comprensión:** explica con tus palabras la diferencia entre `=` y `==`.

### Paso 1.3: Ciclos

- **Repaso del paso anterior:** 1.2 (condicionales, operadores lógicos).
- **Teoría:** `for`, `while`, cuándo usar cada uno, condición de salida, ciclos infinitos.
- **Ejercicio guiado:** sumar los números del 1 al N.
- **Ejercicio sin guía:** imprimir la tabla de multiplicar de un número y contar cuántos múltiplos de 3 hay entre 1 y 100.
- **Pregunta de comprensión:** ¿cuántas veces se ejecuta el cuerpo de `for (int i = 0; i < 5; i++)`? Traza los valores de `i` a mano.

### Paso 1.4: Funciones

- **Repaso del paso anterior:** 1.3 (`for` vs `while`, condición de salida).
- **Teoría:** definir una función, parámetros, valor de retorno, alcance de variables, paso por valor.
- **Ejercicio guiado:** una función `esPrimo`.
- **Ejercicio sin guía:** una función que calcule el factorial y otra que devuelva el máximo de tres números.
- **Pregunta de comprensión:** si una función modifica su parámetro, ¿cambia la variable original? ¿Por qué?

### Paso 1.5: Arreglos y vectores

- **Repaso del paso anterior:** 1.4 (parámetros, retorno, paso por valor).
- **Teoría:** arreglos, `std::vector`, índices desde cero, recorrer, límites y errores fuera de rango.
- **Ejercicio guiado:** encontrar el mayor elemento de un vector.
- **Ejercicio sin guía:** invertir un vector y calcular el promedio de sus elementos.
- **Pregunta de comprensión:** ¿qué pasa si accedes al índice igual al tamaño del vector? ¿Por qué es peligroso?

### Paso 1.6: Strings

- **Repaso del paso anterior:** 1.5 (índices desde cero, recorrer un vector, fuera de rango).
- **Teoría:** `std::string`, recorrer caracteres, comparar, concatenar, funciones comunes.
- **Ejercicio guiado:** contar vocales en una palabra.
- **Ejercicio sin guía:** decidir si una palabra es palíndromo.
- **Pregunta de comprensión:** explica cómo funciona tu solución del palíndromo paso a paso, con un ejemplo.

## Puerta de acreditación del nivel 1

1. **Preguntas escritas (8 a 10):** trazar a mano la ejecución de fragmentos cortos, predecir salidas, encontrar errores en código dado.
2. **Ejercicio sin IA:** un problema nuevo que combine ciclos, arreglos y funciones, por ejemplo encontrar los dos números más grandes de un vector sin ordenarlo.
3. **Explicación por escrito:** Deib explica su propia solución línea por línea y su complejidad aproximada.

## Criterio de paso

Al menos 80% en las preguntas escritas, el ejercicio funciona con casos de prueba que Deib escribe él mismo, y puede explicar cada línea sin ayuda. Si no, repasar los pasos débiles y presentar de nuevo con ejercicios distintos.

> Nota: el ejemplo de ejercicio de la puerta (dos números más grandes) es solo ilustrativo. Al aplicar la puerta, usar un problema que Deib no haya visto.
