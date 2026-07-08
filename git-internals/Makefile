.PHONY: .slides.html

slides.html:
	pandoc \
		--filter pandoc-codeblock-include \
		-t revealjs \
		-s presentation/slides.md \
		-o .slides.html \
        --syntax-highlighting zenburn \
		-V revealjs-url=https://unpkg.com/reveal.js@^4/ \
		-V theme=black \
		--css black-root.css \
