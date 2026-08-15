# landing-personal

## Tecnologías
- HTML5
- CSS3 (Variables CSS, Google Fonts, Flexbox)
- JavaScript

## Pasos y utilización de IA

### Paso 1
- **Prompt:**
  > "Actuá como un desarrollador web Senior especialista en accesibilidad. Necesito la estructura HTML5 semántica para una landing page de portafolio personal. Debe cumplir con las etiquetas header, nav, main, section y footer, incluir roles/atributos ARIA para cumplir con WCAG, tener 4 comentarios explicativos y secciones de Portada, Sobre mí, Habilidades, Proyectos, Sección personal a elección y Formulario de contacto con labels."

### Paso 2
- **Prompt:**
  > "Generá los estilos CSS base utilizando Custom Properties (variables CSS) para paleta de colores oscura, tipografía Google Fonts (Inter y Fira Code), reseteo moderno de estilos y diseño de componentes base (botones con transiciones y títulos decorados)."
- **Revisión y adaptación personal:** 
  Ajusté los valores de colores neón en las variables CSS para mantener un contraste legible y adaptado al tema oscuro.

### Paso 3
- **Prompt:**
  > "Diseñá la maquetación CSS combinando Flexbox para la estructura unidimensional (Header, Nav, Portada, Footer y Formulario) y CSS Grid con repeat(auto-fit, minmax(...)) para las secciones multidimensionales de tarjetas (Habilidades y Proyectos). Asegurá que sea adaptable y fluido."
- **Justificación técnica (Flexbox vs CSS Grid):**
  - **Flexbox:** Seleccionado para la barra de navegación, la sección portada y el pie de página. Es ideal para alineación en un solo eje (horizontal o vertical) y distribución dinámica de elementos (como botones o enlaces).
  - **CSS Grid:** Utilizado en las secciones de Habilidades y Proyectos. Permite estructurar tarjetas en dos dimensiones (filas y columnas) de manera fluida usando `auto-fit` y `minmax()`, haciendo que el diseño sea responsive sin necesidad de recargar de media queries.
  
### Paso 4
- **Prompt:**
  > "Agregá animaciones personalizadas en CSS utilizando @keyframes para crear un efecto de flotación suave en la imagen de perfil (avatar), junto con transiciones interactivas al hacer hover sobre las tarjetas de proyectos, habilidades y enlaces del menú."
- **Revisión y adaptación personal:** 
  Ajusté la duración del @keyframes a 4 segundos e intensifiqué levemente el brillo (box-shadow) en la animación para lograr un acabado estilo dark/tech sin sobrecargar la vista.  


### Paso 5
- **Prompt:**
  > "Generá las Media Queries para optimizar la vista responsive en pantallas móviles (hasta 768px) ajustando la navegación y el alineamiento de la portada. Incluí la regla @media (prefers-reduced-motion: reduce) para garantizar accesibilidad en usuarios que prefieren no ver animaciones."
- **Revisión y adaptación personal:** 
  Probé la disposición del header en dispositivos móviles y ajusté el espaciado interno (padding) de las secciones para evitar el scroll horizontal.


## Enlaces
- Repositorio: https://github.com/flaviorin/landing-personal
- Sitio publicado: https://tu-proyecto.vercel.app