LATEX	= pdflatex
BIBTEX	= bibtex

TARGET	= report

.PHONY: all clean

all: $(TARGET).pdf

$(TARGET).pdf: *.tex
	$(LATEX)	$(TARGET)
	$(LATEX)	$(TARGET)

clean:
	$(RM) $(addprefix $(TARGET)., aux ent log out pdf)
