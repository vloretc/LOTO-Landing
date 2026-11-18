---
version: alpha
name: LoTo
description: Sistema de diseño del portafolio de Lorena Torres.
colors:
  primary: "#51000E"
  secondary: "#BDE0FF"
  surface: "#FCF9EB"
  surface-warm: "#4A2E27"
  ink: "#231815"
typography:
  greeting-min:
    fontFamily: Skynila
    fontSize: 112px
    fontWeight: 400
  greeting-max:
    fontFamily: Skynila
    fontSize: 144px
    fontWeight: 400
  greeting-compact:
    fontFamily: Skynila
    fontSize: 96px
    fontWeight: 400
  greeting-mobile:
    fontFamily: Skynila
    fontSize: 88px
    fontWeight: 400
  section-title:
    fontFamily: Skynila
    fontSize: 48px
    fontWeight: 400
  project-title:
    fontFamily: Skynila
    fontSize: 32px
    fontWeight: 400
  subtitle:
    fontFamily: Roobert TRIAL
    fontSize: 24px
    fontWeight: 600
  subtitle-mobile:
    fontFamily: Roobert TRIAL
    fontSize: 22px
    fontWeight: 600
  language-sample:
    fontFamily: Roobert TRIAL
    fontSize: 18px
    fontWeight: 600
  label:
    fontFamily: Roobert TRIAL
    fontSize: 16px
    fontWeight: 500
  navigation:
    fontFamily: Roobert TRIAL
    fontSize: 16px
    fontWeight: 500
  project-cover:
    fontFamily: Roobert TRIAL
    fontSize: 24px
    fontWeight: 500
  course-year:
    fontFamily: Roobert TRIAL
    fontSize: 16px
    fontWeight: 300
  body:
    fontFamily: Tome Sans Variable
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.65
  credit:
    fontFamily: Tome Sans Variable
    fontSize: 12px
    fontWeight: 400
rounded:
  none: 0px
  subtle: 5px
  full: 9999px
spacing:
  section-gap: 48px
  project-gap: 16px
  gallery-gap: 10px
  course-gap: 24px
  language-gap: 24px
  skills-gap-min: 32px
  folder-gap: 40px
  folder-height-desktop: 76px
  folder-height-mobile: 66px
  hero:
    portrait-ratio: 1
    copy-ratio: 1.8
    gap-min: 56px
    gap-max: 112px
    gap-compact: 32px
  dialog:
    width-max: 760px
    desktop:
      top: 56px
      side: 36px
      bottom: 32px
    mobile:
      top: 48px
      side: 20px
      bottom: 24px
  course-copy:
    top: 36px
    bottom: 40px
    title-to-provider: 14px
motion:
  project-image-zoom:
    duration: 400ms
components:
  navigation:
    backgroundColor: "{colors.surface-warm}"
    textColor: "{colors.surface}"
    typography: "{typography.navigation}"
  navigation-link-hover:
    textColor: "{colors.secondary}"
  project-link:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.surface-warm}"
  project-link-hover:
    textColor: "{colors.primary}"
  footer:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.surface}"
  footer-link-hover:
    textColor: "{colors.secondary}"
  contact-button:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.full}"
    size: 44px
  contact-button-hover:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.ink}"
  portrait:
    backgroundColor: "{colors.secondary}"
  ribbon-wine:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.secondary}"
  ribbon-blue:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.primary}"
  mosaic-image:
    rounded: "{rounded.none}"
  folder-tab-wine:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.surface}"
    height: "{spacing.folder-height-desktop}"
  folder-tab-dark:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.surface}"
    height: "{spacing.folder-height-desktop}"
  folder-tab-warm:
    backgroundColor: "{colors.surface-warm}"
    textColor: "{colors.surface}"
    height: "{spacing.folder-height-desktop}"
  folder-tab-beige:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    height: "{spacing.folder-height-desktop}"
  folder-tab-mobile:
    height: "{spacing.folder-height-mobile}"
  project-cover:
    textColor: "{colors.surface}"
    typography: "{typography.project-cover}"
    rounded: "{rounded.none}"
  project-dialog:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
  project-dialog-title:
    textColor: "{colors.primary}"
    typography: "{typography.project-title}"
  project-dialog-close:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    size: 44px
  courses-section:
    backgroundColor: "{colors.secondary}"
  course-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
  course-title:
    typography: "{typography.subtitle}"
  course-year:
    typography: "{typography.course-year}"
  video-play-button:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.primary}"
    rounded: "{rounded.full}"
    size: 48px
  program-icon:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.surface}"
    rounded: "{rounded.subtle}"
  skill-tag:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.subtle}"
  language-label:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.subtitle}"
  language-level:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
  language-bar-track:
    backgroundColor: "{colors.secondary}"
    rounded: "{rounded.none}"
  language-bar-fill:
    backgroundColor: "{colors.primary}"
    rounded: "{rounded.none}"
