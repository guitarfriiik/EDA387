CC = g++
CFLAGS = -Wall -Wextra -g3 

all: client-multi.out client-simple.out server-iterative.out

client-multi.out: client-multi.cpp
	$(CC) $(CFLAGS) -o $@ $^

client-simple.out: client-simple.cpp
	$(CC) $(CFLAGS) -o $@ $^

server-iterative.out: server-iterative.cpp
	$(CC) $(CFLAGS) -o $@ $^
clean:
	rm client-multi.out client-simple.out server-iterative.out
