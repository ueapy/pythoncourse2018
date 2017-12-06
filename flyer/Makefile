TEX = xelatex
src = flyer.tex
out = flyer.pdf

all : $(src)
	$(TEX) $(src) -o $(out)

.PHONY: clean
clean :
	-rm $(out)
	-rm *.log *.out *.aux
