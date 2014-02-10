CFLAGS=-Wall -g
program := ex6

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
