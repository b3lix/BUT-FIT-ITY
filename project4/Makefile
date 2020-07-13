NAME=proj4

do: $(NAME).tex
	pdflatex $(NAME).tex
	bibtex $(NAME)
	pdflatex $(NAME).tex
	pdflatex $(NAME).tex

clean:
	rm -f $(NAME).aux $(NAME).dvi $(NAME).log $(NAME).ps $(NAME).out $(NAME).bbl $(NAME).blg
