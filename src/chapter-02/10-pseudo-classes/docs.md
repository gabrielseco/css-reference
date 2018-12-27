# Pseudo-Classes

Todas las pseudoclases sin excepción son una palabra precedida por el caracter :.

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

### Selecting the root element

existe la pseudoclase :root que seleciona la raíz del documento que en HTML siempre será la etiqueta html

### Selecting empty elements

Con la pseudoclase :empty puedes seleccionar elementos que no tienen hijos.

### Selecting unique children

Con la pseudoclase only-child puedes seleccionar cuando es el único hijo

### only-of-type

Funciona cuando es el unico elemento de su tipo aplica la clase

### Selecting first and last children

La pseudoclase first-child es usada para seleccionar el primer elemento.
La pseudoclase last-child es usada para seleccionar el último elemento

### Selecting first and last of type

El :first-of-type nos permite seleccionar el primer elemento de su tipo dentro de un contenedor.

El :last-of-type lo mismo pero la última ocurrencia.
