# EX_01

Definimos la URL del sistemap de Xataka.
Creamos un objeto URL a partir de la cadena de la URL.
Establecemos una conexión HTTP con el server.
Configuramos la solicitud HTTP para utilizar el método "GET".
Leemos el contenido del sistemap y lo almacenamos en un StringBuilder.
Utilizamos DocumentBuilderFactory y DocumentBuilder para analizar el contenido del XML.
Extraemos las URL del elemento "loc" del sistemap y se imprimen en la consola.
Utilizamos una serie de excepciones, como IOException y Exception, solo en el caso de que se produzcan errores en la conexión del XML.

# EX_02

Definimos la URL del sistemap inicial de Xataka.
"processSistemap se encarga de procesar un sistemap dado y sus enlaces anidados. Lanza excepciones de tipo IOException y Exception.
Configuramos una conexión HTTP y leemos el contenido del sistemap.
Analizamos el contenido XML con DocumentBuilderFactory y DocumentBuilder.
Extraemos las URL del elemento "loc" del sistemap y se imprimen en consola.
Verificamos si hay sistemaps anidados.
El método processNewsSistemap se utiliza para procesar sistemaps de noticias y mostrar sus URL.

# EX_03

Definimos la URL del sistemap de Xataka y la carpeta de salida para almacenar los archivos.
Mismo código que los dos ejercicios anteriores.
"processNewsSitemap" se utiliza para procesar sitemaps de noticias y almacenar sus URL en archivos locales.
