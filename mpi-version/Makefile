all: sffwi2d sfmodeling2d

sffwi2d: sffwi2d.c
	gcc -O3 -fopenmp -o sffwi2d sffwi2d.c -I/usr/local/madagascar-1.6.4/include -lm -L/usr/local/madagascar-1.6.4/lib/ -lrsf

sfmodeling2d: sfmodeling2d.c
	gcc -O3 -fopenmp -o sfmodeling2d sfmodeling2d.c -I/usr/local/madagascar-1.6.4/include -lm -L/usr/local/madagascar-1.6.4/lib/ -lrsf

clean:
	rm -f sffwi2d sfmodeling2d
