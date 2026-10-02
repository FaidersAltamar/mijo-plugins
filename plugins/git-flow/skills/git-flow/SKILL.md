# Git Flow

Cuando el usuario trabaje con ramas o PRs:
1. Detecta la rama actual, el upstream y el estado del working tree antes de operar.
2. Recomienda el flujo mínimo: rama feature corta, commits atómicos, rebase sobre main antes del merge.
3. Antes de rebase/merge: verifica que no haya cambios sin commitear y propón stash si los hay.
4. Nunca fuerces push a ramas compartidas sin confirmación explícita del usuario.
5. Cierra con un resumen de operaciones y el estado final esperado del repo.
