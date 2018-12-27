# Descendant selectors

El selector descendente no tiene noción de proximidad.

En el siguiente ejemplo el div aside cuando no tiene la clase help le pondría un color gray al span.

Sin embargo la siguiente regla dice que cualquier span dentro de la clase .help es rojo.

Gana la segunda regla al tener la misma especifidad y estar después.

```html
<div class="help">
  <div class="aside">This text contains <span>a span element within</span></div>
</div>
```

```css
div:not(.help) span {
  color: gray;
}

div.help span {
  color: red;
}
```
