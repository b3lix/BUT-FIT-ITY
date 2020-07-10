NAME=proj2

do: $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -t a4 $(NAME).dvi
	pdflatex $(NAME).tex

clean:
	-rm -f $(NAME).aux $(NAME).dvi $(NAME).log $(NAME).ps
