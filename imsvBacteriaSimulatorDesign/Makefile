
simulatorDesign.pdf: simulatorDesign.tex global/*.tex global/figures/*.pdf detailed/*.tex detailed/figures/*.pdf appendix/*.tex
	pdflatex simulatorDesign.tex && pdflatex simulatorDesign.tex

%.pdf: %.svg
	~/svg2pdf.sh $<
