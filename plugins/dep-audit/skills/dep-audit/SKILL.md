# Dependency Audit

Cuando el usuario pida auditar dependencias:
1. Corre la auditoría del package manager (audit / outdated) y el detector de sin-uso del repo si existe.
2. Clasifica: críticas (vulnerabilidad explotable), actualizables con riesgo (major), triviales (patch).
3. Detecta duplicadas en el lockfile que inflan el bundle.
4. Propón un plan: qué actualizar ya, qué requiere testing, qué remover.
5. Nunca actualices automáticamente majors sin confirmación.
