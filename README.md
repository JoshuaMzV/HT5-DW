# HT5-DW

Proyecto de Hoja de Trabajo 5 para Desarrollo Web

## Descripción
Este proyecto implementa una página web moderna y funcional utilizando HTML y SCSS, cumpliendo con los siguientes requisitos:
- Uso de variables, mixins y anidación en SCSS
- Estilos organizados y reutilizables
- Compilación a CSS
- Estructura semántica y visual atractiva

## Estructura de Archivos

- `HT5-2.html`: Archivo principal HTML de la página.
- `style.scss`: Archivo SCSS con estilos organizados, variables, mixins y anidación.
- `style.css`: Archivo CSS compilado desde SCSS.
- `style.css.map`: Mapa de fuente para depuración de CSS.

## Componentes y Estilos

### Header
- Estructura semántica con `<header>`, `<nav>`, `<ul>`, `<li>`, `<a>`.
- Anidación en SCSS para organizar los estilos jerárquicamente.
- Menú de navegación con mixin reutilizable para enlaces.
- Variables para colores, márgenes y fuentes.

### Main
- Sección principal con `<main>`, `<h2>`, `<p>`, `<button>`.
- Botón con mixin parametrizable (`.btn`) para color y tamaño.
- Estilos modernos y responsivos.

### Footer
- Estructura con `<footer>` y `<p>`.
- Estilos básicos usando variables para color y fuente.

## SCSS: Variables y Mixins
- Variables para colores, tamaños de fuente y márgenes.
- Mixin `nav-link` para enlaces del menú.
- Mixin `button($bg, $size)` para botones reutilizables.

## Cómo compilar SCSS a CSS
1. Instala Node.js y Sass (`npm install -g sass`).
2. Ejecuta: `sass style.scss style.css`

## Autor
Joshua Mendez

---
Este proyecto cumple con todos los requisitos del enunciado y está listo para ser revisado y extendido.
