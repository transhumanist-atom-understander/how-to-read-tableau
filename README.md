Source for a LessWrong post on the tableau method for modal logic.

Tableaux are rendered using the `prooftrees` package for TeX.

To generate the final Markdown for the post and to convert TeX diagrams to images, we use [Quarto](https://quarto.org) with the [`danmackinlay/quarto_tikz`](https://github.com/danmackinlay/quarto_tikz) extension:

```
quarto render how-to-read-tableaux.qmd
```
