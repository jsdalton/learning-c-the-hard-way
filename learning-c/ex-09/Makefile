CFLAGS=-Wall -g
program := ex9

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
