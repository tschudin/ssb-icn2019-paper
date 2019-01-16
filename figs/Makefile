# figs/Makefile

all: about-ds.pdf

about-ds.pdf: about-ds.dot
	dot -Teps about-ds.dot >about-ds.eps
	epstopdf about-ds.eps
	rm -f about-ds.eps

# eof