---

# Sistema de diseño de LoTo

## Overview

LoTo es el portafolio de Lorena Torres. La identidad es geométrica, moderna y cercana, con composiciones ordenadas, tipografía de carácter y una base clara con acentos oscuros. Los proyectos tienen prioridad visual. Las descripciones son breves y cada sección se distingue por su jerarquía y sus alineaciones.

## Colors

| Token | Color | Aplicación |
| --- | --- | --- |
| `primary` | Rojo vino · `#51000E` | Títulos, acentos, cintas, relleno de las barras, icono de reproducción y hover de enlaces de proyecto. |
| `secondary` | Azul claro · `#BDE0FF` | Fondo de apoyo y de Cursos, círculo del retrato, etiquetas, base de las barras, cintas y hover de navegación y contacto. |
| `surface` | Beige · `#FCF9EB` | Fondo principal, tarjetas de cursos y de proyecto abiertas, texto e iconos sobre fondos oscuros y círculos de contacto y reproducción. |
| `surface-warm` | Café claro · `#4A2E27` | Navegación, superficies secundarias y enlaces de proyecto en reposo sobre beige. |
| `ink` | Café oscuro · `#231815` | Texto de lectura y etiquetas, pie de página, fondo de iconos de programas e iconos de contacto y cierre. |

Usa colores sólidos y texto a plena opacidad. Las combinaciones de la tabla alcanzan AA para texto normal en ambas direcciones. Respeta el rol de cada fondo y texto según el componente.

| Par de colores | Contraste |
| --- | ---: |
| Café claro y beige | 11.62:1 |
| Café claro y azul claro | 8.92:1 |
| Café oscuro y beige | 16.40:1 |
| Café oscuro y azul claro | 12.59:1 |
| Rojo vino y azul claro | 11.26:1 |
| Rojo vino y beige | 14.67:1 |

## Typography

- **Skynila Regular, 400.** Saludo, títulos de sección, nombre del proyecto dentro de la tarjeta abierta, cintas y nombre de Lorena en el pie. Los títulos de sección miden 48 px. El saludo varía de 112 a 144 px en escritorio, baja a 96 px hasta 850 px y a 88 px hasta 650 px.
- **Roobert TRIAL.** Navegación, botones, pestañas, subtítulos, etiquetas y nombres de proyectos sobre las portadas. Usa los pesos Light 300, Medium 500 y Semibold 600. Las etiquetas usan Medium a 16 px. Los subtítulos de programas, habilidades, idiomas y cursos usan 24 px, con 22 px en el ajuste de subtítulos hasta 650 px. La muestra de barras usa 18 px para el nombre del idioma.
- **Tome Sans Variable.** Cuerpo, descripciones, niveles de idioma y créditos de colaboración. Carga la familia desde Adobe Fonts. El cuerpo usa 16 px con interlineado de 1.65 y los créditos usan 12 px. Alinea los párrafos a la izquierda y evita justificarlos.

## Layout

El recorrido vertical empieza con la presentación, sigue con programas, habilidades e idiomas, y continúa con las cintas entrecruzadas, los proyectos y los cursos. La cinta horizontal precede al contacto. Alinea títulos, textos e imágenes con los bordes de sus bloques.

