Project-Management.pdf: prom.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape prom.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp prom.pdf $${HOME}/Documents/OST\ 3.semester/Project-Management.pdf
