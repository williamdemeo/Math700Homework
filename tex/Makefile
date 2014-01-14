TEX=$(wildcard Homework*.tex)
PDF=$(TEX:.tex=.pdf)

all:${PDF}

${PDF}:%.pdf:%.tex macros.tex
	pdflatex $<

clean:
	rm -rf ${PDF}
