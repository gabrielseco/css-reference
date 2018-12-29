# Dynamic Pseudo Classes

Dynamic pseudoclasses son aquellas con las que aplicamos estilos cuando cambia un estado.

## Link pseudoclasses

:link --> se refiere a cualquier elemento ancla que sea un hyperlink y apunte a una dirección que no ha sido visitada.

:visited --> se refiere a cualquier elemento ancla que sea un hyperlink y ya haya sido visitado.

## User action pseudoclasses

:focus --> se refiere a cualquier elemento que tiene el foco.
:hover --> se refiere a cualquier elemento cuando el ratón pasa por encima
:active --> se refiere a cualquier elemento que ha sido activado por el usuario un click en un ancla o cuando un botón está siendo presionado.

[DEMO](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/user-action.html)

### Note: Dynamic styling

Si cambiamos los tamaños de fuentes con una pseudoclase podemos crear un reflow al tener el navegador que volver a pintar los elementos.

## UI-State pseudoclases

:enabled --> Se refiere a un elemento de UI como elementos de formulario que se encuentran habilitados.

:disabled --> Se refiere a un elemento de UI como elementos de formulario que se encuentran deshabilitados.

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/enabled-disabled.html)

:checked --> Si un elemento radio-button o checkbox ha sido seleccionado.

:indeterminate --> Un elemento radio-button o checkbox no ha sido ni seleccionado ni desmarcado. [caniuse](https://caniuse.com/#feat=css-indeterminate-pseudo)

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/checked.html)

:default --> se refiere a un radio button, checkbox u opción que ha sido seleccionada por defecto.

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/default.html)

:required ---> se refiere a un elemento en el que el usuario tiene que introducir el valor.

:optional --> se refiere a un elemento en el que no necesita introducir el valor.

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/required.html)

:valid --> se refiere si input es válido
:invalid --> se refiere si un input es inválido

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/valid.html)

:in-range --> se refiere un input que está entre el rango mínimo y el máximo
:out-of-range --> se refiere a un input que se encuentra fuera del rango mínimo y el máximo.

No hay soporte para ie 10 y 11 😔

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/range.html)

:read-write --> Se refiere a un input que es editable
:read-only --> Se refiere a un input que no puede ser editado.

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/11-dynamic-pseudo-classes/readonly.html)
