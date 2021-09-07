# POSICIONAMIENTO DE IMAGEN

- Si voy a poner una imagen de fondo, es conveniente que la misma sea solo a modo decorativo, porque ya no va a contener el alt para que el navegador pueda leer lo que dice.
- Para poner las propiedades en el css no es importante en si el orden, siempre y cuandp np utilicemos el atajo. -
- Se pueden poner por orden alfabetico o tomando de lo mas general hacia lo mas especifico. 
- Si usamos el display-flex no deberiamos ponerlo en orden alfabetico.
- Si usamos el atajo el orden tiene que ser de forma alfabetica. Los valores del atajo son:
    - background (atajo)
        - background-color
        - background-image
        - background-repeat
        - background-attachment
        - background-position
        se ponen los valores sin tener que nombrar las propiedades.
- ES BUENA PRACTICA QUE SI VOY A USAR UNA IMAGEN DE FONDO  PONER UN COLOR YA QUE A VECES LAIMAGEN TARDA EN RENDERIZAR Y SI NO HAY COLOR PARECE QUE FALTARA ALGO. UNA VEZ QUE RENDERIZA LA IMAGEN VA A SOBRE ESCRIBIR EL COLOR. 
- Si usamos el contain en el background size, se ajusta al ancho de lo primero que encuentre.
- Cuando ponemos el Background position solemos ponerle center pero si lo queremos usar para mobile y mostras solo una parte de la imagen debemos ir dandole los valores que queremos.

## FONTS
Usamos la libreria de Google Fonts.
Tambien podemos usas Fontawesome, en la cual para poder obtener el enlace externo nos dirigimos a cdnjs, donde podemos encontrar todos los cdn de todas las librerias. cuando buscamos el fanwesome conviene buscar el que dice "all" para que llamemos a todos en el CSS. ESte lo ponemos en el HTML.

- Ya no se usan las fuentes genericas que nos da el VSC.
- Lo optimo es usar librerias mediante un url donde hay librerias que ya tiene las fuentes pero las mismas estan en un servidor. La libreria mas usada es google fonts.
- Sino podemos descargar las fuentes que querramos.
- Si queremos importar estilos de fuentes en css  utilizamos el @import.
- Si bien para exportar una fuente la podemos poner tanto en el html como en el css, es mejor ponerla en este ultimo, ya que si tengo varios html voy a tener que poner el link de la fuente en todos ellos.
- Cunado solo le  queremos dar color a uno solo de los parrafos que se encuentran en la clase, si ponemos .clase p{} eahi el navegador va a tomar a los hijos directos, por otro lado si queremos que tome a los nietos ponemos .clase> p{}.

## ICONOS
Utilizamos la libreria Fontawesome, en la cual para poder obtener el enlace externo nos dirigimos a cdnjs, donde podemos encontrar todos los cdn de todas las librerias. cuando buscamos el fanwesome conviene buscar el que dice "all" para que llamemos a todos en el CSS. ESte lo ponemos en el HTML.
Tambien tenemos flaticom.

- cuando copiamos el link nos suele trae dos clases, la primera es una clase dodne nos trae un icono solido y la segunda es la clase propia para que se pueda ver la canasta.
Si yo tengo intenciones de sobreescribir es conveniente crear una clase al lado.
