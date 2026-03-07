# Contexto del Proyecto — pixan-ai

> Este archivo es para que Claude recuerde el contexto de nuestras conversaciones anteriores.
> Actualizado: 2026-03-06

---

## 👤 Sobre mí

- Nombre de usuario GitHub: **pixan-ai** (antes: aaprosperi)
- Ingeniero electrónico, 49 años
- "Vibe coder" — aprendo haciendo, con Claude como guía
- Directorio de trabajo local: `C:\pixan`
- Meta principal: **contribuir al proyecto Nanobot** y eventualmente construir con Vercel + Railway + Supabase

---

## 🗺️ Lo que ya aprendimos (sesión anterior)

### Python (IDLE)
- print(), variables, f-strings, listas, dicts
- Python es case-sensitive
- Diferencia int vs float (`voltaje=5` vs `voltaje=5.0`)
- Archivos guardados en OneDrive/Documentos

### HTML / CSS / JS
- Creamos una página con tema oscuro (#0a0a0a, acento #00ff88)
- Separamos en 3 archivos: index.html, estilos.css, app.js
- Favicon con SVG data URI
- Verificamos con DevTools (F12) que todo cargaba con status 200

### GitHub & GitHub Pages
- Repo: github.com/pixan-ai/teaching
- Deploy live: pixan-ai.github.io/teaching/
- Conceptos: commit = snapshot, Ctrl+F5 = forzar refresh de caché

### Editores explorados
- **IDLE**: editor de Python, F5 para correr
- **Emacs 29.4**: instalado, shortcuts básicos aprendidos
- **Zed**: instalado con Ayu Dark, VS Code keymap, Trust All Projects ON

### Node.js & TypeScript
- Node.js LTS instalado y verificado
- TypeScript instalado global: `npm install -g typescript`
- Carpeta `typescript-curso` creada, archivo `01_hola.ts` creado
- **Importante**: el usuario NUNCA ha escrito TypeScript de verdad — los archivos .ts que existen en C:\pixan son de Claude Code, no suyos

### Archivos Python creados (en outputs)
- 01_hola_mundo.py
- 02_variables.py
- 03_control.py
- 04_funciones.py
- 05_proyecto.py (calculadora de circuito RC)

---

## 📁 Proyectos en C:\pixan

| Carpeta | Descripción |
|---------|-------------|
| `Nanobot/` | Clonado de HKUDS/nanobot — objetivo principal |
| `pixanbot/` | Implementación de OpenClaw — descartada |
| `openclaw/` | Implementación de OpenClaw — descartada |
| `grid-notes/` | Proyecto propio |
| `ool/` | Proyecto propio |
| `pixan.ai/` | Proyecto propio |
| `.claude/` | Config de Claude Code — ya lo estaba usando |
| `CLAUDE.md` | Archivo de instrucciones para Claude Code |
| `current_page.tsx` | Archivo TypeScript (generado por Claude Code, no escrito por el usuario) |
| `voice_route.ts` | Archivo TypeScript (generado por Claude Code, no escrito por el usuario) |

---

## 🎯 El Proyecto Principal: Nanobot

- Repo original: **github.com/HKUDS/nanobot**
- ~4,000 líneas de Python puro
- Estructura: `agent/`, `bus/`, `channels/`, `cli/`, `config/`, `cron/`, `heartbeat/`, `providers/`, `session/`, `skills/`, `templates/`, `utils/`
- Inspirado en OpenClaw pero 99% más pequeño
- Tiene issues abiertos, comunidad activa, PRs de todo el mundo

### Issues abiertos relevantes (al 2026-03-06)
- **#855** — Usuario italiano documenta su instalación local completa ← modelo de lo que podemos hacer
- **#235** — Bug: bot responde "I've completed processing but have no response to give" (6 👍)
- **#336** — DeepSeek no funciona en Windows
- **#193 / #75** — Soporte para Ollama muy solicitado
- **#398** — PR abierto: múltiples proveedores de búsqueda web (DuckDuckGo, Tavily, SearXNG)

### Oportunidad identificada
> El repo no tiene documentación en español ni guía de instalación para Windows.
> Eso es exactamente lo que el usuario puede aportar como primera contribución.

---

## 🗺️ Roadmap personal (acordado)

| Mes | Enfoque |
|-----|---------|
| 1 | TypeScript + Next.js |
| 2 | PostgreSQL + Supabase + app real |
| 3 | Docker + deploy en Railway |
| 4 | Integración con Claude/OpenAI API |
| 5 | Go o Bun |

---

## 📌 Próximos pasos (al iniciar nuevo chat)

1. Instalar y correr Nanobot localmente en `C:\pixan\Nanobot`
2. Entender la estructura del código leyendo carpeta por carpeta
3. Elegir primera contribución: documentación en español para Windows
4. Fork → branch → PR

---

## 💬 Notas de estilo de aprendizaje

- El usuario aprende mejor con ejemplos concretos y analogías de electrónica
- Prefiere ir paso a paso, no todo de golpe
- Le gusta entender el "por qué" antes del "cómo"
- Tiene buen criterio para elegir proyectos — confiar en su instinto
- Hablar en español siempre
