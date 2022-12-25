rust.pdf: rust.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape rust.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp rust.pdf $${HOME}/Documents/OST\ 3.semester/rust.pdf
