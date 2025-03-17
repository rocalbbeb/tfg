DOC := memoria.tex  

all: memoria.pdf  

memoria.pdf: $(DOC)  
	pdflatex $<  
	bibtex $(basename $<)  
	pdflatex $<  
	pdflatex $<
