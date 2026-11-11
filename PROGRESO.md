# Progreso de Deib

## Estado actual
- Nivel actual: 1 (Lógica y manejo de datos, C++)
- Paso actual: 1.1 (en curso, sin acreditar)
- Última sesión: 2026-11-10
- Siguiente: responder las 2 preguntas de `cin` (qué imprime el programa de edad con entrada `20`; hacia dónde va el dato con `>>`), luego ejercicio guiado (leer dos números y sumarlos, predecir salida) y ejercicio sin guía (precio x cantidad).
- Pendiente de 1.1: pregunta de comprensión final por escrito (7 / 2 en un `int`).

## Niveles acreditados
(ninguno todavía)

## Conceptos dominados
- Estructura mínima de un programa: `#include`, `main`, `return 0;`, `;`.
- Compilar y ejecutar con `g++ archivo.cpp -o archivo` y `./archivo`.
- `cout` con `<<` encadenado y `endl`.
- Tipos básicos `int`, `double`, `char`, string; diferencia entre `'7'`, `7` y `"7"`.
- División entera: trunca, no redondea (9 / 2 = 4, 1 / 2 = 0); con un operando `double` se divide con decimales.

## Conceptos que cuestan trabajo
- `<<`: lo describió como "dar paso" a `cout`; en realidad envía el dato hacia el destino.
- Responde la mitad de la pregunta; hay que releer completa antes de contestar.
- Predecir el valor exacto de una expresión: describió la operación en vez de dar el número.
- Trampa `double r = 7 / 2;`: predijo error o que no imprime nada; imprime 3 porque la división entera ocurre antes de guardar. Ya lo comprobó compilando.

## Bitácora de sesiones
| Fecha | Con quién (Claude Code / Claude web) | Qué se practicó | Resultado | Siguiente paso |
| --- | --- | --- | --- | --- |
| 2026-11-09 | Claude Code | Preparación del repo (CLAUDE.md, niveles/, proyectos/, README). Sin ejercicios. | Repo listo. | Escribir `hola.cpp`, compilarlo y empezar el paso 1.1. |
| 2026-11-10 | Claude Code | Paso 1.1: `hola.cpp`, `cout`/`endl`, tipos, división entera (`division.cpp`, `trampa.cpp`). Teoría de `cin` presentada. | Programas compilados y correctos. Corrigió sus predicciones erróneas sobre `<<` y `double r = 7 / 2`. `cin` aún sin confirmar. | Responder preguntas de `cin`, ejercicio guiado (suma de dos números) y sin guía (precio x cantidad). |
