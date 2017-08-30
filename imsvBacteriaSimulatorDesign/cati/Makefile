

cati.pdf: *.tex cati.bib figures/*.pdf
	pdflatex cati
	bibtex cati
	pdflatex cati
	pdflatex cati

%.pdf: %.svg
	../svg2pdf.sh $<
