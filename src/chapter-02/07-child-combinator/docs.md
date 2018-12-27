# Child combinator selector

Se puede usar cuando prefieres seleccionar un elemento hijo de un elemento

## [Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/07-child-combinator/index.html)

Explicación de la demo selecciona cualquier elemento strong que sea hijo directamente del h1

```html
<h1>This is <strong>very</strong> important.</h1>
<h1>
  This is <em>really <strong>very</strong></em> important.
</h1>
```

```css
h1 > strong {
  color: red;
}
```
