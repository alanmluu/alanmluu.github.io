TEX=pdflatex
BIBTEX=bibtex
DOC := CV_AlanLuu
BIB := reference.bib
SRCS := $(wildcard *.tex) $(BIB) $(FIGS) Makefile

ALL := $(DOC).pdf

all :
	$(TEX) $(DOC).tex

figs :
	mkdir -p figs
clean:
	rm -f $(ALL) *.bbl *.blg *.log *.aux *.out *.run.xml
