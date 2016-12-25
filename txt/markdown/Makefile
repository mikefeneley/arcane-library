MARKDOWN = $(wildcard *.md)
HTML = ${MARKDOWN:.md=.html}

all: $(HTML) 
	cp *.html ../../pages/content/
$(HTML): %.html: %.md
	markdown $< >> $@

