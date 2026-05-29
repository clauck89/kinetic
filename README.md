# KINETIC Athletics

Landing y prototipo de e-commerce para **KINETIC Athletics**, marca de calzado y ropa deportiva premium. El proyecto presenta un recorrido completo por las pantallas clave de una tienda en línea: catálogo, detalle de producto, carrito, búsqueda y autenticación.

[![Repositorio](https://img.shields.io/badge/GitHub-clauck89%2Fkinetic-0035c5?style=flat-square&logo=github)](https://github.com/clauck89/kinetic)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)

---

## Descripción

Sitio estático multipágina orientado a **demostración de UI/UX** y presentación de flujos de compra. No requiere servidor ni base de datos: cada vista es un archivo HTML independiente, enlazado desde un índice central de navegación.

Ideal para portafolio, maquetación de producto o base visual antes de integrar un backend.

---

## Características

- **Hub de navegación** (`index.html`) con acceso rápido a todas las secciones
- **Landing principal** con hero, categorías y destacados (Men)
- **Catálogo** con grid de productos (Women, 20 artículos)
- **Búsqueda avanzada** con filtros y colecciones
- **Ficha de producto** (Volt Runner X1) con galería y opciones
- **Carrito de compras** con resumen de pedido
- **Autenticación**: inicio de sesión y registro de cuenta
- **Diseño responsive** con Tailwind CSS y tipografía Montserrat / Inter
- **Sistema de color** coherente (azul primario `#0035c5`, acento lima `#c1f100`)

---

## Stack tecnológico

| Tecnología | Uso |
|------------|-----|
| HTML5 | Estructura semántica de cada vista |
| [Tailwind CSS](https://cdn.tailwindcss.com) (CDN) | Estilos utilitarios y layout responsive |
| [Google Fonts](https://fonts.google.com/) | Montserrat (titulares), Inter (cuerpo) |
| [Material Symbols](https://fonts.google.com/icons) | Iconografía en componentes |

> **Nota:** Tailwind se carga vía CDN. No hay proceso de build ni dependencias de Node.js.

---

## Estructura del proyecto

```
Proyecto-landing/
├── index.html                          # Índice / mapa del sitio
├── cat_logo-tenis.html                 # Landing principal (Men)
├── cat_logo_completo_20_art_culos.html # Catálogo Women (20 productos)
├── Busqueda-avanzada.html              # Búsqueda y filtros
├── Detalle-producto.html               # Detalle Volt Runner X1
├── carrito_de_compras.html             # Carrito y checkout visual
├── Login.html                          # Iniciar sesión
├── Crear-cuenta.html                   # Registro de usuario
└── README.md
```

---

## Cómo ejecutar el proyecto

### Opción 1: Abrir directamente

1. Clona el repositorio o descarga el ZIP.
2. Abre `index.html` en tu navegador (doble clic o arrastrar al navegador).
3. Usa las tarjetas del índice para navegar entre secciones.

### Opción 2: Servidor local (recomendado)

Evita restricciones del navegador con archivos locales usando un servidor estático:

**Con Python 3:**

```bash
cd Proyecto-landing
python -m http.server 8080
```

Abre [http://localhost:8080](http://localhost:8080) y entra a `index.html`.

**Con la extensión Live Server (VS Code / Cursor):**

Clic derecho en `index.html` → **Open with Live Server**.

---

## Mapa de pantallas

| Archivo | Sección | Descripción |
|---------|---------|-------------|
| `index.html` | Navegación | Punto de entrada y enlaces a todas las vistas |
| `cat_logo-tenis.html` | Inicio / Men | Landing principal de la marca |
| `cat_logo_completo_20_art_culos.html` | Catálogo | Listado de 20 artículos (Women) |
| `Busqueda-avanzada.html` | Colecciones | Búsqueda avanzada con filtros |
| `Detalle-producto.html` | Producto | Detalle del Volt Runner X1 |
| `carrito_de_compras.html` | Compra | Carrito y resumen |
| `Login.html` | Cuenta | Inicio de sesión |
| `Crear-cuenta.html` | Cuenta | Registro de nuevo usuario |

---

## Identidad visual

| Token | Color | Uso |
|-------|-------|-----|
| Primary | `#0035c5` | Marca, títulos, CTAs principales |
| Secondary | `#506600` | Etiquetas y acentos secundarios |
| Accent | `#c1f100` | Hover, contenedores destacados |
| Background | `#fbf8fc` | Fondo general |
| Surface | `#1b1b1e` | Texto principal |

---

## Roadmap sugerido

- [ ] Unificar idioma (`lang`) en todas las páginas
- [ ] Extraer componentes repetidos (header, footer, nav)
- [ ] Conectar formularios a API o servicio de autenticación
- [ ] Publicar en GitHub Pages
- [ ] Optimizar imágenes y assets locales

---

## Licencia

Proyecto de demostración. Consulta al autor antes de uso comercial o redistribución.

---

## Autor

**Christian Lauck** — [clauck89/kinetic](https://github.com/clauck89/kinetic)
