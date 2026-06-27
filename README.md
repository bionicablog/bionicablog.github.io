# Julián Eduardo Urrea Echeverry — Web de presentación profesional

Web de presentación profesional bilingüe (ES/EN) como Técnico Ortoprotésico y Técnico Garante.

Disponible en: **https://bionicablog.github.io**

## Estructura

```
bionicablog.github.io/
├── index.html    ← todo en un único archivo (HTML + CSS + JS)
└── README.md
```

Sin carpetas, sin dependencias, sin build steps. Un solo archivo que se sube y funciona.

## Cambio de idioma

Las banderas 🇪🇸 🇬🇧 del nav cambian entre español e inglés sin recargar la página.
La preferencia se guarda en localStorage y persiste entre visitas.

## Despliegue en GitHub Pages

1. Subir `index.html` al repositorio `bionicablog.github.io`
2. Settings → Pages → Deploy from branch → main → / (root)
3. La web estará disponible en `https://bionicablog.github.io`

## Personalización

- **Textos:** cada elemento tiene su versión ES y EN con `data-lang="es"` / `data-lang="en"`
- **Colores:** variables CSS en `:root` al inicio del `<style>`
- **Foto de perfil:** añadir `<img>` en la sección `#sobre-mi` cuando esté disponible
- **Proyectos:** editar las tarjetas `.project-card` en la sección `#proyectos`
- **Títulos rotativos:** arrays `ROLES_ES` y `ROLES_EN` al inicio del `<script>`
- **Nuevos puestos:** copiar un bloque `.timeline__item` en la sección `#experiencia`

## Notas técnicas

- Sistema de idiomas basado en atributos `data-lang` — no usa clases CSS para evitar conflictos con el layout
- Caché de Chrome puede requerir Ctrl+Shift+R o vaciar caché para ver cambios tras actualizar

## Proyectos relacionados

- **Blog LQNTE:** https://github.com/bionicablog/bionica → https://bionicablog.github.io/bionica
