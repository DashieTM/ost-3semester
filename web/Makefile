web.pdf: web.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape web.tex 

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp web.pdf $${HOME}/Documents/OST\ 3.semester/web.pdf
