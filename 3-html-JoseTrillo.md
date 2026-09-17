3. Comandos básicos en HTML
HTML utiliza diferentes etiquetas para crear y organizar el contenido de una página web. Cada etiqueta tiene una función específica, como crear títulos, párrafos, listas, tablas y definir la estructura de la página.
<html>
La etiqueta <html> es la etiqueta principal de un documento HTML. Indica que todo el contenido que se encuentra dentro pertenece a una página HTML.
Ejemplo:
HTML
<html>
    <!-- Contenido de la página -->
</html>
<head>
La etiqueta <head> contiene información y configuraciones de la página que normalmente no se muestran directamente en el contenido. Dentro de ella se puede colocar el título de la página y otros elementos.
Ejemplo:
HTML
<head>
    <title>Mi página web</title>
</head>
<title>
La etiqueta <title> sirve para establecer el título que aparece en la pestaña del navegador.
Ejemplo:
HTML
<title>Mi página web</title>
<body>
La etiqueta <body> contiene todo el contenido visible de la página web, como textos, títulos, imágenes, listas y tablas.
Ejemplo:
HTML
<body>
    <h1>Bienvenidos</h1>
    <p>Esta es mi página web.</p>
</body>
<h1>
La etiqueta <h1> se utiliza para colocar el título principal de una página. También existen <h2>, <h3> y otros niveles para colocar subtítulos.
Ejemplo:
HTML
<h1>Introducción a HTML</h1>
<p>
La etiqueta <p> se utiliza para escribir párrafos de texto.
Ejemplo:
HTML
<p>HTML es un lenguaje utilizado para crear y organizar páginas web.</p>
<br>
La etiqueta <br> permite realizar un salto de línea dentro de un texto.
Ejemplo:
HTML
<p>Hola<br>Bienvenidos a mi página.</p>
<ul>
La etiqueta <ul> se utiliza para crear una lista no ordenada. Sus elementos aparecen normalmente con viñetas.
Ejemplo:
HTML
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
<ol>
La etiqueta <ol> se utiliza para crear una lista ordenada. Sus elementos aparecen normalmente numerados.
Ejemplo:
HTML
<ol>
    <li>Primero abrir el editor</li>
    <li>Crear el archivo HTML</li>
    <li>Escribir el código</li>
</ol>
<li>
La etiqueta <li> representa cada elemento de una lista. Se utiliza dentro de las etiquetas <ul> o <ol>.
Ejemplo:
HTML
<ul>
    <li>Computadora</li>
    <li>Teclado</li>
    <li>Mouse</li>
</ul>
<table>
La etiqueta <table> se utiliza para crear una tabla. Las tablas permiten organizar información mediante filas y columnas.
Ejemplo:
HTML
<table border="1">
    <!-- Contenido de la tabla -->
</table>
<tr>
La etiqueta <tr> se utiliza para crear una fila dentro de una tabla.
Ejemplo:
HTML
<tr>
    <td>José</td>
    <td>20</td>
</tr>
<th>
La etiqueta <th> se utiliza para crear una celda de encabezado en una tabla. Generalmente el texto aparece resaltado.
Ejemplo:
HTML
<tr>
    <th>Nombre</th>
    <th>Edad</th>
</tr>
<td>
La etiqueta <td> se utiliza para crear una celda normal dentro de una tabla, donde se coloca la información.
<!DOCTYPE html>
<html>

<head>
    <title>Mi primera página</title>
</head>

<body>

    <h1>Introducción a HTML</h1>

    <p>HTML permite crear y organizar el contenido de una página web.</p>

    <h2>Lenguajes web</h2>

    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

    <h2>Estudiantes</h2>

    <table border="1">
        <tr>
            <th>Nombre</th>
            <th>Edad</th>
            <th>Curso</th>
        </tr>

        <tr>
            <td>José</td>
            <td>20</td>
            <td>Programación</td>
        </tr>

        <tr>
            <td>Ana</td>
            <td>21</td>
            <td>Base de Datos</td>
        </tr>
    </table>

</body>

</html>
Ejemplo:
HTML
<tr>
    <td>José</td>
    <td>20</td>
</tr>
