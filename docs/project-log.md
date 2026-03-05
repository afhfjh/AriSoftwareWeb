# AriProjects — Project Log

## Stack & Architecture
- **Type:** Vanilla HTML/CSS/JS (single file) — sin framework, sin build step
- **Hosting:** GitHub Pages (default) o Netlify (alternativa recomendada)
- **Fuentes:** Google Fonts — Playfair Display + DM Sans
- **i18n:** Sistema propio con `data-lang` + clases CSS (`lang-en` / `lang-es`)
- **Formulario:** A definir — Formspree o EmailJS (sin backend requerido)

**Decisión arquitectónica (2026-03-04):** Mantener vanilla HTML. Razón: el sitio ya es un one-pager corporativo completo. Migrar a Astro/Next.js agregaría complejidad sin beneficio real para este caso de uso. Astro/Next.js se reconsiderará si se necesita blog, CMS, o múltiples páginas dinámicas.

---

## Decisiones

| Fecha | Decisión | Razón |
|-------|----------|-------|
| 2026-03-04 | Mantener vanilla HTML/CSS/JS | Sitio ya funcional, sin necesidad de build tools para un one-pager |
| 2026-03-04 | Renombrar `ariprojects.html` → `index.html` | Estándar para hosting estático (GitHub Pages / Netlify) |
| 2026-03-04 | Formspree para contact form | Sin backend, plan gratuito suficiente para MVP |
| 2026-03-04 | GitHub Pages como hosting MVP | Gratis, cero config para HTML estático, CI/CD nativo con GitHub Actions |

---

## Cambios Importantes

### Sprint 1 (2026-03-04) — ✅ COMPLETADO
- Repositorio clonado en `C:\dev\AriSoftwareWeb`
- `ariprojects.html` renombrado a `index.html`
- Hamburger menu mobile implementado (breakpoint 900px, animación X, cierre por click fuera)
- Formulario de contacto conectado a Formspree (`mnjberna`) — envío async sin redirect
- Mensajes de éxito/error bilingües in-page
- Creados: `docs/project-log.md`, `docs/backlog.md`, `.gitignore`
- `README.md` actualizado con instrucciones de setup y deploy
- Favicon SVG (AP azul corporativo) + metatags SEO + OG tags
- GitHub Pages configurado → `ariprojects.com` live con HTTPS
- DNS migrado de Firebase a GitHub Pages (4 A records + CNAME www)

---

## Issues Conocidos

| ID | Descripción | Prioridad |
|----|-------------|-----------|
| #1 | Mobile nav oculto (`display:none !important`) sin hamburger menu | Alta |
| #2 | Formulario de contacto sin backend — no envía nada | Alta |
| #3 | Archivo llamado `ariprojects.html` en vez de `index.html` | Alta |
| #4 | README.md vacío | Media |
| #5 | Sin favicon | Media |
| #6 | Sin metatags OG (Open Graph) para compartir en redes sociales | Media |

---

## Convenciones

- **Ramas:** `main` (producción), `develop` (integración), `feature/<nombre>`, `fix/<nombre>`
- **Commits:** Convencional Commits — `feat:`, `fix:`, `docs:`, `chore:`, `style:`
- **Idioma commits:** Inglés
- **CSS:** Variables en `:root`, mobile-first en breakpoints
- **i18n:** Todo texto en dos idiomas con `data-lang="en"` y `data-lang="es"`

---

## Tareas Pendientes (ver backlog.md para detalle)

- [ ] Renombrar `ariprojects.html` → `index.html`
- [ ] Implementar hamburger menu mobile
- [ ] Conectar formulario con Formspree
- [ ] Agregar favicon
- [ ] Metatags OG + SEO básico
- [ ] Configurar GitHub Pages
- [ ] Actualizar README.md
