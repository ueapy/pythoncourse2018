TEX = xelatex
src = poster.tex
out = poster.pdf

$(out) : $(src)
	$(TEX) $(filter-out $<,$^ ) -o $@

.PHONY: clean
clean :
	-rm $(out)
