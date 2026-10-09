# Sitio web Informativo Insuco - Espacios de Aprendizaje

## Descripción

Este proyecto consiste en un sitio web informativo y personal diseñado para presentar los laboratorios de computación de la especialidad de Programación en el liceo, sus características, equipamiento y horarios de uso. Asimismo, incluye una sección dedicada a la autora del sitio web, sus intereses académicos, metas profesionales e información de contacto.

El sitio fue diseñado con una interfaz limpia, profesional y moderna, estructurada mediante el uso de tonos verdes (`#17352f`, `#2f5d50`), crema (`#f8f5ee`) y detalles en dorado (`#c7a96b`). Cuenta con un diseño adaptativo (*responsive design*) que permite una visualización en computadores, tablets y dispositivos móviles.

## Objetivos del proyecto

- Proveer información clara e interactiva sobre los laboratorios de computación del liceo (equipamiento, responsables, horarios y cursos).
- Dar a conocer el perfil de la autora, sus estudios actuales y su meta profesional de estudiar Medicina Veterinaria.
- Facilitar un medio de comunicación directo mediante un formulario de contacto funcional en el sitio.

## Secciones y Páginas del Sitio

El sitio se encuentra dividido en cuatro páginas principales navegables desde el menú superior:

### 1. Inicio (`index.html`)
- Presentación general de los espacios tecnológicos y de aprendizaje del liceo.
- Acceso directo a las distintas secciones del sitio.
- Reproductor de ambiente/música (*CORTIS - JoyRide*) como elemento complementario durante la navegación.

### 2. Sobre mí (`sobre-mi.html`)
- **Presentación personal:** Información sobre Valentina, estudiante de 4to medio en la especialidad de programación.
- **Metas y futuro:** Interés por estudiar Medicina Veterinaria, especialización internacional en Nueva Zelanda y trabajo con animales exóticos.
- **Intereses personales y pasatiempos:** Lectura, música (en especial CORTIS), cocina, dibujo y aprendizaje de inglés y programación.

### 3. Laboratorios (`laboratorios.html` y detalle por laboratorio)
- Muestra el listado de los laboratorios del liceo, sus características generales, responsables (Prof. Juan Acevedo y técnico Eduardo Salazar) y páginas de detalle individual:
  - `lab01.html`: Detalle y horario semanal del Laboratorio 01.
  - `lab02.html`: Detalle y horario semanal del Laboratorio 02.
  - *(lab03.html, lab04.html, lab05.html)*.

### 4. Contacto (`contacto.html`)
- Formulario de contacto interactivo con validación de campos obligatorios (`Nombre`, `Correo electrónico` y `Mensaje`).
- Sección de preguntas e información del propósito del sitio.

## Tecnologías Utilizadas

- **HTML5:** Estructuración semántica del contenido (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, etc.).
- **CSS3:** Hoja de estilos principal (`estilos.css`) con implementación de:
  - Variables CSS (`:root`) para la paleta de colores.
  - *Flexbox* y *CSS Grid* para la maquetación y distribución espacial de tarjetas y tablas.
  - *Media Queries* para garantizar el diseño adaptativo (*responsive*).
  - Animaciones CSS (`@keyframes`) para elementos interactivos como el reproductor y rotación de imágenes.

## Estructura del Proyecto

```text
sitio-personal/
│
├── index.html          # Página principal de bienvenida
├── sobre-mi.html       # Página con información personal y metas de Valentina
├── laboratorios.html   # Listado general de laboratorios de computación
├── lab01.html          # Detalle y horarios del Laboratorio 01
├── lab02.html          # Detalle y horarios del Laboratorio 02
├── lab04.html          # Detalle y horarios del Laboratorio 03
├── lab02.html          # Detalle y horarios del Laboratorio 04
├── lab05.html          # Detalle y horarios del Laboratorio 05
├── contacto.html       # Formulario de comunicación y contacto
├── estilos.css         # Hoja de estilos global del proyecto
│
├── audio/
│   └── musica.mp3      # Archivo de audio para el reproductor en Inicio
│
└── img/
    ├── valentina.jpeg  # Fotografía principal para la sección "Sobre mí"
    ├── lab01.jpg       # Imagen del Laboratorio 01
    ├── lab02.jpg       # Imagen del Laboratorio 02
    ├── lab03.jpg       # Imagen del Laboratorio 03
    ├── lab04.jpg       # Imagen del Laboratorio 04
    └── lab05.jpg       # Imagen del Laboratorio 05
