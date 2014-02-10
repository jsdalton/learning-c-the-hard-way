CFLAGS=-Wall -g
program := ex12

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
