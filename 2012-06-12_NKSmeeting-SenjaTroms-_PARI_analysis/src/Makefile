presentation.pdf: presentation.tex PARI.tex
	latexmk presentation.tex -pdf #-pdfps #-pvc
open: clean presentation.pdf
	see presentation.pdf

clean:
	rm -f  *.fdb_latexmk *.aux *.toc *.idx *.ind *.ilg *.log *.out *.lof *.lot *.lol *.bbl *.blg *.bak *.dvi *.ps *.nav *.snm thesis.zip  presentation.pdf