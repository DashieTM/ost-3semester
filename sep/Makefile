SE-Pracice.pdf: uml.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape uml.tex nix.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp uml.pdf $${HOME}/Documents/OST\ 3.semester/uml.pdf
	cp nix.pdf $${HOME}/Documents/OST\ 3.semester/nix.pdf
