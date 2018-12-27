# Selecting following siblings

Podemos seleccionar cualquier elemento que siga un elemento cuando comparten el mismo padre.

Esto se puede hacer con el caracter tilda.

Ejemplo:

Selecciona todos las listas ordenadas que sigan al h2. No tienen que ser hermanos adjacentes.

```css
h2 ~ ol {
  font-style: italic;
}
```

## [Demo](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-02/09-selecting-following-selectors/index.html)
