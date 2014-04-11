all:
	latex numeroPi.tex
	latex numeroPi.tex
	bibtex numeroPi
	latex numeroPi.tex
	latex numeroPi.tex
	dvips -o numeroPi.ps numeroPi.dvi
	ps2pdf -sPAPERSIZE=a4 -DMaxSubsetPct=100 -dCompatibilityLevel=1.2 -dSubsetFonts=true -dEmbedAllFonts=true memte.ps memte.pdf

clean:
	rm -f *.toc *.ps *.log *.lof *.lot *.dvi *.aux *.blg *.bbl *.*~
