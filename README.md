# PFO1 · Portfolio Personal — Gonzalo Santini

Landing page de portfolio personal desarrollada con **HTML5 y CSS3 puro**, como Práctica Formativa Obligatoria N°1 de Desarrollo de Sistemas Web - Front End. El sitio presenta mi perfil, mis habilidades técnicas y blandas, algunos proyectos en los que trabajé, una sección personal y un formulario de contacto.

## 🔗 Enlaces

- **Sitio publicado:** [https://ifts-tsds-frontend-pfo1.vercel.app/](https://ifts-tsds-frontend-pfo1.vercel.app/)
- **Repositorio:** [https://github.com/gonzalo-333/IFTS-TSDS-frontend-pfo1/](https://github.com/gonzalo-333/IFTS-TSDS-frontend-pfo1/)
- **GitHub:** [github.com/gonzalo-333](https://github.com/gonzalo-333)
- **Contacto:** mgs.argentum@gmail.com

## 📌 Secciones del sitio

- **Hero** — presentación inicial con foto y resumen de perfil.
- **Habilidades** — stack técnico (Java, Spring Boot, C++, C#, Python, HTML/CSS/JS, React, Linux, entre otros) y habilidades blandas, con iconografía de [Devicon](https://devicon.dev/).
- **Experiencia** — proyectos concretos: e-commerce, aplicaciones de escritorio y móvil, análisis de datos, automatización y desarrollo de videojuegos.
- **Sobre mí** — mi recorrido de formación (Tecnicatura en Programación en la UTN y Desarrollo de Software en IFTS).
- **Más allá del código** — intereses personales (dibujo digital, entrenamiento, tarot, tatuajes, videojuegos y otros) presentados como tarjetas interactivas con efecto flip.
- **Contacto** — formulario accesible con `label` asociado a cada campo.

## 🛠️ Tecnologías utilizadas

- **HTML5 semántico:** `header`, `nav`, `main`, `section`, `footer`, `form` con etiquetas `label`.
- **CSS3:**
  - Variables CSS (`:root`) para centralizar la paleta de colores (Nord — Polar Night) y facilitar cambios de estilo.
  - **Flexbox** para el header, el hero y el formulario de contacto.
  - **CSS Grid** (`auto-fit`/`auto-fill`) para las grillas de habilidades, proyectos y tarjetas de intereses, evitando media queries adicionales para reacomodar columnas.
  - **Diseño responsive** con `clamp()`, unidades relativas y `@media queries` en varios breakpoints (768px, 900px, 640px).
  - **Animaciones y transiciones:** cursor de terminal parpadeante junto a los "prompts" (`gonzalo@portfolio:~$`), tarjetas con efecto *flip* en CSS puro (`perspective` + `rotateY`) en la sección de intereses, filtro de escala de grises a color en hover sobre la foto de perfil, capa de *scanlines* estilo CRT retro.
- **Google Fonts:** *Roboto* para el cuerpo de texto y *Share Tech Mono* para los elementos de estética terminal.
- **Devicon:** iconos de tecnologías en la sección de habilidades.
- **Git y GitHub** para control de versiones.
- **Vercel** para el despliegue (pendiente).

## 🎨 Decisiones de diseño

Elegí una estética oscura inspirada en la paleta **Nord (Polar Night)**, combinada con un concepto de terminal/retro: los "prompts" tipo consola que encabezan cada sección (`ls skills`, `history | grep "xp"`, `cat sobre_mi.txt`, etc.), el cursor parpadeante y la capa sutil de scanlines. Busqué que cada sección se distinga claramente una de otra, con jerarquía visual clara en los títulos y buen contraste entre fondo y texto para que sea legible y agradable a la vista.

La foto de perfil está en un recuadro rectangular, en escala de grises por defecto y revela su color al pasar el mouse — una idea que tomé como referencia de dos compañeros de la cursada y adapté a mi propio diseño. Las tarjetas de "Más allá del código" usan el mismo recurso de interacción (flip 3D) para mostrar una imagen al frente y una descripción personal al dorso.

## 📁 Estructura del proyecto

```text
portfolio/
├── index.html
├── style.css
└── README.md
```

## 🤖 Declaración de uso de Inteligencia Artificial

- **Herramienta utilizada:** Gemini.
- **Plan utilizado:** Gratuito.

**Para qué la utilicé:**

- El HTML y la estructura general de la página, el contenido, la paleta de colores (Nord) y el concepto de diseño terminal/retro fueron decisiones e ideas propias, desarrolladas antes de recurrir a la IA.
- Usé la IA principalmente para **detectar y corregir errores** que ya tenía en mi CSS: Clases de CSS que no coincidían con las que usaba en el HTML. Además de perfeccionar el reset básico.
- Le pedí sugerencias puntuales de maquetación (el recuadro rectangular de la foto y el efecto de escala de grises a color fueron incorporados al diseño gracias a estas sugerencias) para pulir detalles menores del diseño que yo ya tenía definido.
- También me ayudó a estructurar y ordenar este mismo README, sugiriendo qué secciones incluir.

**Qué revisé, mantuve o adapté con criterio propio:**

- Mantuve la estructura, el contenido y la información personal que yo ya había definido; la IA no generó el sitio desde cero.
- Elegí yo mismo qué sugerencias de diseño aplicar (por ejemplo, conservé la estética de tarjetas 3D y los prompts de terminal tal como los había planteado).
- Revisé cada corrección de CSS propuesta antes de aplicarla, para entender qué solucionaba y por qué.

## 👤 Autor

**Gonzalo Santini**
GitHub: [github.com/gonzalo-333](https://github.com/gonzalo-333)
