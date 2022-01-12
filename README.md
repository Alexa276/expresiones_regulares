## Expresiones Regulares Alexa Reyes

 **Nivel 1**

 Con las expresiones regulares, podemos utilizar . (un punto) como un comodín que simboliza un carácter 
 cualquiera (¡sólo uno!), de modo que si escribes dos puntos simboliza una palabra con dos 2 carácteres. 
 ¿Cómo representarías, por ejemplo, un DNI (que está formado por 8 dígitos + 1 letra)? 

 *<input pattern=".........">*

 **Nivel 2**

 Sin embargo, esto es sólo un ejemplo inicial y no tiene demasiado sentido. Vamos con algo más útil... Si nos fijamos en su primer carácter ¿Cómo podríamos seleccionar sólo el personaje feliz?

 *<input pattern="8.......A">*