# API Design

## Instrucciones

Para endpoints o contratos nuevos:
1. Recursos con nombres de sustantivos en plural; verbos solo para acciones.
2. Errores con `code` estable + `message` + `details` opcional.
3. Paginación cursor-based para colecciones grandes.
4. Cambios incompatibles van a nueva versión del endpoint, nunca in-place.
5. Documenta la operación con ejemplos de request/response autosuficientes.
