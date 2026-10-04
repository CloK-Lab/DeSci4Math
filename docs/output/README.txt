CURRENT DOCUMENT EXPORTS

pdf/verification_market_ecosystem.pdf
  Current Ecosystem document, compiled from verification_market_ecosystem.tex.

pdf/verification_market_summary.pdf
  Current three-page summary, compiled from verification_market_summary.tex.

From the docs directory, refresh the PDFs with:
  latexmk -pdf -no-shell-escape -interaction=nonstopmode -halt-on-error -outdir=output/pdf verification_market_ecosystem.tex
  latexmk -pdf -no-shell-escape -interaction=nonstopmode -halt-on-error -outdir=output/pdf verification_market_summary.tex

Compilation auxiliaries are ignored by Git. Check both PDFs after rebuilding.
Refresh both exports when the documentation changes.
