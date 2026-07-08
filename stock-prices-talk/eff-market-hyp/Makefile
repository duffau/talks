.PHONY:.slides.html

REVEAL_VERSION = 4.6.1

slides.html:
	pandoc  -t revealjs -s pres/slides.md -o .slides.html --mathjax --highlight-style zenburn -V revealjs-url=https://cdn.jsdelivr.net/npm/reveal.js@$(REVEAL_VERSION)
 -V theme=black
		
