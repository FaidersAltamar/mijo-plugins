# Bundle Optimizer

Cuando el usuario pida reducir el bundle:
1. Identifica los módulos más pesados (analyzer si existe, o por tamaño de dependencias).
2. Detecta imports barrel que arrastran todo el paquete y reemplázalos por imports directos.
3. Propón dynamic import para rutas/paneles no críticos del primer render.
4. Revisa assets: imágenes sin optimizar, fuentes, mapas de source en producción.
5. Cuantifica el ahorro esperado por propuesta y ordénalas por impacto/esfuerzo.
