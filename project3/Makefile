NAME=proj3

all: do clean

do: $(NAME).tex
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -t -sPAPERSIZE=a4 $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	-rm -f $(NAME).aux $(NAME).dvi $(NAME).log $(NAME).ps
