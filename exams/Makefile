besys.pdf: besys.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape besys.tex comgra.tex phys.tex

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp besys.pdf $${HOME}/Documents/OST\ 3.semester/exams/besys.pdf
	cp comgra.pdf $${HOME}/Documents/OST\ 3.semester/exams/comgra.pdf
	cp phys.pdf $${HOME}/Documents/OST\ 3.semester/exams/phys.pdf
