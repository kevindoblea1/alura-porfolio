# Portafolio personal – Kevin Alvarenga

Portafolio web responsivo construido con HTML, CSS y JavaScript para presentar mi perfil profesional, experiencia y proyectos como desarrollador web e ingeniero en Tecnologías de la Información.

> Proyecto basado en los desafíos de portafolio de **Alura** y desplegado como sitio estático.

---

## Vista previa

- Portafolio: **https://kevindoblea1.github.io/alura-porfolio**
- Página de resumen/CV: `resumen.html` (accesible desde el botón “Ver resumen completo” en la sección principal).

---

## Características principales

- **Diseño responsivo**  
  Adaptado a desktop, tablet y mobile usando diferentes hojas de estilo (`index.css`, `tablet.css`, `desktop.css`).

- **Interfaz en español e inglés**  
  Sistema de internacionalización simple con:
  - Archivos de idioma: `languages/es.json` y `languages/en.json`
  - Cambio de idioma mediante banderas en el encabezado
  - Textos dinámicos basados en atributos `data-section` y `data-value`

- **Secciones del sitio**

  1. **Home (`#home`)**  
     Presentación breve, rol actual, ubicación y botones para ver el CV y contactar.

  2. **Perfil / Sobre mí (`#sobreMi`)**  
     Descripción del perfil profesional enfocado en infraestructura, soporte, virtualización y desarrollo web.

  3. **Aptitudes (`#habilidades`)**  
     Tecnologías, herramientas y habilidades blandas destacadas.

  4. **Educación (`#formacion`)**  
     Formación académica y cursos relevantes (por ejemplo, CEUTEC, Cisco, Alura, EC-Council, etc.).

  5. **Experiencia (`#experiencia`)**  
     Resumen de experiencia profesional, proyectos destacados y responsabilidades técnicas.

  6. **Contacto (`#contacto`)**  
     Formulario de contacto con campos de nombre, correo, asunto y mensaje.

- **Loader de inicio**  
  Animación de carga controlada desde `loader.css` y ocultada con JavaScript una vez que la página termina de cargar.

- **Navegación mejorada**
  - Menú hamburguesa para pantallas pequeñas (abre y cierra la navegación principal).
  - Cambio de estilo del encabezado al hacer scroll.
  - Resaltado automático del enlace de navegación de la sección visible (scroll-spy).
  - Botón flotante “ir arriba” con desplazamiento suave.

- **Formulario de contacto listo para Netlify**
  - Etiqueta `netlify` en el formulario para permitir integración como formulario estático.
  - Validaciones básicas de HTML5 (`required`, tipo `email`, etc.).

- **Página de resumen (`resumen.html`)**
  - Plantilla de CV en una sola página con:
    - Datos de contacto
    - Enlaces a LinkedIn y portafolio
    - Perfil profesional
    - Experiencia, educación, certificaciones y habilidades

---

## Tecnologías utilizadas

- **HTML5 semántico**
- **CSS3**
  - Flexbox y Grid
  - Media queries por dispositivo
  - Sistema de tipografías con Google Fonts
- **JavaScript Vanilla**
  - DOM API para interactividad
  - Eventos de scroll y clic
  - `fetch` para cargar archivos de idioma
- **Recursos externos**
  - Google Fonts
  - Font Awesome (iconos)
- **Favicons y manifest**
  - Conjunto de iconos para diferentes plataformas en `assets/images/favicon`
  - `manifest.json` y `browserconfig.xml` para integración en navegadores y dispositivos

---

## Estructura del proyecto

```text
alura-porfolio/
├── index.html
├── resumen.html
├── script.js
├── assets/
│   ├── fonts/
│   ├── images/
│   │   ├── cap-portafolio.webp
│   │   ├── cap-encriptador.webp
│   │   ├── cap-cipher.webp
│   │   └── … (otros íconos e imágenes)
│   └── stylesheet/
│       ├── index.css
│       ├── tablet.css
│       ├── desktop.css
│       ├── loader.css
│       └── resumen.css
├── languages/
│   ├── es.json
│   └── en.json
├── LICENSE
└── README.md   ← (este archivo)
```

---

## Cómo ejecutar el proyecto localmente

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/kevindoblea1/alura-porfolio.git
   cd alura-porfolio
   ```

2. Abrir el archivo `index.html` en tu navegador:

   - Opción rápida: doble clic sobre `index.html`.
   - Opción recomendada: usar una extensión como **Live Server** en VS Code para recarga automática.

3. Para ver el CV:

   - Abrir `resumen.html` en el navegador, o
   - Hacer clic en el botón “Ver resumen completo” en la sección principal.

---

## Personalización

- **Textos e idioma**
  - Editar `languages/es.json` y `languages/en.json` para actualizar textos de cada sección.
- **Datos personales**
  - Actualizar la información de contacto, resumen profesional y experiencia en `index.html` y `resumen.html`.
- **Imágenes y proyectos**
  - Reemplazar las capturas de pantalla en `assets/images/` por imágenes de tus propios proyectos.
- **Colores y estilos**
  - Ajustar paleta de colores, tamaños y espaciados en los archivos CSS (`index.css`, `tablet.css`, `desktop.css`).

---

## Licencia

Este proyecto se distribuye bajo la licencia **MIT**.  
Consulta el archivo `LICENSE` para más información.

---

## Autor

Desarrollado por **Kevin Alvarenga**.  
- LinkedIn: `www.linkedin.com/in/kevindoblea`
- Portafolio: `https://kevindoblea1.github.io/alura-porfolio`
