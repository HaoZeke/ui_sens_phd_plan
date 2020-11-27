# UI PhD Study Plan Template

This is a study plan template for the [School of Engineering and Natural Sciences at the University of Iceland](https://english.hi.is/school_of_engineering_and_natural_sciences).

## Instructions

- Largely self-explanatory
  - Change names and add things
- Keep track of the bibliography and the names
- Also needs the logo, _do not_ delete `logo`

## Compilation

Locally this needs `xelatex`.

```{bash}
latexmk -pdfxe -shell-escape -8bit -pvc studyPlanSENS.tex
```

## Overleaf

This repository has also been [submitted to Overleaf for use as a template](https://www.overleaf.com/latex/templates/ui-sens-phd-study-plan/xqnwgtyfjhnt).

## Acknowledgements

The Calibri font has been kanged from the sources of ArchLinux's `ttf-windows` [AUR package](https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=ttf-windows).

## License

- The logo (in the header) is reserved for use by the University of Iceland
- The rest of the content is junk
- The template itself (code) is MIT licensed
