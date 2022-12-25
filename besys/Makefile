besys.pdf: besys.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape besys.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp besys.pdf $${HOME}/Documents/OST\ 3.semester/besys.pdf
