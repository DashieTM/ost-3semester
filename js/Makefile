js.pdf: js.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape js.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp js.pdf $${HOME}/Documents/OST\ 3.semester/js.pdf
