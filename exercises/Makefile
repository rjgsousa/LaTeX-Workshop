LATEX=latex --output-format=pdf
BIBTEX=bibtex


sheet:
	$(LATEX) class
	$(BIBTEX) class
	$(LATEX) class
	$(LATEX) class

clean:
	-rm -rfv *~ *.log *.aux *.nav *.out *.snm *.toc *.bbl *.blg *.vrb
