🌐 Fundamentos de HTML5

¡Bienvenido/a a este repositorio! Aquí encontrarás una guía práctica, notas y ejemplos sobre los fundamentos de HTML5 (HyperText Markup Language), el lenguaje de marcado estándar utilizado para estructurar páginas web.

Este recurso está diseñado tanto para quienes están comenzando en el mundo del desarrollo web como para quienes buscan repasar los conceptos esenciales.

📋 Tabla de Contenidos

¿Qué es HTML?

Estructura Básica de un Documento

Etiquetas y Conceptos Clave

Encabezados y Párrafos

Formateo de Texto

Enlaces e Imágenes

Listas

Formularios y Tablas

HTML Semántico

Cómo Ejecutar estos Ejemplos

Recursos Recomendados

Contribuciones

Contacto y Licencia

❓ ¿Qué es HTML?

HTML (HyperText Markup Language) es el bloque de construcción más elemental de la web. Define el significado y la estructura del contenido web. Utiliza "etiquetas" (<tag>) para indicar al navegador cómo debe mostrar el texto, las imágenes y otros elementos multimedia.

🏗️ Estructura Básica de un Documento

Todo documento HTML5 bien estructurado sigue esta plantilla esencial:

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la Página</title>
</head>
<body>
    <h1>¡Hola, mundo!</h1>
    <p>Este es mi primer documento HTML.</p>
</body>
</html>


🏷️ Etiquetas y Conceptos Clave

Encabezados y Párrafos

<h1>Encabezado Principal (H1)</h1>
<h2>Subtítulo (H2)</h2>
<!-- Se pueden usar hasta <h6> -->
<p>Este es un párrafo de texto.</p>


Formateo de Texto

<strong>Texto en negrita con importancia semántica</strong>

<em>Texto en cursiva o énfasis</em>

<mark>Texto resaltado</mark>

Enlaces e Imágenes

<!-- Enlace externo -->
<a href="https://developer.mozilla.org" target="_blank" rel="noopener noreferrer">MDN Web Docs</a>

<!-- Imagen -->
<img src="ruta/a/imagen.jpg" alt="Descripción de la imagen para accesibilidad">


Listas

<!-- Lista desordenada (viñetas) -->
<ul>
    <li>Elemento 1</li>
    <li>Elemento 2</li>
</ul>

<!-- Lista ordenada (números) -->
<ol>
    <li>Primer paso</li>
    <li>Segundo paso</li>
</ol>


HTML Semántico

El uso de etiquetas semánticas ayuda a la accesibilidad y al SEO:

<header>: Encabezado del sitio o sección.

<nav>: Menú de navegación.

<main>: Contenido principal único.

<section>: Sección genérica de contenido.

<article>: Contenido independiente (ej. entrada de blog).

<footer>: Pie de página.

🚀 Cómo Ejecutar estos Ejemplos

Clona el repositorio:

git clone https://github.com/tu-usuario/nombre-de-tu-repo.git


Abre el proyecto:
Navega a la carpeta e ingresa a los archivos .html.

Visualiza en el navegador:

Haz doble clic en cualquier archivo .html para abrirlo en tu navegador predeterminado.

Tip: Si usas Visual Studio Code, puedes instalar la extensión Live Server para ver los cambios en tiempo real.

📚 Recursos Recomendados

📖 MDN Web Docs - HTML

🌐 W3Schools - HTML Tutorial

🎨 W3C Markup Validation Service (Para validar tu código HTML)

🤝 Contribuciones

¡Las contribuciones, correcciones o sugerencias son bienvenidas!
Si deseas aportar:

Haz un Fork de este proyecto.

Crea una rama para tu función (git checkout -b feature/NuevaCaracteristica).

Haz Commit de tus cambios (git commit -m 'Añade nueva característica').

Haz Push a la rama (git push origin feature/NuevaCaracteristica).

Abre un Pull Request.

📜 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo LICENSE para más detalles.
