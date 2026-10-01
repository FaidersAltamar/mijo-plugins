# DB Migrate

## Instrucciones

Al crear o revisar una migración:
1. Sigue expand-and-contract cuando el cambio afecta código en uso.
2. Cada migración tiene `up` y `down` reales y probados.
3. DDL peligrosa (DROP, ALTER masivo, RENAME) va con confirmación explícita.
4. Verifica índices necesarios para las nuevas consultas.
5. Lista los pasos de rollback en el comentario.
