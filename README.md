This is a shell script intended to compile LaTeX using latex or
pdflatex. Also the BibTeX file can be specified. If you are using
glossaries there is an option for that!

# Prerequisites #

    * [http://www.ctan.org/pkg/glossaries](glossaries)

This is what I did and where I placed my script:
``` shell
$ mv llatex $HOME/bin
$ cd $HOME/bin
$ chmod u+x llatex
```
The directory $HOME/bin mus be specified in the $PATH.
