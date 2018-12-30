# Id selector and attribute selector specifity

Un selector id tiene una especifidad de 0, 1, 0, 0.

Mientras que uno de atributo sería como de clase 0, 0, 1, 0.

```css
#meadow {
  color: green; /* 0, 1, 0, 0 */
}
*[id="meadow"] {
  color: red; /* 0, 0, 1, 0 */
}
```

What happens if you create several dom nodes when same ids and you style them with the attribute selector?

[SHIT HAPPENS](https://htmlpreview.github.io/?https://github.com/gabrielseco/css-reference/blob/master/src/chapter-03/03-id-and-attribute-selector/index.html)
