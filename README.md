# Resume (GitHub Pages)

Este repositorio ya quedó preparado para publicar **2 currículums** en GitHub Pages.

## Estructura creada

```text
.
├── README.md
└── docs
    ├── index.html
    └── resumes
        ├── cv-principal.pdf      ← súbelo tú
        └── cv-secundario.pdf     ← súbelo tú
```

## Dónde subir cada CV y con qué nombre

Sube tus archivos PDF dentro de:

- `docs/resumes/cv-principal.pdf`
- `docs/resumes/cv-secundario.pdf`

> Es importante respetar **exactamente** esos nombres para que los enlaces funcionen sin cambios.

## Qué hace cada archivo

- `docs/index.html`: página principal pública de GitHub Pages con links a ambos CV.
- `docs/resumes/`: carpeta donde viven tus PDFs.

## Activar GitHub Pages

1. Ve a tu repositorio en GitHub.
2. Entra a **Settings → Pages**.
3. En **Build and deployment**, selecciona:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/docs`
4. Guarda los cambios.

Tu sitio quedará disponible en una URL similar a:

`https://TU-USUARIO.github.io/resume/`

Y tus PDFs en:

- `https://TU-USUARIO.github.io/resume/resumes/cv-principal.pdf`
- `https://TU-USUARIO.github.io/resume/resumes/cv-secundario.pdf`

## Si quieres cambiar nombres

Si prefieres otros nombres de archivo, solo cambia los `href` correspondientes en `docs/index.html`.
