.PHONY: clean

simple: main.o foo.o
	gcc main.o foo.o -o simple

main.o: main.c
	gcc main.c -c -o main.o

foo.o: foo.c
	gcc foo.c -c -o foo.o

clean:
	rm  foo.o main.o  simple
