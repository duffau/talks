.PHONY:.slides.html

REVEAL_VERSION = 4.6.1

slides.html:
	pandoc  -t revealjs -s slides.md -o .slides.html --highlight-style zenburn --incremental -V revealjs-url=https://cdn.jsdelivr.net/npm/reveal.js@$(REVEAL_VERSION) -V theme=black -V  transition="linear"
		
