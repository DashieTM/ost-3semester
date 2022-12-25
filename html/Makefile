html.pdf: html.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape html.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp html.pdf $${HOME}/Documents/OST\ 3.semester/html.pdf
