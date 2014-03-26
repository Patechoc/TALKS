default: slides.pdf

open: slides.pdf
	open slides.pdf &

slides.pdf: slides.tex syntheticBiology.tex uio.pdf
	pdflatex slides.tex

clean:
	touch uio.pdf && rm *.aux *.log *.dvi *.ps *.blg *.lof *.toc *.lot *.bbl *.bmt *.mtc* *.maf *.ps *.fig.bak *.M* *.ptc* *.nav *.snm *.out
