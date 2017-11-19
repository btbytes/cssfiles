all: aal.html normalize.html sinorcaish-lite.html sinorcaish-screen.html sinorcaish.html

aal.html: sample.md
	pandoc $< -o $@ --standalone --css=../aal.css

normalize.html: sample.md
	pandoc $< -o $@ --standalone --css=../normalize.css

sinorcaish-lite.html: sample.md
	pandoc $< -o $@ --standalone --css=../sinorcaish-lite.css

sinorcaish-screen.html: sample.md
	pandoc $< -o $@ --standalone --css=../sinorcaish-screen.css

sinorcaish.html: sample.md
	pandoc $< -o $@ --standalone --css=../sinorcaish.css

.PHONY:
clean:
	rm -f aal.html
	rm -f normalize.html
	rm -f sinorcaish.html
	rm -f sinorcaish-lite.html
	rm -f sinorcaish-screen.html
