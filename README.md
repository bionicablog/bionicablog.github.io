# Portfolio — Julián Eduardo Urrea Echeverry

Web de presentación profesional como Técnico Ortoprotésico y Técnico Garante.

## Estructura

```
portfolio/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## Despliegue en GitHub Pages

1. Crear un nuevo repositorio en GitHub (ej. `julian-portfolio`)
2. Subir todos los archivos tal como están
3. Ir a **Settings → Pages**
4. En *Source*, seleccionar **Deploy from a branch**
5. Rama: `main` / Carpeta: `/ (root)`
6. Guardar — la web estará disponible en `https://tu-usuario.github.io/julian-portfolio/`

## Personalización rápida

- **Datos de contacto:** editar directamente en `index.html` (sección `#contacto`)
- **Colores:** variables CSS en `:root` dentro de `css/style.css`
- **Foto de perfil:** añadir `<img>` en la sección `#sobre-mi` si se desea
- **Proyectos:** editar las tarjetas en la sección `#proyectos`

## Sin dependencias externas de build

Solo HTML, CSS y JS vainilla + Google Fonts (CDN). No requiere Node, npm ni ningún build step.
