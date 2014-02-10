CFLAGS=-Wall -g
program := ex7

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
