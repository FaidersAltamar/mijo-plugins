# Performance Audit

## Instrucciones

Evalúa el código indicado buscando:
1. Queries N+1 y carga no paginada.
2. Trabajo síncrono pesado en paths calientes.
3. Asignaciones/clones innecesarios en loops.
4. Bundle/paquete que debería ser lazy.
5. Datos que deberían cachearse y no lo están.
Para cada hallazgo: impacto estimado y cambio concreto.
