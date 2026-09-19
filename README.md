# Milagros Álvarez — Sitio Web Personal

##  Bienvenido/a
Este proyecto corresponde a mi sitio web personal y portafolio, desarrollado como proyecto final del curso de **Desarrollo Web** en Coderhouse. Presenta información sobre mí, mis habilidades, proyectos y formas de contacto, utilizando HTML5 semántico, estilos avanzados con **SCSS (Sass)** organizados de forma modular, componentes de **Bootstrap 5** y efectos interactivos mediante transiciones y animaciones CSS.

---

##  Sitio Online / Deploy
* **Demo en Netlify:** [milagros-alvarez.netlify.app](https://milagros-alvarez.netlify.app)
* **Repositorio:** [github.com/milagrosayealvarez-beep/mili_css](https://github.com/milagrosayealvarez-beep/mili_css)

---

##  Objetivo del proyecto
Lograr un diseño visualmente ordenado, atractivo y accesible, con excelente organización del contenido y adaptación responsiva total en dispositivos móviles, tablets y desktop mediante **CSS Grid**, **Flexbox** y **Media Queries**, asegurando estándares de accesibilidad, SEO y validación W3C.

---

##  Páginas del sitio
El sitio cuenta con una estructura de 5 páginas enlazadas mediante rutas relativas optimizadas y nomenclatura estándar (*kebab-case*):
* `index.html` (Inicio / Presentación)
* `pages/sobre-mi.html` (Sobre mí y trayectoria)
* `pages/habilidades.html` (Habilidades técnicas y blandas)
* `pages/proyectos.html` (Listado y detalle de proyectos)
* `pages/contacto.html` (Formulario e información de contacto)

---

##  Tecnologías y herramientas utilizadas
* **HTML5:** Marcado semántico riguroso (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`), jerarquía clara de encabezados (`<h1>` a `<h3>`) y validación sin errores ni advertencias en el **W3C Markup Validation Service**.
* **SCSS (Sass):** Arquitectura modular (7-1 pattern simplificado), mapas y variables para paleta de colores, mixins para reutilización de código y nesting controlado.
* **CSS3:** Animaciones con `@keyframes`, transiciones suaves en estados `:hover`/`:focus` y diseño responsivo adaptativo.
* **Bootstrap 5 (vía CDN):** Integración de componentes de navegación, listas interactivas y utilidades de espaciado.
* **Git & GitHub:** Control de versiones con ramas de trabajo y flujo de commits descriptivos.
* **Netlify:** Despliegue e integración continua en producción.
* **Google Lighthouse:** Auditorías integradas de Performance, Accesibilidad, Mejores Prácticas y SEO.

---

##  Estructura del proyecto
```text
├── index.html
├── pages/
│   ├── sobre-mi.html
│   ├── habilidades.html
│   ├── proyectos.html
│   └── contacto.html
├── styles/
│   ├── styles.css             (CSS compilado)
│   └── styles.css.map         (Source map)
├── scss/
│   ├── main.scss              (Punto de entrada de compilación)
│   ├── utilities/
│   │   ├── _variables.scss    (Variables de color, fuentes y breakpoints)
│   │   └── _mixins.scss       (Mixins reutilizables y media queries)
│   ├── base/
│   │   ├── _tipografia.scss
│   │   └── _base.scss
│   ├── layout/
│   │   ├── _header.scss
│   │   ├── _nav.scss
│   │   ├── _footer.scss
│   │   └── _main.scss
│   └── components/
│       ├── _buttons.scss
│       └── _cards.scss
└── assets/                   (Imágenes y recursos multimedia optimizados)
```_
 Autora
Milagros Alvarez - Estudiante de Desarrollo Web en Coderhouse.
