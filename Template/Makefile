TEX=thesis
Chapter=chapter

all:
	 latex ${TEX}
	 bibtex ${TEX}
	 latex ${TEX}
	 latex ${TEX}
	 dvipdfmx ${TEX}
#	 pdftohtml ${TEX}.pdf



read:
	elinks ${TEX}.html
#	evince ${TEX}.pdf &

readpdf:
#	mupdf ${TEX}.pdf
	atril ${TEX}.pdf &

commit:
	git commit -ae && git push

sync:
	cd  /run/media/freeman/Abundant/git/h/thesis.git && git push

cleanPDF:
	rm -f ${TEX}.pdf
    
clean:
	 rm -f ${TEX}.aux
	 rm -f ${TEX}.bbl
	 rm -f ${TEX}.blg
	 rm -f ${TEX}.dvi
	 rm -f ${TEX}.lof
	 rm -f ${TEX}.lot
	 rm -f ${TEX}.toc
	 rm -f ${TEX}.log
	 rm -f ${TEX}.out
	 rm -f ${TEX}.pdf
	 rm -f ./content/${Chapter}1.tex.aux
	 rm -f ./content/${Chapter}2.tex.aux
	 rm -f ./content/${Chapter}3.tex.aux
	 rm -f ${TEX}.html
	 rm -f ${TEX}_ind.html
	 rm -f ${TEX}s.html
	 rm -f ./*.png
	 rm -f ./*.jpg

