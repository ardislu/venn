# venn

## Deprecated March 2023

My original idea for this was to use trigonometry to dynamically calculate the appropriate `x` and `y` attributes for each `<text>` element based on the total number of items and the size of the diagram. Then the resulting SVG could be easily copied into any document since the coordinates would be hardcoded into the SVG.

However, it's much easier and faster to use the [`shape-outside` CSS property](https://developer.mozilla.org/en-US/docs/Web/CSS/shape-outside) to achieve this effect! This CSS property basically makes my original approach obsolete, so I'm archiving this project.

---

Quickly make a [Venn diagram](https://en.wikipedia.org/wiki/Venn_diagram) SVG element that can be copied into any HTML document.
