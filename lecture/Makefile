LATEX=latex --output-format=pdf
BIBTEX=bibtex

slides:
	$(LATEX) lectures
	$(BIBTEX) lectures
	$(LATEX) lectures
	$(LATEX) lectures

sheet:
	$(LATEX) exercises
	$(BIBTEX) exercises
	$(LATEX) exercises
	$(LATEX) exercises

clean:
	-rm -rfv *~ *.log *.aux *.nav *.out *.snm *.toc *.bbl *.blg *.vrb
