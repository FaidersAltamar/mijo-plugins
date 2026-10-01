# Debug Console

## Instrucciones

Frente a un bug:
1. Repro reproducíble mínima primero; no se arregla lo que no se reproduce.
2. Hipótesis falsables numeradas; verifícalas de más barata a más cara.
3. Bisecta el rango de cambios si hay regresión.
4. La causa raíz se demuestra con un test rojo que pase al corregirse.
5. Termina con: causa raíz, por qué no se detectó antes, qué evita que vuelva.
