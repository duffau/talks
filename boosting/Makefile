.PHONY: .slides.html sim

REVEAL_VERSION = 4.6.1

reveal_flags = --mathjax \
		--syntax-highlighting zenburn \
		--slide-level 3 \
		-V revealjs-url=https://unpkg.com/reveal.js@$(REVEAL_VERSION) \
		-V theme=black \
		-V transition="linear" \
		-V slideNumber="'c/t'" \
		--css ./black-root.css \
		--bibliography ./bibliography.bib \
		--citeproc

sim:
	cd ./simulation; ./run.sh

slides.html:
	pandoc -t revealjs \
	  	-s slides.md \
		-o .slides.html \
		$(reveal_flags)
