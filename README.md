# Sabina Romero Rodríguez — CV Web

Portafolio profesional / CV web construido con HTML, CSS y JavaScript puro. Incluye un sistema de temas intercambiables sin recargar la página.

## 🚀 Ver online
Una vez publicado en GitHub Pages: `https://TU_USUARIO.github.io/sabina-cv`

---

## 🎨 Temas disponibles

| Tema | Archivo | Descripción |
|------|---------|-------------|
| 🔵 Tech | `style-tech.css` | Dark tech con acentos azules, tipografía Syne + DM Mono |
| ☀️ Light | `style-light.css` | Editorial / revista, fondo crema, tipografía Playfair Display |
| 🌟 Neopets | `style-neopets.css` | Y2K / early 2000s, galaxia púrpura, marquee animado, cursor ⭐ |
| ⚔️ Solo Leveling | `style-sololeveling.css` | Sistema RPG, grid de partículas, runas, paneles holográficos |
| 🍄 Mario | `style-mario.css` | Pixel art retro, tipografía Press Start 2P, nubes y ladrillos |

El botón **"cambiar →"** en la esquina inferior derecha cicla entre todos los temas. La preferencia se guarda en `localStorage`.

---

## 📁 Archivos

```
index.html              — estructura del sitio
style-tech.css          — tema Dark Tech (predeterminado)
style-light.css         — tema Light Editorial
style-neopets.css       — tema Neopets Y2K
style-sololeveling.css  — tema Solo Leveling RPG
style-mario.css         — tema Mario Bros pixel art
script.js               — animaciones e interacciones
README.md               — este archivo
```

---

## 📄 Secciones del CV

1. **Hero** — nombre, roles, resumen y estadísticas (20+ años, 92 módulos REUF, 10+ tecnologías)
2. **Sobre mí** — descripción profesional y stack tecnológico completo
3. **Experiencia** — timeline con Banco Consorcio, AIEP/IPChile/ESUCOMEX, S&M Consulting, Achilles Chile y más
4. **Certificaciones REUF** — 92 módulos TI aprobados por SENCE (17 de marzo de 2026), organizados por área
5. **Formación** — UNAB (Ciencias de Datos, cursando), IPChile x2
6. **Contacto** — email, teléfono, LinkedIn y ubicación

---

## 🛠️ Publicar en GitHub Pages

1. Crea un repositorio en GitHub (ej: `sabina-cv`)
2. Sube **todos** los archivos del proyecto
3. Ve a **Settings → Pages**
4. En **Source** selecciona: `Deploy from a branch`
5. Branch: `main` → Folder: `/ (root)` → Guardar
6. Espera 1-2 minutos → tu sitio estará en:
   `https://TU_USUARIO.github.io/sabina-cv`

---

## ➕ Agregar un nuevo tema

1. Crea un archivo `style-NOMBRE.css` con tus estilos
2. Agrégalo al array `themes` en el `<script>` al final de `index.html`:
```js
{ id: 'NOMBRE', css: 'style-NOMBRE.css', label: '🎨 Mi Tema' }
```
3. ¡Listo! El botón lo incluirá automáticamente en el ciclo

---

## ✏️ Personalizar contenido

Edita directamente `index.html` para actualizar:
- Datos de contacto (email, teléfono, LinkedIn)
- Experiencia laboral en el timeline
- Certificaciones y fechas
- Renta pretendida

---

Santiago, Chile · Marzo, 2026