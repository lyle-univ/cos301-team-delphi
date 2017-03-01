#pdflatex is called twice to generate table of content
pdf: images
	pdflatex main.tex;
	pdflatex main.tex;

images:
	java -jar Umlet/umlet.jar -action=convert -format=pdf -filename=diagrams/layered_architecture.uxf -output=diagrams/layered_architecture.pdf;

clean:
	rm main.aux main.log main.out main.pdf main.toc
