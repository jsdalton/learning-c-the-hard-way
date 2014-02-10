CFLAGS=-Wall -g
program := ex10

clean:
	rm -f $(program)

debug:
	valgrind --track-origins=yes ./$(program)

all: $(program)
