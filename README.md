[LaTeX for PHYSICAL REVIEW JOURNALS]
\
(Published by the American Physical Society)
\
https://journals.aps.org/
\
\
[latex, revtex4]
\
sudo apt-get install texlive-lang-cjk xdvik-ja latexmk
\
sudo apt install texlive-publishers
\
sudo apt install -y okular
\
\
[aspell]
\
sudo apt install -y aspell
\
$ aspell -l en -c paper.tex
\
\
$ platex paper.tex
\
$ dvipdfmx paper.dvi
