#
# Makefile for acmart package
#
# This file is in public domain
#
# $Id: Makefile,v 1.10 2016/04/14 21:55:57 boris Exp $
#

PACKAGE=acmart

SAMPLES = report.tex


PDF = $(PACKAGE).pdf ${SAMPLES:%.tex=%.pdf} acmguide.pdf

all:  ${PDF}


%.pdf:  %.dtx   $(PACKAGE).cls
	pdflatex $<
	- bibtex $*
	pdflatex $<
	- makeindex -s gind.ist -o $*.ind $*.idx
	- makeindex -s gglo.ist -o $*.gls $*.glo
	pdflatex $<
	while ( grep -q '^LaTeX Warning: Label(s) may have changed' $*.log) \
	do pdflatex $<; done


acmguide.pdf: $(PACKAGE).dtx $(PACKAGE).cls
	pdflatex -jobname acmguide $(PACKAGE).dtx
	- bibtex acmguide
	pdflatex -jobname acmguide $(PACKAGE).dtx
	while ( grep -q '^LaTeX Warning: Label(s) may have changed' acmguide.log) \
	do pdflatex -jobname acmguide $(PACKAGE).dtx; done

%.cls:   %.ins %.dtx
	pdflatex $<

%.pdf:  %.tex   $(PACKAGE).cls ACM-Reference-Format.bst
	pdflatex $<
	- bibtex $*
	pdflatex $<
	pdflatex $<
	while ( grep -q '^LaTeX Warning: Label(s) may have changed' $*.log) \
	do pdflatex $<; done

sample-sigconf-xelatex.pdf:  sample-sigconf-xelatex.tex   $(PACKAGE).cls ACM-Reference-Format.bst
	xelatex $<
	- bibtex $*
	xelatex $<
	xelatex $<
	while ( grep -q '^LaTeX Warning: Label(s) may have changed' $*.log) \
	do xelatex $<; done

sample-sigconf.pdf \
sample-sigconf-authordraft.pdf \
sample-sigconf-xelatex.pdf \
sample-sigplan.pdf \
sample-sigchi.pdf: samplebody-conf.tex


.PRECIOUS:  $(PACKAGE).cfg $(PACKAGE).cls


clean:
	$(RM)  *.log *.aux \
	*.cfg *.glo *.idx *.toc \
	*.ilg *.ind *.out *.lof \
	*.lot *.bbl *.blg *.gls *.cut *.hd \
	*.dvi *.ps *.thm *.tgz *.zip *.rpi

distclean: clean
	$(RM) $(PDF) *-converted-to.pdf

#
# Archive for the distribution. Includes typeset documentation
#
archive:  all clean
	COPYFILE_DISABLE=1 tar -C .. -czvf ../$(PACKAGE).tgz --exclude '*~' --exclude '*.tgz' --exclude '*.zip'  --exclude CVS --exclude '.git*' $(PACKAGE); mv ../$(PACKAGE).tgz .

zip:  all clean
	zip -r  $(PACKAGE).zip * -x '*~' -x '*.tgz' -x '*.zip' -x CVS -x 'CVS/*'

documents.zip: all
	zip $@ acmart.pdf acmguide.pdf sample-*.pdf *.cls *.bst
