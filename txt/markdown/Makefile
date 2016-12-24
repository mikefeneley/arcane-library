MARKDOWN = $(wildcard *.md)
HTML = ${MARKDOWN:.md=.html}

all: $(HTML) 

$(HTML): %.html: %.md
	markdown $< >> $@

