# Makefile

all: main.pdf

main.pdf: main.tex main.bib Makefile
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main

clean:
	rm -rf *~ *.log *.aux *.blg *.bbl

# eof
