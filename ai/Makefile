ai.pdf: ai.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape ai.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp ai.pdf $${HOME}/Documents/OST\ 3.semester/ai.pdf
