PDF=hyperautomation_systemic_engineering.pdf

all: $(PDF)

$(PDF): main.tex references.bib
	pdflatex -interaction=nonstopmode main.tex
	biber main
	pdflatex -interaction=nonstopmode main.tex
	pdflatex -interaction=nonstopmode main.tex
	cp main.pdf $(PDF)

clean:
	rm -f *.aux *.bbl *.bcf *.blg *.log *.out *.run.xml *.toc main.pdf
