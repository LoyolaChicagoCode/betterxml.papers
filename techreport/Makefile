all: article

article:
	pdflatex naturalxml.article
	bibtex naturalxml.article
	pdflatex naturalxml.article
	pdflatex naturalxml.article

#slides:
#	pdflatex naturalxml.beamer
#	#bibtex naturalxml.beamer
#	#pdflatex naturalxml.beamer
#	pdflatex naturalxml.beamer

clean:
	-rm *.aux *.log *.nav *.out *.pdf *.snm *.toc *.vrb *.ps *.dvi *.bbl *.blg
	-rm *~