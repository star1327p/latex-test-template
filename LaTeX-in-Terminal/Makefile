# Provide the filename without any extensions
FILENAME = test_latex_nested

commands:

	# Primary commands to compile .tex into PDF
	pdflatex $(FILENAME).tex
	bibtex $(FILENAME)
	pdflatex $(FILENAME).tex
	pdflatex $(FILENAME).tex
	
	# Automatically clean up auxiliary files
	rm -f *.aux *.log *.toc *.blg *.bbl *.synctex.gz

