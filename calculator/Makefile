CC = gcc

source_files = main.c addition.c subtraction.c multiplication.c division.c

object_files = $(source_files:.c=.o)

all:calculator

calculator: $(object_files)
	gcc -o $@ $^

clean:
	rm -f $(object_files) calculator
