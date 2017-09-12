
simulatorDesign.pdf: simulatorDesign.tex simulatorDesign.bib global/*.tex global/figures/*.pdf detailed/*.tex detailed/figures/*.pdf appendix/*.tex appendix/figures/*.pdf principles/*.tex algorithm/*.tex algorithm/figures/*.pdf
	pdflatex simulatorDesign
	bibtex simulatorDesign
	pdflatex simulatorDesign
	pdflatex simulatorDesign

%.pdf: %.svg
	./svg2pdf.sh $<
