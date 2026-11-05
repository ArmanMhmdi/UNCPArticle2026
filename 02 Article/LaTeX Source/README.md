# LaTeX source for the revised article

This folder contains the manuscript source, bibliography, journal class and styles, figures, and the marked revision source. All image assets are kept beside the `.tex` files so their relative paths resolve.

Compile the final article from this folder with:

```sh
latexmk -pdf -interaction=nonstopmode Paper.tex
```

Compile the highlighted version with:

```sh
latexmk -pdf -interaction=nonstopmode Manuscript_Highlighted_Latest.tex
```

`results_compact.tex` supplies the compact results tables and charts. `sn-bibliography.bib` contains references. The included `.bbl` files allow the highlighted manuscript to reuse the final bibliography when compiling independently.
