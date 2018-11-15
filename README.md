# Esquema basico de una pagina web con html5 css3 y javascript

Esquema de pagina realizada con los estandares html5 y css3 con codigo javascript para gua de desarrollo de otras paginas

## Javascript

La finalidad principal de javascript es permitir la creacion de paginas dinamicas, con codigo que se ejecuta del lado del criente, disminuyendo la tarea del servidor y disminuyendo el numero de peticiones que se le hacen a este.

La inclusion de un codigo javascript en un documento HTML se indica mediante la inclucion de la siguiente linea en el encabezado

<script type="text/javascript"> y </script>

Sin embargo la mejor opcion es hacer un enlace a un archivo externo que contenga el codigo javascript, de la siguiente manera

<script type="text/javascript" scr="./js/script.js"></script>

Para que el documento quede validado, la etiqueta script debe tener el atributo  

type="text/javascript"

En el valor scr se indica la ruta y el nombre del archivo que contiene el codigo javascript que se desea ejecutar desde la pagina HTML.
