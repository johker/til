# How to use latex in Ubuntu

First, install texlive with apt:


```bash
sudo apt install texlive-latex-extra
```

I can create a pdf from a tex file by running


```bash
pdflatex -interaction nonstopmode -halt-on-error -file-line-error <file>.tex
```

