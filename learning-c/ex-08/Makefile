CFLAGS=-Wall -g
program := ex8

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
