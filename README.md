# AchromatopsiaMx — Sitio Web Oficial

Sitio web oficial de la banda **AchromatopsiaMx** (*"Total Color Blindness"*), agrupación musical independiente de la Ciudad de México caracterizada por sus atmósferas envolventes, potentes riffs y una estética visual monocromática.

---

## 📋 Tabla de Contenidos
- [Descripción General](#-descripción-general)
- [Características](#-características)
- [Estructura del Proyecto](#-estructura-del-proyecto)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Integrantes de la Banda](#-integrantes-de-la-banda)
- [Historial de Cambios (Changelog)](#-historial-de-cambios-changelog)
- [Contacto y Enlaces](#-contacto-y-enlaces)

---

## 🎸 Descripción General

Este proyecto consiste en una Single Page Application (SPA) estática optimizada para presentar la identidad artística de AchromatopsiaMx. Ofrece una experiencia inmersiva para los oyentes, permitiendo escuchar su música, consultar información de los integrantes, solicitar fechas de presentación (booking) y ponerse en contacto directo con la banda.

---

## ✨ Características

- **Diseño Visual Temático:** Estética oscura y monocromática alineada al concepto de la banda.
- **Navegación Fluida:** Navbar flotante con efecto *glassmorphism* (desenfoque de fondo), cambio visual al hacer scroll y enlaces con desplazamiento suave (*smooth scrolling*).
- **Hero Interactivo:** Carrusel/Slideshow de fondo con transición automática de imágenes.
- **Responsive Design:** Adaptabilidad total a pantallas de escritorio, tablets y dispositivos móviles con menú tipo hamburguesa.
- **Hub Multimedia y Streaming:** Accesos directos a plataformas como Spotify, YouTube, Bandcamp, Audius, Instagram y TikTok.
- **Módulo de Tour & Booking:** Sección informativa de próximas presentaciones y formulario/canales directos para promotores y eventos.
- **Formulario de Contacto:** Envío de mensajes y consultas de prensa con validación interactiva.

---

## 📁 Estructura del Proyecto

```text
AchromatopsiaMx/
├── css/
│   └── style.css        # Estilos visuales, variables CSS, reset y diseño responsive
├── img/
│   ├── 1.jpg            # Imágenes promocionales / galería
│   ├── 2.jpg            # Foto de fondo para Hero
│   ├── 3.jpg            # Foto de fondo para Hero
│   ├── Aldo.jpg         # Fotografía de Aldo Sánchez
│   ├── Dave.jpg         # Fotografía de Dave Moreno
│   ├── Marko.jpg        # Fotografía de Andrés Arrieta
│   └── logo.png         # Logotipo oficial de AchromatopsiaMx
├── js/
│   └── main.js          # Lógica interactiva (menú móvil, slideshow, scroll effect)
├── .gitignore           # Archivos ignorados por Git
├── index.html           # Documento HTML principal
└── README.md            # Documentación e historial de cambios
```

---

## 🛠️ Tecnologías Utilizadas

- **HTML5:** Marcado semántico y estructurado.
- **CSS3:** Variables personalizadas, CSS Grid, Flexbox, animaciones de transición y media queries para diseño responsivo.
- **JavaScript (ES6+):** Manipulación del DOM, eventos de scroll, carrusel automatizado y control del menú móvil.
- **Google Fonts:** Tipografías *Inter* (texto principal) y *Oswald* (títulos y encabezados).
- **FontAwesome 6:** Iconografía vectorial para redes sociales y elementos de interfaz.

---

## 👥 Integrantes de la Banda

| Integrante | Rol |
| :--- | :--- |
| **Dave Moreno** | Lead Guitar & Vocals |
| **Aldo Sánchez** | Bass & Vocals |
| **Andrés Arrieta** | Drums |

---

## 📜 Historial de Cambios (Changelog)

### [`4de1a63`] — 2026-08-20
**Actualizando la página**
- **Refactorización y Modularización:**
  - Separación limpia de la arquitectura del proyecto en archivos dedicados: `css/style.css` y `js/main.js`.
- **Mejoras Visuales y UX:**
  - Implementación de barra de navegación fija (*sticky glassmorphism*) con efecto dinámico al hacer scroll.
  - Implementación de menú hamburguesa responsivo para dispositivos móviles.
  - Creación de carrusel/slideshow con temporizador de transición automática para el fondo de la sección principal (*Hero*).
  - Modernización de la sección de integrantes con tarjetas estilizadas y efectos de *hover*.
  - Rediseño de la sección de enlaces de streaming con botones interactivos y badges.
  - Incorporación del módulo renovado para **Tour & Booking**, facilitando la contratación para festivales, foros y eventos culturales.
  - Optimización del formulario de contacto y footer con enlaces a redes sociales oficiales.

### [`7adbeee`] — 2026-03-18
**Empezando arreglos**
- Ajustes menores en la estructura de `index.html`.
- Adición y configuración del archivo `.gitignore` para ignorar archivos temporales del sistema (`.DS_Store`).

### [`b2f71ea`] — 2026-03-18
**Rediseñando toda la página**
- Incorporación de recursos gráficos en el directorio `img/`:
  - Fotos de los integrantes (`Dave.jpg`, `Aldo.jpg`, `Marko.jpg`).
  - Fotografías de sesión/fondo (`1.jpg`, `2.jpg`, `3.jpg`).
  - Logotipo oficial de la banda (`logo.png`).
- Reestructuración integral del contenido de `index.html` con nuevo enfoque visual y secciones ampliadas.

### [`883fd9a`] — 2025-06-19
**Create index.html**
- Creación inicial del repositorio y primer prototipo del archivo `index.html` para la presencia digital de la banda.

---

## 📬 Contacto y Enlaces

- ✉️ **Booking & Prensa:** [achromatopsiamx.contacto@gmail.com](mailto:achromatopsiamx.contacto@gmail.com)
- 📍 **Ubicación:** Ciudad de México, México
- 🌐 **Redes y Música:**
  - [Spotify](https://open.spotify.com/artist/0phu1BKW8Bv8YY0f3oQwXV?si=0RYj53iITUmJS---W6rtfA)
  - [YouTube](https://www.youtube.com/channel/UCBLkW1-BFmlFBYn2jyZS7OQ)
  - [Bandcamp](https://achromatopsiamx.bandcamp.com/)
  - [Audius](https://audius.co/achromatopsia.mx)
  - [Instagram](https://instagram.com/achromatopsia.mx)
  - [Facebook](https://www.facebook.com/Achromatopsia.Mx)
  - [TikTok](https://www.tiktok.com/@achromatopsiamx)
  - [Twitter / X](https://twitter.com/AchromatopsiaMx)

---
*© 2026 AchromatopsiaMx. Todos los derechos reservados.*
