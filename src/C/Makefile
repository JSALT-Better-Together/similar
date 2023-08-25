files=faster_near_with_floats

all: ${files}

clean: 
	rm ${files}; rm *.o

util.o: util.c util.h
	cc -c util.c

faster_near_with_floats: faster_near_with_floats.c util.o
	cc -o faster_near_with_floats faster_near_with_floats.c util.o -lm

