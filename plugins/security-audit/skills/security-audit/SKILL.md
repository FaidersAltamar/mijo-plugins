# Security Audit

## Instrucciones

Audita el cambio o el módulo indicado:
1. **Entrada de datos**: cualquier input no validado llegando a shell/SQL/DOM/filesystem.
2. **Secretos**: claves, tokens o contraseñas en texto claro o en logs.
3. **Auth**: endpoints o handlers sin control de autorización.
4. **Dependencias**: paquetes nuevos o sospechosos introducidos.
5. Clasifica cada hallazgo: critical / high / medium / low con la ruta de explotación concreta.
