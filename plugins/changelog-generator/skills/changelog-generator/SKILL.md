# Changelog Generator

Cuando el usuario pida changelog:
1. Lista commits entre el último tag (o rango dado) y HEAD con `git log --oneline`.
2. Agrupa por tipo: Added / Changed / Fixed / Deprecated / Removed / Security.
3. Resume cada entrada en una línea orientada al usuario, no al commit técnico.
4. Formato Keep a Changelog con versión semántica sugerida según los cambios.
5. Marca entrada de Breaking Changes si hay alguna.
