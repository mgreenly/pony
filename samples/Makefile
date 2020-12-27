.DEFAULT_GOAL := all

all: $(wildcard */)
	ponyc --output=$< $<

.PHONY: clean
clean:
	find . -maxdepth 2 -type f -executable -exec rm {} +
