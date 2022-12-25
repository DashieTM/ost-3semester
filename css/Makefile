css.pdf: css.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape css.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp css.pdf $${HOME}/Documents/OST\ 3.semester/css.pdf
