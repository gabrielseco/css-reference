# Dynamic Pseudo Classes

Dynamic pseudoclasses son aquellas con las que aplicamos estilos cuando cambia un estado.

## Link pseudoclasses

:link --> se refiere a cualquier elemento ancla que sea un hyperlink y apunte a una dirección que no ha sido visitada.

:visited --> se refiere a cualquier elemento ancla que sea un hyperlink y ya haya sido visitado.

## User action pseudoclasses

:focus --> se refiere a cualquier elemento que tiene el foco.
:hover --> se refiere a cualquier elemento cuando el ratón pasa por encima
:active --> se refiere a cualquier elemento que ha sido activado por el usuario un click en un ancla o cuando un botón está siendo presionado.

[DEMO](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/user-action.html)

### Note: Dynamic styling

Si cambiamos los tamaños de fuentes con una pseudoclase podemos crear un reflow al tener el navegador que volver a pintar los elementos.
