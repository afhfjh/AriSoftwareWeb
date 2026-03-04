# AriProjects — Backlog

> Prioridad: **P1** crítico · **P2** importante · **P3** nice-to-have

---

## Sprint 1 — Fundación (MVP listo para publicar)

| # | Tarea | Prioridad | Estado |
|---|-------|-----------|--------|
| 1 | Renombrar `ariprojects.html` → `index.html` | P1 | ✅ Done |
| 2 | Actualizar `README.md` (cómo correr local, estructura, deploy) | P1 | ✅ Done |
| 3 | Implementar hamburger menu para mobile | P1 | ✅ Done |
| 4 | Conectar formulario de contacto con Formspree | P1 | ✅ Done |
| 5 | Agregar `favicon.ico` y `apple-touch-icon.png` | P2 | Pendiente |
| 6 | Metatags SEO: `description`, `keywords`, OG tags, Twitter Card | P2 | Pendiente |
| 7 | Configurar GitHub Pages (rama `main`, directorio raíz) | P1 | Pendiente |
| 8 | Crear `.gitignore` básico | P2 | ✅ Done |

---

## Sprint 2 — Mejoras UX & Conversión

| # | Tarea | Prioridad | Notas |
|---|-------|-----------|-------|
| 9 | Animaciones scroll (Intersection Observer) para secciones | P2 | Sin librería externa |
| 10 | Contador animado en strip de métricas (+80, 15+, +40) | P2 | JS puro |
| 11 | Sección "Casos de éxito / Testimonios" | P2 | Pendiente contenido del cliente |
| 12 | Modal de confirmación al enviar formulario | P2 | Depende de #4 |
| 13 | Persistent language preference (localStorage) | P3 | Recuerda idioma del usuario |
| 14 | Google Analytics / GA4 básico | P2 | Necesita cuenta GA4 |

---

## Sprint 3 — Calidad & Deploy Profesional

| # | Tarea | Prioridad | Notas |
|---|-------|-----------|-------|
| 15 | Dominio personalizado `ariprojects.com` en GitHub Pages | P1 | Requiere configuración DNS |
| 16 | HTTPS forzado (automático con GitHub Pages + dominio) | P1 | Depende de #15 |
| 17 | Lighthouse audit — target 90+ en Performance, SEO, Accessibility | P2 | |
| 18 | Optimizar `logo_blue.png` → WebP + lazy load | P2 | |
| 19 | Política de privacidad / aviso legal (GDPR básico) | P2 | Si hay formulario activo |
| 20 | LinkedIn + redes sociales links en footer | P3 | Pendiente info del cliente |

---

## Ideas Futuras (No comprometidas)

- Blog / artículos de thought leadership (requeriría Astro o CMS headless)
- Portal de cliente / área privada
- Chatbot básico de calificación de leads
- Versión PWA (offline)
