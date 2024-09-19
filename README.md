# Sam's curriculum vitae LaTeX source

![LaTeX build](../../workflows/LaTeX%20build/badge.svg) [![Latest build of
SamuelCHoover.pdf](https://img.shields.io/badge/SamuelCHoover.pdf-latest-orange.svg?style=flat)](../gh-action-result/pdflatex/SamuelChoover.pdf)

Fork of a [LaTeX CV template](https://github.com/duetosymmetry/cv) from [Leo C.
Stein](https://github.com/duetosymmetry). See his repo for more details and
configurations as I have removed many (I'm not a tenured professor like him!)
sections to fit my needs.

Please feel free to clone this repo if you like the style and want to use it
for your CV.  If you're going to customize it, you need to know the layout of
the contents:

- [SamuelCHoover.tex](SamuelCHoover.tex): The top-level file. Compiling this
gives the full CV. However the sources for list of publications, list of talks,
and contact info are in other files (listed below).

The following files are included by the above (they can not be compiled by
themselves):

- [ContactContent.tex](ContactContent.tex): Contains the contact info header
with email address, web site, and LinkedIn
- [PubsContent.tex](PubsContent.tex): Contains list of publications,
- [TalksContent.tex](TalksContent.tex): Contains list of talks.
