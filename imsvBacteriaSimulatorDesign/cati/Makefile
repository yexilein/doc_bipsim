

cati.pdf: *.tex figures/*.pdf
	pdflatex cati.tex && pdflatex cati.tex

%.pdf: %.svg
	~/svg2pdf.sh $<
