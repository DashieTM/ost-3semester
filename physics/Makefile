Physics.pdf: physics.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape physics.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp physics.pdf $${HOME}/Documents/OST\ 3.semester/physics.pdf
