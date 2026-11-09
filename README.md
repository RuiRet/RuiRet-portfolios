# RuiRet Portfolio's

Autora: Ana Belén Ruiz Retamero
Curso: 1º DAM A
Fecha: 2026

## 1. Descripción del proyecto

RuiRet Portfolio's es una página web personal creada como portfolio para presentar mis conocimientos, proyectos e intereses relacionados con el desarrollo de videojuegos, la programación y el diseño 3D.

El objetivo principal es disponer de un espacio donde mostrar mi evolución como desarrolladora, compartir algunos de mis trabajos y dar a conocer las herramientas y tecnologías que utilizo.

## 2. Estructura de la página web

El proyecto está formado por cinco páginas HTML principales:

- **Inicio (`index.html`):** presentación personal, formación, conocimientos y proyectos destacados.
- **Programación y Proyectos (`proyectos.html`):** artículos y contenido relacionado con programación y desarrollo de videojuegos.
- **Herramientas y Tecnologías (`tabla.html`):** tabla con las herramientas y tecnologías que utilizo o estoy aprendiendo.
- **Galería (`galeria.html`):** recopilación de imágenes, referencias visuales, relacionado con el desarrollo de los modelos.
- **Contacto (`formulario.html`):** formulario de ejemplo para recoger información sobre posibles consultas o proyectos.

Además, el proyecto incluye un archivo `rss.xml`, que permite ofrecer un canal RSS con las últimas novedades del portfolio.

## 3. Tecnologías utilizadas

Para desarrollar la página he utilizado principalmente:

- **HTML5:** para estructurar el contenido mediante etiquetas semánticas.
- **Git:** para controlar las versiones y registrar los cambios realizados durante el desarrollo.
- **GitHub:** para alojar el repositorio y gestionar el proyecto.
- **GitHub Pages:** para publicar la página web y permitir su acceso desde Internet.

También se han utilizado diferentes formatos multimedia, como SVG, PNG, JPG, WebP, MP4 y archivos de audio.

## 4. Problemas y dificultades durante el desarrollo

Daurante la realización del proyecto, he afrentado distintos problemas a los cuales se les ha buscado solución.

### 4.1. Problemas con Git y GitHub

Uno de los principales problemas que tuvimos fue al intentar subir el proyecto al repositorio de GitHub. El vídeo utilizado en la página ocupaba demasiado espcio y GitHub rechazaba por el peso del archivo.

Para solucionarlo, había dos opciones, subir el vídeo a Youtube o comprimirlo. Como la práctica exigía un vídeo local, decidí comprimirlo. El problema llegó cuando al revisar el historial de Git, y el vídeo sin comprimir seguía apareciendo en commits anteriores.

Usé una herramienta de Git para limpipar el historial del repositorio, eliminando la versión antigua del vídeo, sin modificar el resto de contenido de los commits, y volviendo a subir la versión comprimida.

Este proceso me permitió aprender más sobre los commits, el historial de versiones, los archivos pesados y los problemas que pueden aparecer al trabajar con repositorios remotos.

### 4.2. Problemas con los archivos XML

Durante la creación del archivo RSS aparecieron errores de validación relacionados con la declaración XML.

El problema estaba relacionado con la posición y el formato de la declaración inicial del documento. Fue necesario revisar el contenido del archivo para asegurar que la declaración XML estuviera correctamente situada al principio.

### 4.3. Organización y referencias multimedia

La incorporación de imágenes, vídeos y audios también requirió prestar atención a las rutas de los archivos, sus formatos y su organización dentro de las carpetas del proyecto.

Además, fue necesario trabajar con un mapa de imágenes para crear diferentes zonas interactivas dentro de una misma imagen.

## 5. Mejoras futuras

La idea es hacer que RuiRet porfotlio's ea algo más que un simple proyecto de clase, y se pueda llevar a otros ámbitos y sacarle provecho.

Entre las mejoras que tengo previstas se encuentran:

- **Diseño visual:** Una vez aprendidos los conceptos de CSS necesarios para darle vida a la página.
- **Proyectos interactivos:** Añadir zonas interactivas de vidoejuegos, incluso en algún futuro una opción de que la página web pueda ser un propio videojuego.
- **Galería multimedia:** Añadir más imágenes, vídeos y referencias de mis proyectos, incluyendo modelos 3D y procesos de desarrollo.
- **Blog:** Publicar artículos sobre programación, resolución de problemas y experiencias durante el desarrollo de videojuegos.

## 6. Conclusión

La realización de este proyecto me ha permitido poner en práctica los conocimientos adquiridos sobre desarrollo web, especialmente en HTML5, organización de archivos, contenido multimedia y control de versiones.

También me ha ayudado a comprender que desarrollar una página web no consiste únicamente en escribir código, sino que implica planificar, probar, detectar errores y buscar soluciones.

Considero que este portfolio es una primera versión de un proyecto que podré mejorar y ampliar a medida que avance en mi formación como desarrolladora.

---

**Proyecto:** RuiRet Portfolio's  
**Repositorio:** https://github.com/RuiRet/RuiRet-portfolios  
**Página web:** https://ruiret.github.io/RuiRet-portfolios/