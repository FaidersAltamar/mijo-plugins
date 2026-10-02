# i18n Scanner

Cuando el usuario pida revisar i18n:
1. Escanea JSX/TSX en busca de texto literal visible para el usuario (children, placeholder, title, aria-label).
2. Excluye lo no traducible: rutas, constantes técnicas, logs, símbolos.
3. Propón una clave por string siguiendo la convención del proyecto (namespaces existentes).
4. Reporta duplicados que pueden compartir clave.
5. No reescribas código sin mostrar primero la tabla de propuestas.
