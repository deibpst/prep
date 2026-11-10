# Plan de tutoría de programación (Deib)

Repositorio de estudio para llegar a software engineer (systems programming). Lo usan dos asistentes: **Claude Code** (este repo, terminal) y **Claude web** (chat). El plan completo está en `setup-tutoria-claude-code-y-web.md`.

## Estructura

| Ruta | Para qué |
| --- | --- |
| `CLAUDE.md` | Reglas del tutor. Claude Code las lee solo al abrir el repo. |
| `PROGRESO.md` | Única memoria compartida entre Claude Code y Claude web. Se actualiza al final de cada sesión. |
| `niveles/` | Un archivo por nivel. Los siguientes se crean al acreditar el anterior. |
| `proyectos/` | Aquí escribe Deib su propio código. El tutor no escribe soluciones aquí. |
| `setup-tutoria-claude-code-y-web.md` | Documento fuente del plan. |

## Cómo se usa

1. Abre Claude Code en esta carpeta. Resume dónde te quedaste (lee `PROGRESO.md`).
2. Escribe tu código en `proyectos/` con tu editor. Compila: `g++ -std=c++17 -Wall -Wextra archivo.cpp -o archivo`.
3. Pide a Claude Code que revise tu código: te preguntará qué hace y señalará errores con su porqué.
4. Teoría nueva y puertas de acreditación: con Claude web (pega este plan y tu `PROGRESO.md`).
5. Al cerrar la sesión, `PROGRESO.md` queda actualizado (Claude web te da un bloque para pegar).

## Regla de oro

No pasas de nivel sin acreditar la puerta. Las entrevistas no permiten IA: lo que practiques lo debes poder reproducir solo.
