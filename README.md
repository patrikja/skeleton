# Skeleton for papers using LaTeX and lhs2TeX
A paper skeleton for writing a research paper with embedded Haskell code.

Dependencies:
* a LaTeX system (TeX Live 2015)
* latexmk
** http://users.phys.psu.edu/~collins/software/latexmk-jcc/
* lhs2TeX
** http://www.andres-loeh.de/lhs2tex/

## Ubutu install script

``` Shell
sudo apt-get install texlive-latex-extra
sudo apt-get install texlive-fonts-recommended
sudo apt-get install texlive-math-extra
sudo apt-get install latexmk
sudo apt-get install lhs2TeX
```

With a Haskell system already in place the last line can be replaced by

``` Shell
cabal install lhs2TeX
```

which is the [recommended way to install lhs2TeX](http://www.andres-loeh.de/lhs2tex/).
