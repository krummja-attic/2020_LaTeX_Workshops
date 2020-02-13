# LaTeX Workshops

## Plan

+ Start with messy code that outputs a boring document; the goal will be to end the workshop with clean code and a beautiful document.
+ The idea here is to use the cleaning up of the code as a rhetorical device for digressions into various related topics.

## Topics

- color & fonts
- Math mode
- Labels and Refs!!
- BibTeX and Biber
- using Biber to do a keyworded annotated bib

- LaTeX as workflow
- Emphasize things like tables, figures, diagrams, etc.
- Custom commands
- environments
- Beamer presentations
- Show a "zen mode" workspace with maximally offloaded support files
- Show using Zotero in my workflow!!

- engines




## TeX Engines
- tex : Reads macros defined in `plain.tex` and outputs DVI
- pdftex : Alternative version of tex engine that outputs PDF
- latex : calls pdftex engine reading LaTeX format and outputs DVI
- pdflatex : calls pdftex engine reading LaTeX and outputs PDF
- xetex : extensions to tex allowing unicode and right-to-left typesetting; reads plain tex and outputs to PDF
- xelatex : calls the xetex engine but with LaTeX format; produces PDF output
- luatex : partial implementation of tex engine incorporating lua, PDF output
- lualatex : calls luatex engine reading LaTeXand outputting PDF

## PLAIN TEX
  ``` tex
  Test of plain \TeX.\bye
  ```

## LATEX, PDFLATEX, XELATEX, or LUALATEX
  ``` latex
  \documentclass{article}
  \begin{document}
  Test of \LaTeX.
  \end{document}
  ```

## PDFLATEX (with Unicode)
  ``` latex
  \documentclass{article}
  \usepackage[utf8]{inputenc}
  \usepackage[T1]{fontenc}
  \begin{document}
  Test of \LaTeX with Unicode! Matthäuspassion
  \end{document}
  ```

## XELATEX or LUALATEX (with Unicode)
  ``` latex
  \documentclass{article}
  \usepackage{fontspec}
  \setmainfont{Latin Modern Roman}
  \begin{document}
  Test of \LaTeX with Unicode! Matthäuspassion
  \end{document}
  ```
