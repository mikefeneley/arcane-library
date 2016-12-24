MARKDOWN = $(wildcard *.md)
HTML = ${MARKDOWN:.md=.html}

all: $(HTML) 
	mv *.html ../../pages/content/
$(HTML): %.html: %.md
	markdown $< >> $@

