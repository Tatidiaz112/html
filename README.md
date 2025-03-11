# html
**HTML (HyperText Markup Language)** es el lenguaje de marcado estándar utilizado para crear páginas web. Se utiliza para estructurar y presentar contenido en la web, como texto, imágenes, enlaces, formularios y otros elementos multimedia.

### Elementos clave de HTML:

1. **Etiquetas (Tags):**
   HTML está basado en etiquetas que indican cómo debe estructurarse y mostrarse el contenido. Las etiquetas están rodeadas por corchetes angulares (`< >`).
   Ejemplo:
   ```html
   <h1>Encabezado principal</h1>
   ```

2. **Estructura básica de un documento HTML:**
   Un archivo HTML típico tiene la siguiente estructura:
   ```html
   <!DOCTYPE html>
   <html lang="es">
     <head>
       <meta charset="UTF-8">
       <title>Título de la página</title>
     </head>
     <body>
       <h1>Bienvenido a mi página web</h1>
       <p>Esto es un párrafo de texto.</p>
     </body>
   </html>
   ```

3. **Etiquetas comunes:**
   - **`<html>`:** Indica el inicio del documento HTML.
   - **`<head>`:** Contiene información no visible directamente en la página (metadatos, título, enlaces a hojas de estilo, etc.).
   - **`<title>`:** Define el título de la página que aparece en la pestaña del navegador.
   - **`<body>`:** Contiene el contenido visible de la página.
   - **`<h1>`, `<h2>`, ... `<h6>`:** Encabezados de diferentes niveles.
   - **`<p>`:** Define un párrafo de texto.
   - **`<a href="">`:** Crea un enlace a otra página o recurso.
   - **`<img src="">`:** Inserta una imagen.
   - **`<ul>` y `<ol>`:** Listas desordenadas y ordenadas, respectivamente.
   - **`<li>`:** Elementos de una lista.

4. **Atributos:**
   Las etiquetas pueden tener atributos que modifican su comportamiento o apariencia.
   Ejemplo:
   ```html
   <a href="https://www.ejemplo.com" target="_blank">Enlace</a>
   ```
   En este caso, `href` es el atributo que define la URL y `target="_blank"` indica que el enlace se abrirá en una nueva pestaña.

5. **Comentarios:**
   Los comentarios no se muestran en la página, pero son útiles para dejar notas en el código.
   ```html
   <!-- Esto es un comentario -->
   ```

### Propósito de HTML:
HTML se encarga de la **estructura** y el **contenido** de una página web. No define la apariencia, que se maneja con CSS, ni la interactividad, que se gestiona con JavaScript. Sin embargo, HTML es fundamental para crear la base sobre la que se desarrollan los sitios web.

Este es un resumen básico de HTML, pero existen muchas más etiquetas y conceptos avanzados que permiten crear sitios web más complejos y dinámicos.
