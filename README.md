# Landing de Portafolio Personal — Flavio Rinaldi

Proyecto práctico individual desarrollado para la materia **Desarrollo de Sistemas Web (Front End)**. Consiste en una landing page personal orientada a presentar mi perfil, habilidades técnicas, proyectos y medios de contacto.

## 🔗 Enlaces del Proyecto
- **Sitio Publicado (Vercel):** https://landing-personal-mm8xjnv4w-flaviorin-gmailcoms-projects.vercel.app/
- **Repositorio en GitHub:** https://github.com/flaviorin/landing-personal
- **Perfil de GitHub:** https://github.com/flaviorin/

---

## 🛠️ Tecnologías y Conceptos Aplicados
- **HTML5 Semántico:** Estructura limpia basada en `<header>`, `<nav>`, `<main>`, `<section>` y `<footer>`, enriquecida con etiquetas de accesibilidad ARIA (`aria-label`, `aria-labelledby`).
- **CSS3 Moderno:**
  - **Custom Properties (Variables CSS):** Para gestión eficiente de la paleta de colores oscuros, fuentes y radios de borde.
  - **Google Fonts:** Tipografías *Inter* (cuerpo) y *Fira Code* (elementos técnicos y logo).
  - **Layout Fluido:** Combinación de **Flexbox** (navegación unidimensional, portada, formulario y footer) y **CSS Grid** (cuadrículas bidimensionales responsivas mediante `auto-fit` y `minmax()` para tarjetas).
  - **Animaciones e Interactividad:** Animación personalizada `@keyframes` para la foto de portada (*floatAvatar*) y transiciones suaves (`hover`) en tarjetas y navegación.
  - **Responsive Design & Accessibility:** Ajustes por Media Queries para celulares y soporte de `@media (prefers-reduced-motion: reduce)`.
- **JavaScript ES6 (Fetch API):** Manejo asíncrono para el envío interactivo del formulario de contacto integrado con Formspree.

---

## 🤖 Declaración de Uso de IA y Trazabilidad del Proceso

En cumplimiento con los requisitos transversales del trabajo práctico, se documenta a continuación el uso de Inteligencia Artificial como herramienta de asistencia y colaboración durante el desarrollo:

### 1. Herramientas utilizadas
- **Modelo/Herramienta:** Gemini (Google).
- **Plan:** Plan gratuito.
- **Experiencia previa:** Uso habitual de asistentes de IA como apoyo en programación, depuración de código y armado de casos de prueba/QA.

### 2. Registro de Prompts y Evolución del Proyecto

* **Paso 1: Estructura HTML y Accesibilidad**
  * *Prompt:* `"Actuá como un desarrollador web Senior especialista en accesibilidad. Necesito la estructura HTML5 semántica para una landing page de portafolio personal. Debe cumplir con las etiquetas header, nav, main, section y footer, incluir roles/atributos ARIA para cumplir con WCAG, tener 4 comentarios explicativos y secciones de Portada, Sobre mí, Habilidades, Proyectos, Sección personal a elección y Formulario de contacto con labels."`
  * *Criterio y adaptación propia:* Adapté los nombres de las clases e IDs al español para mantener consistencia en la convención del proyecto (`portada`, `avatar`, etc.) y personalicé la redacción del perfil y proyectos.

* **Paso 2: Estilos Base y Variables CSS**
  * *Prompt:* `"Generá los estilos CSS base utilizando Custom Properties (variables CSS) para paleta de colores oscura, tipografía Google Fonts (Inter y Fira Code), reseteo moderno de estilos y diseño de componentes base (botones con transiciones y títulos decorados)."`
  * *Criterio y adaptación propia:* Seleccioné los tonos de color para garantizar un contraste suficiente entre texto y fondo.

* **Paso 3: Maquetación con Flexbox y CSS Grid**
  * *Prompt:* `"Diseñá la maquetación CSS combinando Flexbox para la estructura unidimensional (Header, Nav, Portada, Footer y Formulario) y CSS Grid con repeat(auto-fit, minmax(...)) para las secciones multidimensionales de tarjetas (Habilidades y Proyectos)."`
  * *Justificación técnica:* Se usó Flexbox donde se requería alinear elementos en un solo eje dinámico (navegación, portada y enlaces del pie de página) y CSS Grid en las secciones de Habilidades y Proyectos para estructurar tarjetas en filas y columnas autoadaptables sin recargar el código de media queries.

* **Paso 4: Animaciones y Transiciones**
  * *Prompt:* `"Agregá animaciones personalizadas en CSS utilizando @keyframes para crear un efecto de flotación suave en la imagen de perfil (avatar), junto con transiciones interactivas al hacer hover sobre las tarjetas de proyectos, habilidades y enlaces del menú."`
  * *Criterio y adaptación propia:* Ajusté la frecuencia y velocidad de la animación del avatar a 4 segundos para un resultado estético tenue.

* **Paso 5: Responsive Design y Accesibilidad Final**
  * *Prompt:* `"Generá las Media Queries para optimizar la vista responsive en pantallas móviles (hasta 768px) ajustando la navegación y el alineamiento de la portada. Incluí la regla @media (prefers-reduced-motion: reduce) para garantizar accesibilidad."`
  * *Criterio y adaptación propia:* Verifiqué que en pantallas chicas no se generara desplazamiento horizontal (*scroll*) ineseado.

* **Paso 6: Detalle de Favicon**
  * *Criterio propio:* Agregué la etiqueta `<link rel="icon">` en la cabecera HTML para vincular el ícono del navegador, mejorando la presentación profesional del proyecto.

* **Paso 7: Integración de Formulario de Contacto Real (Formspree + JavaScript Fetch)**
  * *Prompt:* `"Configurá el formulario de contacto para enviar los datos de forma funcional utilizando la API de Formspree. Implementá un script de JavaScript nativo con la API Fetch para procesar la petición de forma asíncrona sin recargar la página, mostrando la confirmación mediante una alerta personalizada y deshabilitando temporalmente el botón durante el envío."`
  * *Criterio y adaptación propia:* Mantuve la respuesta visual mediante un `alert()` de JS e integré las claves de mi propia cuenta en Formspree.

---

## 📄 Licencia
Este proyecto fue creado con fines educativos para la materia Desarrollo de Sistemas Web (Front End).