dhtsearch:dht.o dhtsearch.o
	gcc dhtsearch.o dht.o -o dhtsearch -lcrypt

dht-example.o:dhtsearch.c dht.h
	gcc -c dhtsearch.c -o dhtsearch.o

dht.o:dht.c dht.h
	gcc -c dht.c -o dht.o
	
clean:
	rm -rf *.o dhtsearch
