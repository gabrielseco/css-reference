# Pseudo-Classes

Todas las pseudoclases sin excepción son una palabra precedida por el caracter :

Las pseudoclases hacen referencia al elemento con el que van juntas

CSS permite encadenar pseudoclases juntas.

```css
.btn:link:hover {
  color: red;
}

.btn:visited:hover {
  color: maroon;
}
```

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/chaining-pseudo-classes.html)

### Selecting the root element

existe la pseudoclase :root que seleciona la raíz del documento que en HTML siempre será la etiqueta html

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/root.html)

### Selecting empty elements

Con la pseudoclase :empty puedes seleccionar elementos que no tienen hijos.

### Selecting unique children

Con la pseudoclase only-child puedes seleccionar cuando es el único hijo

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/only-child.html)

### only-of-type

Funciona cuando es el unico elemento de su tipo aplica la clase

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/only-of-type.html)

### Selecting first and last children

La pseudoclase first-child es usada para seleccionar el primer elemento.
La pseudoclase last-child es usada para seleccionar el último elemento

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/first-and-last.html)

### Selecting first and last of type

El :first-of-type nos permite seleccionar el primer elemento de su tipo dentro de un contenedor.

El :last-of-type lo mismo pero la última ocurrencia.

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/first-of-type.html)

### Selecting every nth-child

Al igual que podemos seleccionar el primer hijo o el último hijo de también podemos seleccionar el tercero o el cuarto, esto se puede hacer con la pseudoclase :nth-child

En nth-child podemos pasar como argumento un numero o una serie por ejemplo

```css
ul > li:nth-child(3n) {
  text-transform: uppercase;
}
```

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/nth-child.html)

Tenemos las palabras even (par) y odd (impar) para seleccionar elementos con nth-child

```css
tr:nth-child(odd) {
  background: silver;
}

tr:nth-child(even) {
  background: gray;
  color: white;
}
```

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/even-odd.html)

### Selecting every nth of type

En teoría nth-of-type tiene más especifidad que nth-child

[Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/10-pseudo-classes/nth-of-type.html)
