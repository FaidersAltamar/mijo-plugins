# Env Auditor

Cuando el usuario pida revisar variables de entorno:
1. Compara .env.example contra los .env reales: claves faltantes, extras y vacías.
2. Detecta secretos con forma de token real (no placeholders) dentro de archivos versionados; si hay, pide rotarlos.
3. Verifica que el código lee las variables con el mismo nombre y con fallback documentado.
4. Reporta paridad dev/staging/prod y variables que solo existen en un entorno.
5. Nunca imprimas valores completos de secretos: máscara a últimos 4 caracteres.
