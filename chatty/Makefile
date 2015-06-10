.PHONY: default

NAME    := paper
LHS2TEX := lhs2TeX
LATEXMK := latexmk

default : $(NAME).pdf

%.tex : %.lhs %.fmt
	$(LHS2TEX) --poly $< > $@

#	$(LHS2TEX) --agda $< > $@

%.pdf : %.tex %.bib
	$(LATEXMK) -pdf $<

paper.tex :: code/Monoid.lhs code/Functor.lhs

clean:
	latexmk -C $(NAME).tex
