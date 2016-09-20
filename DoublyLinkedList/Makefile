CC = g++ 
DFLAGS = -std=c++14

all: main

clean:
	rm -f * .o

DoublyLinkedList.o: DoublyLinkedList.cpp
	$(CC) $(DFLAGS) -c -o $@ $<

main: DoublyLinkedList.o
	$(CC) $(DFLAGS) Main.cpp DoublyLinkedList.o
