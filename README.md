# AriProjects — Corporate Website

Sitio web corporativo de [AriProjects](https://ariprojects.com) — consultoría especializada en Project Management, Customer Experience (CX) y Employee Experience (EX).

---

## Correr localmente

No requiere instalación de dependencias. Es HTML/CSS/JS puro.

```bash
# Opción 1: abrir directamente en el browser
start index.html   # Windows
open index.html    # macOS

# Opción 2: servidor local (recomendado)
python -m http.server 8080   # Python
npx serve .                  # Node.js
# O instala "Live Server" en VS Code y click en "Go Live"
```

Luego abre: `http://localhost:8080`

---

## Estructura del proyecto

```
AriSoftwareWeb/
├── index.html          # Sitio completo (one-page)
├── logo_blue.png       # Logo corporativo
├── README.md
└── docs/
    ├── project-log.md  # Decisiones, cambios, convenciones
    └── backlog.md      # Tareas priorizadas por sprint
```

---

## Desplegar (GitHub Pages)

1. Ve a **Settings → Pages** en el repositorio
2. Source: `Deploy from a branch`
3. Branch: `main` / `/ (root)`
4. Guarda — el sitio queda en `https://afhfjh.github.io/AriSoftwareWeb/`

Para dominio personalizado (`ariprojects.com`): ver `docs/project-log.md`.

---

## Ramas de trabajo

| Rama | Propósito |
|------|-----------|
| `main` | Producción — siempre desplegable |
| `develop` | Integración |
| `feature/<nombre>` | Nuevas funcionalidades |
| `fix/<nombre>` | Correcciones de bugs |
