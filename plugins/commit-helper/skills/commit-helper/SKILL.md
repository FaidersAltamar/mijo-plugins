# Commit Helper

Cuando el usuario pida hacer commit:
1. Revisa `git status` y `git diff --staged` para entender el alcance real.
2. Clasifica el cambio: feat / fix / refactor / docs / test / chore / perf.
3. Redacta el mensaje conventional commit: `<tipo>(<scope>): <resumen imperativo en español>`.
4. Cuerpo opcional con bullets de cambios relevantes y nota de breaking si aplica.
5. Nunca incluyas secretos ni datos sensibles detectados en el diff; avísalos antes.
