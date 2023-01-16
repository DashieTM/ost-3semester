cpp.pdf: cpp.tex ../ost-summary-template.tex
	latexmk -pdf -shell-escape cpp.tex --extra-mem-bot=10000000 --extra-mem-top=10000000

clean:
	(rm -f *.aux *.fdb_latexmk *.fls *.log *.out *.synctex.gz *.xdv);\

move: 
	cp cpp.pdf $${HOME}/Documents/OST\ 3.semester/cpp.pdf
