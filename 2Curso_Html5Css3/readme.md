# Curso HTML5 y Css3 
## HTML 5
### Evolución de Html
1. Creado por TIm Berners  Lee en el CERN en 1991 1.0, derivado de SGML, inicialmente tenía 20 etiquetas que perduran 13 solo. 
1. La segunda versión 2.0 es del año 1994. Se agregaron 19 etiqeutas  y incluye Doctype y validaciones con DTD.
1. La tercera versión 3.2 fue ne 1996, primera versión desarrollada enteramente por W3C, aparece CSS y los navegadores empiezan a adoptarlo. 
1. Cuarta versión, también es una recomendación 4.01 en 1999. Incluye hojas de estilo y se mejoran la presentación de fuentes, fondos y colores. 
1. XHTML 1.0 en el 2000, mezcla html y xml y su rigidez para validar documentos. 
1. HTML 5 (2014), fue una recomendación aún no es estandar. Comenzó a desarrollarse por las pocas posibilidades complejas de XHTML. Incluye etiquetas semánticas, APIs, simplifica DOCTYPE, link y script y mejora de formularios. 

### Etiquetas 
Habrá una apertura entre <> , el contenido entre el cierre y la apertura. Puede haber etiqeutas sin contenido con la siguiente estructura <etiqueta .../&gt;

### Atributos 
Proporcionan información adicional sobre la etiqueta, se establecen en la apertura y no son obligatorios. Hay atributos generales y específicos según la etiqueta. Estructura = clave="valor".

Tanto las etiquetas como los atributos deben ir en minuscula.
Deberemos cerrar todos los elementos con contenido.         

### Comentarios
Los comentarios son texto que ponemos dentro de los archivos HTML que no son mostrados por los navegadores y que sirven para dar información adicional sobre el código HTML creado. Estructura. 
```html
<!--
    Esto es un comentario 
-->

```

### Estructura de página web 
Toda página web tiene forma de árbol(DOM). 

#### Cabecera 
No representa contenido alguno, contiene metadata que son elementos que describen la informacion de la pagina, contiene enlaces a scripts o archivos. Etiquetas:
- title :titulo página web
- style: link css
- link: enlazan archivos
- meta: describir página web, etiquetas que miran los buscadores 
    - <meta charset="utf8"&gt;
    - <meta name="description" content="Página web Ejemplo"/ &gt;
    - <meta name="keywords" content="tienda,boniatos,sevilla"/ &gt;
    - <meta name="autor" content="Alejandro Ruiz"/ >
    - <meta name="viewport" content="width=device-width, initial-scale=1.0"/ >
    - <meta http-equiv="refresh" content="30"/ >
- base: permite definir ruta por defecto. 

####  Body
- Las etiquetas &lt;h&gt; van del 1 al 6 dependiendo del tamaño, incluye negrita.


## CSS3