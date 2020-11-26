# UI PhD Study Plan Template

This is a study plan template for the School of Engineering and Natural Sciences at the University of Iceland.

## Instructions

- Largely self-explanatory
  - Change names and add things
- Keep track of the bibliography and the names
- Needs the Calibri font
  - This involves, say, on ArchLinux, the `ttf-windows` AUR package
- Also needs the logo, _do not_ delete `logo`

## Compilation

Locally this needs `xelatex`.

```{bash}
latexmk -pdfxe -shell-escape -8bit -pvc studyPlanSENS.tex
```

## Overleaf

This repository has also been submitted to Overleaf for use as a template.

## License

- The logo (in the header) is reserved for use by the University of Iceland
- The rest of the content is junk
- The template itself (code) is MIT licensed
