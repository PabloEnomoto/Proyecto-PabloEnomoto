//COMO EMPEZAR A COMPILAR SASS//

1. Abrir la consola en esta carpeta con ctrl+ñ
    a. npm install nodemon node-sass
    b. npm init

2. Abrir el archivo package.json y editarlo
    a. A continuación de && exit 1" colocar una , presionar enter
    y pegar el siguiente texto:
    
"build-css": "node-sass --include-path scss scss/main.scss css/style.css",
"watch-css": "nodemon -e scss -x \"npm run build-css\""
    
3. Crear las carpetas con sus respectivos archivos
    a. scss/main.scss
    b. css/style.css
    
4. En la consola correr el comando
    a. npm run build-css //Por unica vez
    b. npm run watch-css
    
5. Cada vez que se quiera seguir compilando en SASS
    a. abrir la consola con ctrl+ñb. npm run watch-css
    
//FIN

<-----------------------SEO-------------------------------->

<------------INDEX----------------->
AGREGUE LA DESCRIPTION
description (Adentrate en nuestra pagina para conocer a fondo a todos aquellos personajes, peliculas y series que han formado parte del equipo X-Men)
AGREGUE LAS KEYWORDS
keywords (x men, super heroes, marvel, mutantes, super poderes)

<------------CONTACTO----------------->
AGREGUE LA DESCRIPTION
description (Adentrate en nuestra pagina para conocer a fondo a todos aquellos personajes, peliculas y series que han formado parte del equipo X-Men)
AGREGUE LAS KEYWORDS
keywords (x men, super heroes, marvel, mutantes, super poderes contacto x men)

<------------HISTORIA----------------->
AGREGUE LA DESCRIPTION
description (Adentrate en nuestra pagina para conocer a fondo a todos aquellos personajes, peliculas y series que han formado parte del equipo X-Men)
AGREGUE LAS KEYWORDS
keywords (x men, super heroes, marvel, mutantes, super poderes historia x men)

<------------PELICULAS----------------->
AGREGUE LA DESCRIPTION
description (Adentrate en nuestra pagina para conocer a fondo a todos aquellos personajes, peliculas y series que han formado parte del equipo X-Men)
AGREGUE LAS KEYWORDS
keywords (x men, super heroes, marvel, mutantes, super poderes, peliculas x men)

<------------PERSONAJES----------------->
AGREGUE LA DESCRIPTION
description (Adentrate en nuestra pagina para conocer a fondo a todos aquellos personajes, peliculas y series que han formado parte del equipo X-Men)
AGREGUE LAS KEYWORDS
keywords (x men, super heroes, marvel, mutantes, super poderes, personajes x men)

<------------SERIES----------------->
AGREGUE LA DESCRIPTION
description (Adentrate en nuestra pagina para conocer a fondo a todos aquellos personajes, peliculas y series que han formado parte del equipo X-Men)
AGREGUE LAS KEYWORDS
keywords (x men, super heroes, marvel, mutantes, super poderes, series x men)

<------------MIXIN----------------->
lo agregue en el scss _historia, para darle estilo al boton que te lleva al principio de la pagina
    button {
        a {
            @include btn-irArriba (black, none)
        }