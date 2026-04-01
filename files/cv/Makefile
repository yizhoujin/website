PDF = cv_yjin.pdf

all: $(PDF)

$(PDF): main.tex cv_academia.tex
	pdflatex -jobname cv_yjin main.tex
	pdflatex -jobname cv_yjin main.tex

clean:
	rm -f cv_yjin.aux cv_yjin.log cv_yjin.out

.PHONY: all clean
