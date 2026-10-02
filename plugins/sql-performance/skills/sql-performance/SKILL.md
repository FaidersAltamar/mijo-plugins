# SQL Performance

Cuando el usuario reporte queries lentas:
1. Identifica las queries calientes (logs, ORM, endpoints lentos) y pide/deduce los índices existentes.
2. Busca patrones N+1 en el código de acceso a datos.
3. Propón índices compuestos con el orden de columnas justificado por selectividad.
4. Reescribe queries problemáticas: evita SELECT *, funciones sobre columnas indexadas, OR implícitos.
5. Valida cada propuesta con EXPLAIN cuando haya base accesible; si no, marca la suposición.
