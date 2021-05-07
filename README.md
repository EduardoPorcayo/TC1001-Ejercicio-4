# TCH1001-Tiroparabolico
Pablo Michán
Eduardo Porcayo
El código del Juego del Tiro Parabólico original, lo pudimos encontrar en la siguiente liga: http://www.grantjenks.com/docs/freegames/cannon.html 

Para poder cambiar la velocidad, tanto de los objetivos como del proyectil, únicamente se modificaron los datos en las secciones ya antes preestablecidas de speed y target, donde al variar los números, podemos ya sea disminuir o aumentar la velocidad, que en este caso por la instrucción, se optó por aumentarla.

Para hacer el juego infinito se modificaron las lineas 71 para quitar un return y poner target.x = 200 para que el juego no acabara cuando una pelota zul tocara la parte izquierda de la pantalla y se re-dibujara a la derecha. Tambien se agrego en la linea 47 un if para limitar a 30 el numero de pelotas que pueden existir en pantalla.  
