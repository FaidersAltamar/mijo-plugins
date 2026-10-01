# Code Review

Modo de revisión de código para este workspace.

## Instrucciones

Cuando el usuario pida una revisión:
1. Localiza el diff o los archivos afectados.
2. Reporta hallazgos con severidad: `blocker`, `major`, `minor`, `nit`.
3. Para cada hallazgo: archivo, línea aproximada, por qué importa y sugerencia concreta.
4. Verifica que las rutas críticas tengan tests; si falta uno relevante, proponlo con su caso exacto.
5. Termina con un veredicto: ✅ ship, ⚠️ ship con notas, ❌ bloquear.
