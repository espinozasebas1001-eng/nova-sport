# NOVA SPORT

NOVA SPORT es un sitio web de e-commerce de ropa deportiva, desarrollado como proyecto final de desarrollo web.

##  Sobre el proyecto

El sitio presenta una tienda online de indumentaria y accesorios deportivos, con una interfaz moderna, responsive y orientada a una experiencia de navegación simple.

El proyecto incluye:

- Página de inicio.
- Catálogo de productos.
- Sección de favoritos.
- Carrito de compras.
- Checkout simulado.
- Navegación responsive.
- Diseño adaptable a distintos dispositivos.
- Animaciones y efectos visuales.

## Tecnologías utilizadas

- HTML5
- CSS3
- SCSS
- Bootstrap 5
- AOS (Animate On Scroll)
- Google Fonts
- Git
- GitHub

## Estructura del proyecto

```text
nova-sport/
│
├── index.html
│
├── pages/
│   ├── productos.html
│   ├── favoritos.html
│   ├── carrito.html
│   └── checkout.html
│
├── scss/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── utilities/
│   └── main.scss
│
├── styles/
│   ├── style.css
│   └── style.css.map
│
├── assets/
│   └── images/
│
├── package.json
├── package-lock.json
└── README.md

## SCSS

Los estilos fueron organizados mediante una arquitectura modular utilizando partials.

Se aplicaron:

- Variables.
- Nesting.
- Mixins con parámetros.
- `@extend`.
- Media queries.
- Animaciones con `transition` y/o `keyframes`.
- CSS compilado desde SCSS.

El archivo `main.scss` se utiliza exclusivamente para importar los distintos partials mediante `@use`.

## Responsive Design

El sitio fue desarrollado para adaptarse a:

-  Mobile.
-  Tablet.
-  Desktop.

Se utilizaron media queries y layouts flexibles para evitar scroll horizontal y mantener una correcta distribución de los elementos.

## Animaciones

El proyecto incorpora:

- Animaciones nativas mediante SCSS.
- Animaciones mediante la librería externa AOS.

## Navegación

El sitio cuenta con una navbar responsive desarrollada con Bootstrap 5, incluyendo menú hamburguesa para dispositivos móviles.

## 🚀 Deploy

El proyecto se encuentra desplegado en Vercel:

https://nova-sport-ej5ctefdm-sebastian-espinoza.vercel.app

## Repositorio

**GitHub:**  
https://github.com/espinozasebas1001-eng/nova-sport

## Autor

NOVA SPORT — Proyecto final de desarrollo web.