Los márgenes laterales son del 4.2 % en general y del 7 % en la presentación. En escritorio, la retícula del retrato y el texto es de `1fr 1.8fr`, con un hueco flexible de 56 a 112 px. Usa 48 px como ritmo vertical de referencia, 16 px entre proyectos, 10 px entre imágenes de galería, 24 px entre cursos y bloques de idiomas y al menos 32 px entre bloques de habilidades.

Distribuye las etiquetas en tres filas. Coloca inglés y francés uno debajo del otro e italiano al lado. Iguala el ancho de las barras al del bloque de programas en la disposición de referencia.

| Ancho de pantalla | Ajuste acumulativo |
| --- | --- |
| Hasta 1300 px | Los cursos pasan de tres columnas a una. |
| Hasta 1100 px | Programas y habilidades se disponen en dos columnas. Los idiomas se agrupan debajo. |
| Hasta 850 px | El saludo baja a 96 px y se reduce el hueco entre el retrato y el texto a 32 px. |
| Hasta 700 px | La tarjeta abierta adopta 48 px arriba, 20 px a cada lado y 24 px abajo. |
| Hasta 650 px | La presentación y las habilidades se apilan. El saludo baja a 88 px, los subtítulos a 22 px y las pestañas tienen un mínimo de 66 px de alto. |
| Hasta 600 px | El contacto se apila y las galerías reorganizan sus módulos. |

Las tarjetas abiertas permiten desplazamiento interno. Mantén las proporciones de las imágenes y centra el video vertical. Reorganiza cada mosaico según su contenido y el ancho disponible.

## Elevation & Depth

La interfaz es plana. Las carpetas superpuestas y sus bloques de color dan profundidad. Mantén sin sombra la tarjeta de proyecto abierta, las imágenes y las tarjetas de cursos. La tarjeta abierta tampoco lleva franja de color.

El degradado lineal oscuro se reserva para la parte inferior de las portadas de proyecto. Su función es mantener legible el nombre en beige. Aplica el degradado de abajo hacia arriba, de café oscuro al 80 % a transparente, limitado al 45 % inferior de la imagen.

Al abrir un proyecto, oscurece el fondo con una capa independiente de la tarjeta. Usa café oscuro al 65 % para esta capa. La transparencia se limita a estos tratamientos funcionales y el texto conserva su opacidad.

## Shapes

Las imágenes, las tarjetas y las barras de idiomas tienen esquinas rectas de 0 px. Las etiquetas y los iconos de programas usan 5 px. Cada pestaña de carpeta tiene lados inclinados y un radio de 5 px en las esquinas superiores. Ajusta el ancho al texto y usa una altura mínima de 76 px en escritorio o 66 px hasta 650 px. Deja 40 px por encima de cada carpeta a partir de la segunda.

Usa círculos en el retrato y en los controles de contacto y reproducción. Aplica `rounded.full` a cajas cuadradas para formar los círculos.

## Components

### Navegación y enlaces

La barra usa fondo café claro, logo a la izquierda y enlaces beige a la derecha. Los enlaces llevan a Sobre mí, Proyectos, Cursos y Contacto. Al pasar el cursor cambian a azul claro.

Los enlaces de proyecto van subrayados en café claro sobre beige y pasan a vino al colocar el cursor. Usa «Ver proyecto completo ↗» como ejemplo de etiqueta.

El pie usa fondo café oscuro y texto beige. Cada vínculo de contacto lleva un botón circular beige con icono café oscuro. Al pasar el cursor, el texto se vuelve azul claro y se subraya, y el círculo también cambia a azul claro. Muestra el nombre de Lorena en Skynila. Los contactos son `vlorenatc@gmail.com`, `55 3124 8518` y `@vlorenadesign`.

### Retrato y cintas animadas

El retrato se coloca sobre un círculo azul claro. Deja que parte de la cabeza y el cabello sobresalgan del borde superior y recorta la parte inferior siguiendo el círculo.

