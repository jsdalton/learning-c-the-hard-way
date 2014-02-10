CFLAGS=-Wall -g
program := ex13

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
