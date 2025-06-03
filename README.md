# TLP
Universo Borderline - Sección de Cursos
Este repositorio contiene el código para la sección de Cursos del sitio web "Universo Borderline". Esta página está diseñada para presentar los programas de formación disponibles, enfocados en Terapia Dialéctico Conductual (DBT) y Terapia Cognitivo Conductual (TCC), con el objetivo de promover el autoconocimiento y el empoderamiento.

Descripción General
La página de Cursos sirve como un portal donde los usuarios pueden descubrir y explorar los diferentes programas educativos ofrecidos. Cada curso se presenta con una descripción detallada, los temas clave que cubre y un enlace para obtener más información o inscribirse. El diseño busca ser visualmente atractivo y coherente con la estética "cósmica" y moderna del sitio principal.

Características Principales
Presentación Clara de Cursos: Cada curso (DBT y TCC) se muestra en una tarjeta distintiva con:

Un ícono representativo.

Título del curso.

Descripción concisa de los objetivos y el contenido.

Lista de puntos clave o módulos que se aprenderán.

Botón para explorar el curso en detalle (enlazando a dbt.html y cbt.html respectivamente).

Diseño Responsivo: La página se adapta a diferentes tamaños de pantalla, asegurando una buena experiencia de usuario en dispositivos móviles, tabletas y computadoras de escritorio.

Animaciones Sutiles:

Efecto de aparición gradual para las tarjetas de los cursos al hacer scroll.

Efectos de hover en las tarjetas y botones para mejorar la interactividad.

Fondo animado con estrellas y gradientes para mantener la temática del sitio.

Navegación Consistente: Incluye el mismo encabezado y pie de página que otras secciones del sitio para una experiencia de usuario unificada.

Encabezado: Logo, nombre del sitio ("Universo Borderline") y enlaces a Inicio, Cursos (activo), Blog, Foros y Memes.

Pie de Página: Información del sitio, navegación, enlaces útiles (enfocados en psicoeducación sobre DBT, TCC, Mindfulness e información sobre TLP del NIMH), e información de contacto (email y enlace a la comunidad de Discord https://discord.gg/92cYjcwZ).

Sin Menciones a Premium o Soporte 24/7: El contenido se alinea con las directrices de no incluir referencias a servicios premium o soporte técnico continuo.

No se Ofrece Búsqueda de Terapeutas: La sección de enlaces útiles se centra en recursos informativos y no incluye opciones para encontrar terapeutas directamente.

Iconos Sociales Omitidos (Footer): La primera columna del pie de página no incluye iconos de redes sociales, manteniendo solo el enlace de texto a Discord en la sección de contacto.

Tecnologías Utilizadas
HTML5: Para la estructura semántica del contenido.

CSS3: Para el diseño, la tematización visual, animaciones y la responsividad.

Uso de variables CSS (custom properties) para una fácil gestión de la paleta de colores y temas.

Flexbox y Grid para el layout.

Keyframes para animaciones.

JavaScript (Vanilla):

Para la generación dinámica de estrellas en el fondo.

Para la detección de scroll y aplicación de clases (ej. header que cambia al hacer scroll).

Para el efecto de aparición de elementos con Intersection Observer.

Para actualizar dinámicamente el año en el copyright del pie de página.

Para la lógica de resaltado del enlace activo en la navegación.

Font Awesome: Para los iconos utilizados en la interfaz.

Google Fonts: Para las tipografías personalizadas (Comfortaa, Fredoka One, Krona One, Monoton, Playfair Display, Raleway).

Estructura del Archivo (cursos.html)
<head>:

Metadatos (charset, viewport, description, title).

Enlaces a hojas de estilo (Font Awesome, Google Fonts).

Estilos CSS embebidos dentro de la etiqueta <style>.

<body>:

Efectos de fondo (stars, galaxy).

<header>: Contiene el logo y la navegación principal.

<main class="main-page-content">:

<section class="page-header">: Título principal de la página de cursos y párrafo introductorio.

<section class="courses-grid">: Contenedor para las tarjetas de los cursos.

Cada curso es un <article class="course-card"> con su respectivo contenido (ícono, título, descripción, lista de aprendizajes y botón).

<footer>: Pie de página con información relevante, enlaces de navegación, enlaces útiles y contacto.

<script>: Código JavaScript para funcionalidades dinámicas.

Cómo Utilizar
Clonar el repositorio (si estuviera en uno).

Abrir el archivo cursos.html en un navegador web.

Asegurar que los archivos vinculados (como index.html, blog.html, foro.html, memes.html, dbt.html, cbt.html) existan en la misma estructura de directorios para que la navegación funcione correctamente.

Posibles Mejoras Futuras
Separar el CSS y JavaScript en archivos externos para una mejor organización y mantenibilidad.

Implementar un sistema de plantillas o componentes si el sitio crece para evitar la repetición de código (ej. header y footer).

Añadir más cursos o módulos interactivos.

Integrar un sistema de gestión de contenido (CMS) para facilitar la actualización de los cursos.
