
simulatorDesign.pdf: simulatorDesign.tex global/global.tex global/figures/*.pdf detailed/*.tex 
	pdflatex simulatorDesign.tex && pdflatex simulatorDesign.tex

%.pdf: %.svg
	~/svg2pdf.sh $<
