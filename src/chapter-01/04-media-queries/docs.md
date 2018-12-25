# Media Queries

Con las media queries podemos definir en que entorno ejecutar nuestro css.

Pueden ser usadas en:

- El atributo media del elemento link
- El atributo media del elemento style
- El media descriptor de un @import
- El media descriptor de un @media

Ejemplo de una media query en una presentación

```css
h1 {
  color: maroon;
}

@media projection {
  body {
    background: yellow;
  }
}
```

## Media Types

Existen 3 tipos

- all --> para todos los tipos
- print --> para impresoras
- screen --> para pantallas de escritorio

## Logical keywords

Existen el and para unir para condiciones

El not para negarlas.

El or no existe
