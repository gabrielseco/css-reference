## Feature queries

Nos permiten soportar progresivamente nuevas features presentes en los nuevos ordenadores.

Son muy similares a las media queries en estructura

```css
@supports (display: grid) {
  .main {
    display: grid;
  }
}
```

Se puede añadir un bloque supports dentro de media queries.

También se pueden hacer negaciones con el operador not

Sin embargo aquí se puede usar el operador or

```css
@supports (color: black) and ((display: flex) or (display: grid)) {
}
```