Cruza dos cintas onduladas. La cinta vino lleva «LORENA TORRES» en azul claro y la cinta azul claro lleva «Diseñadora Gráfica» en vino. Usa Skynila y desplaza el texto a 42 unidades SVG por segundo. Cada vuelta recorre una frase completa.

Antes del pie, coloca una cinta horizontal vino con «Hagamos algo juntos» en Skynila azul claro. Separa cada repetición con un cuadrado azul claro. Las cintas se repiten en un ciclo continuo sin saltos ni cortes.

### Mosaicos y carpetas

Usa el mosaico tanto en las carpetas de proyectos como en las galerías abiertas. Combina módulos de una o varias filas y columnas según la cantidad y orientación de imágenes. Alinea bordes y separaciones. Ajusta el encuadre respetando las proporciones y el contenido importante.

Apila las carpetas con pestañas en distintas posiciones. Sus fondos son vino, café oscuro, café claro y beige, en ese orden. Las tres primeras llevan texto beige y la cuarta, café oscuro. Al abrir una, muestra su mosaico y cambia el signo de + a −. Mantén abierta una carpeta a la vez. Las muestras contienen 3, 6, 3 y 4 proyectos.

### Portadas y tarjetas de proyecto

La portada muestra el nombre en Roobert y beige sobre el degradado inferior. La ampliación de referencia de la imagen es de 1.025 en 400 ms. Las dos muestras de detalle usan 1.06 para hacer visible el efecto.

La tarjeta se abre dentro de la misma página. Usa superficie beige, nombre en Skynila vino, imagen principal a todo el ancho y descripción en café oscuro. En la variante con galería, coloca el mosaico después de la descripción. Cierra con la cruz café oscuro, la tecla Escape o un clic fuera.

La tarjeta abierta tiene un ancho máximo de 760 px y una altura máxima del 85 % de la ventana. El relleno de escritorio es de 56 px arriba, 36 px a cada lado y 32 px abajo. Aplica el ajuste de Layout hasta 700 px.

### Cursos

Las tarjetas beige van sobre la sección azul claro. Cada una incluye año, imagen a todo el ancho, nombre del curso y quién lo imparte. Usa café oscuro para los tres textos. Da al bloque de texto 36 px de relleno superior, 40 px de relleno inferior y 14 px entre el nombre y quien imparte el curso.

### Videos

Usa un círculo beige con el icono de reproducción en vino. Las relaciones de aspecto son 16:9 y 9:16. La tarjeta abierta incluye nombre, video y descripción. Expande el video horizontal al ancho disponible de la tarjeta y centra el vertical.

### Programas, etiquetas y barras de dominio

Los iconos de programas llevan logos beige en recuadros café oscuro de 5 px de radio. Las etiquetas usan azul claro con texto café oscuro en Roobert Medium de 16 px y radio de 5 px.

En las barras de dominio, usa base azul claro, relleno vino y esquinas rectas. Sobre beige, muestra nombre y nivel en café oscuro. Usa Roobert a 24 px para el nombre y Tome Sans Variable a 16 px para el nivel. En la muestra bajo «Barras de dominio», el nombre aparece a 18 px.

## Do's and Don'ts

### Sí

- Usa Skynila para títulos, Roobert para navegación, controles, subtítulos y nombres sobre portadas, y Tome Sans Variable para textos y créditos.
- Mantén el beige como fondo principal y usa textos claros sobre superficies oscuras.
- Conserva las alineaciones, los espacios y las proporciones. Da prioridad visual a los proyectos y mantén legibles sus nombres.
- Subraya los enlaces de proyecto y aplica el subrayado al contacto en hover.
- Mantén los ciclos de las cintas continuos.

### No

- Introducir otras familias tipográficas o colores.
- Aplicar degradados decorativos, sombras decorativas u opacidad al texto.
- Deformar imágenes o texto para encajarlos en una tarjeta o pestaña.
- Usar texto azul claro sobre beige.
- Reutilizar la misma composición de mosaico en todos los proyectos.
