all: impresor.o suma.o
	gcc impresor.o suma.o -o ejecutar
	
impresor.o: impresor.c
	gcc -c impresor.c
	
suma.o: suma.c
	gcc -c suma.c

clean:
	 rm ejecutar suma.o impresor.o