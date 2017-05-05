all: sffwi2d sfmodeling2d

sffwi2d: sffwi2d.c
	gcc -O3 -fopenmp -o sffwi2d sffwi2d.c -I/usr/local/madagascar/include -lm -L/usr/local/madagascar/lib/ -lrsf

sfmodeling2d: sfmodeling2d.c
	gcc -O3 -fopenmp -o sfmodeling2d sfmodeling2d.c -I/usr/local/madagascar/include -lm -L/usr/local/madagascar/lib/ -lrsf

clean:
	rm -f sffwi2d sfmodeling2d
