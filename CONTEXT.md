# Contexto del Proyecto — pixan-ai

> Este archivo es para que Claude recuerde el contexto de nuestras conversaciones anteriores.
> Actualizado: 2026-03-07

---

## 👤 Sobre mí

- Nombre de usuario GitHub: **pixan-ai** (antes: aaprosperi)
- Ingeniero electrónico, 49 años
- "Vibe coder" — aprendo haciendo, con Claude como guía
- Directorio de trabajo local: `C:\pixan`
- Meta principal: **aprender TypeScript → Next.js** y eventualmente construir con Vercel + Railway + Supabase

---

## 🗺️ Lo que ya aprendimos

### Python (IDLE)
- print(), variables, f-strings, listas, dicts
- Python es case-sensitive
- Diferencia int vs float (`voltaje=5` vs `voltaje=5.0`)

### HTML / CSS / JS
- Creamos una página con tema oscuro (#0a0a0a, acento #00ff88)
- Separamos en 3 archivos: index.html, estilos.css, app.js
- Deploy live: pixan-ai.github.io/teaching/

### GitHub & GitHub Pages
- Repo: github.com/pixan-ai/teaching
- Conceptos: commit = snapshot, Ctrl+F5 = forzar refresh de caché

### Editores explorados
- **IDLE**: editor de Python, F5 para correr
- **Emacs 29.4**: instalado, shortcuts básicos aprendidos
- **Zed**: instalado con Ayu Dark, VS Code keymap, Trust All Projects ON
- **github.dev**: VS Code en el navegador, sin instalar nada, sin terminal
- **Replit**: IDE en la nube con IA, tiene terminal, puede correr código

### Setup actual de trabajo (acordado 2026-03-07)
- **Claude.ai** → aprender, generar código, subir archivos al repo
- **github.dev** → ver y editar archivos en el navegador
- **Replit** → correr código cuando se necesita
- No se necesita nada local por ahora

### TypeScript — Lecciones completadas
- **Lección 1** (`01_tipos_basicos.ts`) — `number`, `string`, `boolean`, `let`, `console.log()`
- **Lección 2** (`02_funciones.ts`) — funciones con tipos en parámetros y return, `void`
- **Lección 3** (`03_interfaces.ts`) — interfaces, propiedades opcionales con `?`
- **Lección 4** (`04_arrays_objetos.ts`) — arrays tipados, forEach, map, filter, find, arrays de objetos
- **Lección 5** (`05_clases.ts`) — clases, constructor, métodos, public/private/readonly, herencia con extends
- **Lección 6** (`06_tipos_avanzados.ts`) — union types, type alias, optional chaining `?.`, nullish coalescing `??`, generics `<T>`
- Repo: github.com/pixan-ai/typescript-curso

### Conceptos clave entendidos
- TypeScript es JavaScript con tipos — se convierte a JS antes de correr
- TS detecta errores mientras escribes, Python solo cuando corres
- `interface` = define la "forma" de un objeto (como un conector estándar en electrónica)
- `void` = función que no regresa nada
- `console.log()` = `print()` de Python
- JSX/TSX = TypeScript mezclado con HTML (lo que usa Next.js)
- `class` = molde para crear objetos (datos + comportamiento juntos)
- `extends` = herencia, una clase recibe todo lo de otra y puede agregar más
- `private` = solo accesible desde dentro de la clase
- `readonly` = se puede leer pero no modificar desde afuera
- `type X = A | B` = union type, el valor puede ser de varios tipos
- `?.` = optional chaining, accede sin error si el valor no existe
- `??` = nullish coalescing, usa un default si el valor es null/undefined
- `<T>` = generic, código reutilizable que funciona con cualquier tipo

---

## 📁 Proyectos en GitHub

| Repo | Descripción |
|------|-------------|
| `pixan-ai/teaching` | Página web + contexto de aprendizaje |
| `pixan-ai/nanobot` | Fork de HKUDS/nanobot — objetivo de contribución |
| `pixan-ai/typescript-curso` | Curso de TypeScript paso a paso |

---

## 🎯 El Proyecto Principal: Nanobot

- Repo original: **github.com/HKUDS/nanobot**
- ~4,000 líneas de Python puro
- Tiene issues abiertos, comunidad activa, PRs de todo el mundo

### Oportunidad identificada
> El repo no tiene documentación en español ni guía de instalación para Windows.
> Eso es exactamente lo que el usuario puede aportar como primera contribución.

---

## 🗺️ Roadmap personal (acordado)

| Etapa | Enfoque |
|-------|---------|
| 1 (actual) | TypeScript — tipos, funciones, interfaces, arrays, clases, tipos avanzados |
| 2 | Next.js — componentes, páginas, rutas |
| 3 | PostgreSQL + Supabase + app real |
| 4 | Docker + deploy en Railway |
| 5 | Integración con Claude/OpenAI API |

---

## 📌 Próximos pasos (al iniciar nuevo chat)

1. Continuar TypeScript desde Lección 7 (async/await y fetch de APIs)
2. Repo: github.com/pixan-ai/typescript-curso
3. Abrir en github.dev para leer/editar

---

## 💬 Notas de estilo de aprendizaje

- El usuario aprende mejor con ejemplos concretos y analogías de electrónica
- Prefiere ir paso a paso, no todo de golpe
- Le gusta entender el "por qué" antes del "cómo"
- Tiene buen criterio para elegir proyectos — confiar en su instinto
- Hablar en español siempre
- Cuando algo no queda claro, pregunta hasta entender — muy buena señal
- Resuelve problemas solo cuando puede (usó Ctrl+. para arreglar un error de interfaz)
- Ritmo ágil — avanza rápido cuando el tema está claro, sin necesidad de pausa
