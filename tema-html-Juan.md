# 4. Imágenes y enlaces en HTML

## Etiqueta <img>

La etiqueta `<img>` se usa para insertar imágenes en una página web. Es una etiqueta vacía (no tiene cierre) y depende de dos atributos principales:

- **src**: indica la ruta o URL de la imagen que se quiere mostrar.
- **alt**: proporciona un texto alternativo que se muestra si la imagen no carga, y mejora la accesibilidad para lectores de pantalla.

<img src="imagenes/logo.png" alt="Logo de la universidad">

## Etiqueta <a>

La etiqueta `<a>` crea enlaces (hipervínculos) hacia otras páginas, sitios o recursos. El atributo principal es:

- **href**: define la dirección de destino del enlace (una URL, una página interna, un correo, etc.).

<a href="https://www.ejemplo.com">Visitar sitio web</a>

## Ejemplo combinado (imagen + enlace a MDN)

<a href="https://developer.mozilla.org/es/docs/Web/HTML">
  <img src="https://developer.mozilla.org/favicon-48x48.png" alt="Documentación de MDN Web Docs">
</a>
