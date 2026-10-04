# DeSci-Market Documentation

- [Ecosystem](verification_market_ecosystem.tex) · [PDF](output/pdf/verification_market_ecosystem.pdf)
- [Summary](verification_market_summary.tex) · [PDF](output/pdf/verification_market_summary.pdf)
- [Editable ecosystem map](figures/ecosystem_map.excalidraw)
- [Overleaf editor](https://www.overleaf.com/project/6ab6baa74349edae79fa13fc)

These documents record the project's evolving ideas and observations. The
current LaTeX files each contain their figure and bibliography and compile
independently. Editable figures are in `figures/`; PDF exports are in `output/pdf/`.

With a TeX installation and `latexmk`, run these commands from this directory:

```sh
latexmk -pdf -no-shell-escape -interaction=nonstopmode -halt-on-error -outdir=output/pdf verification_market_ecosystem.tex
latexmk -pdf -no-shell-escape -interaction=nonstopmode -halt-on-error -outdir=output/pdf verification_market_summary.tex
```

Compilation auxiliaries are ignored by Git. Review both PDF exports after
changing the sources, including the diagram and the Summary's layout.

Overleaf stores the contents of this directory at its project root. Keep the
two sources, their PDF exports, and supporting figures in sync. Background
collections in local `references/` and `resources/` directories are excluded
from the GitHub repository.
