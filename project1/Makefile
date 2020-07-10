NAME=proj1

all: do

do: $(NAME).tex
	latex $(NAME).tex
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	-rm -f $(NAME).aux $(NAME).dvi $(NAME).log $(NAME).ps
