.PHONY: all
all: games-notes.pdf games-slides.pdf

SRC=		games-preamble.tex games.bib
SRC+=		abstract.tex games-content.tex
SRC+=		libbib.sty crypto.bib

games-notes.pdf: llncs biblatex-lncs
games-notes.pdf: games-notes.tex ${SRC}

games-slides.pdf: games-slides.tex ${SRC}


INCLUDE_MAKEFILES=../makefiles
include ${INCLUDE_MAKEFILES}/tex.mk
INCLUDE_LIBBIB=../libbib
include ${INCLUDE_LIBBIB}/libbib.mk
