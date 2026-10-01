# Mijo Plugins

Marketplace oficial de plugins para Mijo Code (skills, comandos y agentes).

## Uso

En la app: Settings → Plugins → el marketplace `mijocode-plugins-official` ya apunta a este repo.

Este repo es también la fuente directa: `https://github.com/FaidersAltamar/mijo-plugins` (fuente git) o `marketplace.json` en la raíz (fuente url).

## Estructura

- `.claude-plugin/marketplace.json` — manifest del marketplace (formato Claude Code).
- `plugins/<name>/.claude-plugin/plugin.json` — manifiesto del plugin.
- `plugins/<name>/skills/<skill>/SKILL.md` — skills del plugin.
- `plugins/<name>/commands/<cmd>.md` — comandos slash del plugin.
