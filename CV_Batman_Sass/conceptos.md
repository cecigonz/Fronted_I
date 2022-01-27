# INTRODUCCION CSS

## Formas de vincularse

- Interna: ya no utiliso el atributo style son una etiqueta de apertur y cierre y todo lo que  vaya dentro de eta etique van a ser los estilo que voy a utilizar para el documento
- Externa: paraponer una archivo dentro de un documento html de forma externa se pone en el head por medio d etqiueta link donde con un href"" se vincula el documento CSS. este es la practica mas usada porque esta mas organizado y tengo a todos los estilos dentro de un solo documento.
- En linea: es cuando lo pones en la etiueta de apetura y es decirle al navegador que voy a utilizar CSS utilizando el atributo Style, propiedad: valor; propiedad:valor; etc. dentro de una etiqueta. 

## Regla de CSS

Puede abarcar a uno o mas elementos sobre todo cuando compraten estilo es conveniente agruparlos.
Se puede poner:
h1,h2 {
    width;
    top;}

- Las propiedades y valores se eacriben entre llaves.

## Tipo de selectores

- h1: se puede poner el nombre de la etiqueta directaentre, pero la misma va a afectar a todas las etiquetas del mismo mnombre.
- #saludo (id=""): este es unico y se usa para cuando tenemos una fucncionalidad. En CSS el id tiene mas importancia.
- .nav-menu (class=""): este se puede usar muchas veces en distintas etiquetas.

## Estilos den html y CSS

- Si tengo estilos en el head y despues en resto del documeto html primero va a tomar los que se pongan en el head.
- Cuando ponemos un estilo en una etiqueta y en el head, el navegador toma como prioridad lo que es en el navedagor en linea.
- Siempre la hoja de estilo final va al ultimo dentro del head. Esto es para que pise las propiedades que pueden llegar a tener los otros links que pongamos, ya qeu como bustrap o fontosom ya tienen estilos y clases y con la hoja de estilo  le agregamos nuestras propias clases y commo la ponemos al ultimo el navegador le da prioridad y de esa forma podemos sobreescribir tranquilos.

## Estilos Generales

- H1, h2, parrafos, margenes, bullet, etc.

### ID

### CLASES



### ELEMENTOS PREVALENTES POR UBICACIÓN

- No importa en que ubicación este la clase siempre va a enr prioridad.
- Si pusieramos una regla  en dos estilos iguales, el navegador tomara  primero el ultimo estilo que hayamos escrito.

### COLORES 
ColorZilla es una extencion que nos instala un lapiz para ver cual es el color que tiene una pagina

- RGBA: se usa cuando queremos darle transparencia al color entonce el % que le pongamos a A va a ser la transparencia que va a tener. Se pone con un .5, y este va a ser el porsentaje qdel 1 al 100 que va a tener de transparencia.
- OPACITY: la diferencia que tiene con el rgba es que el opacity se hereda, mientras que el rgba solo va a impactar su trasparencia al elemento al que le asignemos ese color.
- EXADECIMAL: puedo dar trasnparencia, pero como sigo estando en el sitema de 0 a 1 le tengo que agregar un cuarto par para el numero. EJ:abb7d380, el ultimo numero hace referencia al porcentaje dde opacidad.

### FONTS

- Font-size: es el tamaño de la fuente en px. Hay algunas fuentes que tienen su tamaño por defecto como los parrafosque tienen 16px.
- Font-weith: es el grosor de cada letra. El 900 es el mas alto y si superamos ese tenemos el bold o border.
- Font-family: no solemos trabajr las fuentes que vienen por defecto en el navegador, sino que descargamos librerias o descargamos en nuestro proyecto y llamamos a esas fuentes. Igualemente hay que poner varias opciones de fuentes por si el navegador no me toma la primera asi sigue con las segunda. Se puede usar google fonts o dafonts. Si se descargan las fuentes hacemos una carpeta nueva que contrenga las fuentes.
- Text-align: este se suele usar por defecto el centrado sobre todo en los titulos. 
- Text-transform: me aseguro que todos los titulos esten en mayuscula.
