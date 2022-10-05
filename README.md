#Interface design

```sh
<!DOCTYPE html>
<html lang="en">
<!--   Lenguage de la web -->
  <head>
    <base href="http://192.168.64.2/" />
    <!-- BASE Hace una ruta relativa para redirección -->
    <meta charset="UTF-8" />
    <!-- charset  unicode, todos los idiomas, emojis... -->
    <meta name="description" content="This is my first webpage ... " />
    <!-- en name pones el nombre del metadato. y en content el metadato: En desctiption es una descripción en lenguaje natural  -->
    <meta name="keywords" content="coding, html, programming" />
    <!-- keywords ayuda a posicionarnos frente a los motores de búsqueda -->
    <meta name="author" content="Autor de la página web" />
    <!-- Autor de la página web -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <!-- Para dar soporte a las versiones antiguas de IE -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- El conjunto de cosas que se muestra en pantalla, es decir si no se pone, las páginas responsives no se muestran, es la referencia de estas-->
    <meta name="generator" content="Programa" />
    <!-- Si nuestra página web ha sido creada de forma automáticamente con un programa -->
    <link rel="stylesheet" href="style.css" />
    <!-- Señalar contenido que tiene relación con el html de la web, tienes que poner en rel la palabra cable -->
    <link rel="icon" href="icon.favicon" />
    <!-- Favicon de la web -->
    <title>My first webpage</title>
  </head>
  <body>
    <!-- etiquetas en bloque #–-->
    <div></div>
    <header></header>
    <nav></nav>
    <footer></footer>
    <article></article>
    <section></section>
    <aside></aside>
    <main></main>

    <!-- etiquetas de línea # # #-->

    <a href=""></a>
    <abbr title=""></abbr>
    <span></span>
    <script></script>
    <del></del>
    <button></button>
    <img src="" alt="" />

    <!-- id / class -->
    <!--

    - id -> Identificador único, se recomienda que no se use para css, se recomienda su uso en JS pero hay 2 escuelas de pensamiento ID/CLASS. No se pueden sumar IDs.
    id Selector -> # ej #p1
    - class ->  Se recomienda su uso para definir en CSS las clases, se pueden ir sumando clases <p class="p2 p3 p4">
    class selector -> . ej .p2

   !important : Se salta la jerarquía de css.
  -->

    <!-- TEXTO
  <h1><h6>
  <p>
  <pre>

  -->

</html>

```
