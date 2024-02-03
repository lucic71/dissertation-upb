# Debian dependencies:
#   * texlive-latex-base
#   * texlive-latex-extra
#   * texlive-science
#   * inkscape

PROJECT=main
PDFLATEX=pdflatex --shell-escape

build:
	${PDFLATEX} ${PROJECT}.tex
	${PDFLATEX} ${PROJECT}.tex
	${PDFLATEX} ${PROJECT}.tex

show:
	evince ${PROJECT}.pdf

clean:
	rm -f *.aux *.blg *.out *.bbl *.log *.toc *.pdf *.nav *.vrb *.snm
