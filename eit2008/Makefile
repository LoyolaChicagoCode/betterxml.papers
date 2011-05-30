all: article

article:
	pdflatex betterxml
	bibtex betterxml
	pdflatex betterxml
	pdflatex betterxml

clean:
	-rm *.aux *.log *.nav *.out *.pdf *.snm *.toc *.vrb *.ps *.dvi *.bbl *.blg
	-rm *~