# API reto — Consumo de APIs públicas en el navegador

Sitio web estático que integra **varias APIs públicas** (personajes, álbumes, Pokémon, etc.) usando **JavaScript** y **fetch**, con páginas HTML dedicadas y estilos propios.

**Autora del repositorio:** [@Juli21v](https://github.com/Juli21v)

## Objetivos de aprendizaje

- Peticiones HTTP asíncronas desde el cliente
- Manipulación del DOM con los datos recibidos
- Organización por páginas (`index.html`, `album.html`, …)
- Separación básica: HTML, `assets/css`, `assets/js`

## Qué incluye

- **Personajes / listas** vía API pública (página principal).
- Otras vistas: **álbum**, **Rick and Morty**, **Pokémon**, etc. (ver `album.html` y scripts en `assets/js/`).
- Sin React ni bundler: ideal para mostrar **dominio de fetch + JSON + DOM**.

## Estructura del repositorio

```
web-con-apis-series-y-mas/
├── index.html
├── album.html
├── assets/
│   ├── css/style.css
│   └── js/
│       ├── peopleApi.js
│       ├── albumApi.js
│       ├── rick.js
│       └── pokemon.js
└── README.md
```

## Cómo verlo

Abre `index.html` en el navegador o sirve la carpeta con un servidor estático local (algunas APIs pueden exigir HTTPS o políticas CORS según el entorno).

## Para reclutadores

Demuestra **integración de APIs de terceros** y manejo de **JSON** en el front sin framework.
