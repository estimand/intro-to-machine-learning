
all: intro_machine_learning.pdf

%.pdf: %.tex
	latexmk -pdf -pdflatex="xelatex --shell-escape" -use-make $<

clean:
	latexmk -CA

