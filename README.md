# Proyecto Pentagame - Sitio Web de Videojuegos
## Descripción General
Pentagame es un sitio web informativo dedicado al mundo de los videojuegos. El proyecto está estructurado como un sitio web estático con múltiples páginas que abarcan diferentes aspectos de la cultura gamer, desde la historia de los videojuegos hasta los géneros y plataformas disponibles en la actualidad.

## Estructura del Proyecto
### Organización de Carpetas
- Carpeta Raíz : Contiene el archivo index.html y el README.md
- _css/ : Contiene los archivos de estilos CSS
- _html/ : Contiene las páginas HTML secundarias
- _img/ : Almacena todas las imágenes utilizadas en el sitio
### Archivos Principales HTML
- index.html : Página principal del sitio que presenta una introducción general
- _html/historia.html : Página que narra la evolución de los videojuegos desde sus inicios hasta la actualidad
- _html/generos.html : Página que describe los diferentes géneros de videojuegos con ejemplos
- _html/plataformas.html : Página que muestra las diferentes plataformas de juego disponibles
- _html/contacto.html : Página con un formulario de contacto e información de la empresa CSS
- _css/styles.css : Archivo que contiene todos los estilos del sitio, incluyendo diseño responsivo Imágenes
El directorio _img/ contiene numerosas imágenes utilizadas en el sitio, incluyendo:

- Capturas de juegos clásicos (Pong, Spacewar)
- Carátulas de juegos populares (Call of Duty, The Legend of Zelda, etc.)
- Imágenes de consolas y plataformas (PS5, Xbox Series, Nintendo Switch, etc.)
- Logos de tiendas digitales (Steam, App Store, Play Store)
## Tecnologías Utilizadas
### HTML5
- Estructura semántica con uso de etiquetas como <header> , <nav> , <main> , <section> , <article> , <aside> y <footer>
- Formularios interactivos con diversos tipos de inputs
- Enlaces internos para navegación entre páginas
### CSS3
- Diseño responsivo mediante media queries
- Sistema de grid para layouts flexibles
- Animaciones y transiciones para mejorar la experiencia de usuario
- Estilos personalizados para cada sección temática
## Características del Sitio
### Navegación
- Menú de navegación consistente en todas las páginas
- Indicador visual de la página actual mediante clase "active"
- Enlaces internos para facilitar la navegación entre secciones relacionadas
### Contenido
- Historia : Línea temporal de la evolución de los videojuegos por décadas
- Géneros : Clasificación y ejemplos de los principales géneros de videojuegos
- Plataformas : Información sobre consolas, PC y dispositivos móviles para jugar
- Contacto : Formulario para comunicación con los administradores del sitio
### Diseño Visual
- Paleta de colores coherente con predominio de verdes (#4caf50) y grises
- Tarjetas informativas para presentar contenido de manera organizada
- Imágenes ilustrativas para cada sección
- Diseño adaptable a diferentes tamaños de pantalla
## Aspectos Destacados
- Uso de grid layouts para organizar contenido en tarjetas
- Implementación de formularios con validación
- Estructura de navegación intuitiva
- Diseño responsivo que se adapta a dispositivos móviles y de escritorio
- Organización modular del código CSS
## Posibles Mejoras Futuras
- Implementación de JavaScript para añadir interactividad
- Galería de imágenes con lightbox
- Sistema de comentarios para los usuarios
- Integración con bases de datos para contenido dinámico
- Optimización de imágenes para mejorar el rendimiento
### HTML
- Uso de DOCTYPE HTML5
- Atributo lang="es" para especificar el idioma
- Metaetiquetas para codificación UTF-8 y viewport responsive
- Estructura semántica con elementos HTML5
- Atributos required para validación de formularios
- Atributos alt en imágenes para accesibilidad
- Rutas relativas para enlaces e imágenes
### CSS
- Selectores de clase para estilos específicos
- Selectores descendentes para elementos anidados
- Pseudo-clases como :hover para interactividad
- Propiedades de transformación para efectos visuales
- Transiciones para animaciones suaves
- Variables de color mediante valores hexadecimales
- Unidades relativas (rem) para tipografía escalable
- Función repeat(auto-fit, minmax()) para layouts responsivos
### Optimización
- Minificación de CSS (compresión de código eliminando espacios y saltos de línea)
- Reutilización de clases para mantener el código DRY (Don't Repeat Yourself)
- Organización modular del CSS por componentes y secciones