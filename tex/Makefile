main:
	latexmk -g -pdf *.tex

update:
	latexmk -pdf -pvc main.tex

clean:
	rm -f *.blg *.fdb_latexmk *.fls main.log main.bbl  mainNotes.bib *.aux

png:
	convert \
		-density 1000 \
		-quality 100 \
		main.pdf \
		main.png
