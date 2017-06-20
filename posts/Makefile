HTML_FILES = $(patsubst %.asciidoc,%.html,$(wildcard *.asciidoc))
OUTPUT_DIR=../

%.html: %.asciidoc
	asciidoc --backend=html5 --out-file=$(OUTPUT_DIR)/$@ $<

all: $(HTML_FILES)

clean:
	rm output/*
