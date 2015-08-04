all: impresor.o suma.o
	gcc impresor.o suma.o -o ejecutar
	
impresor.o:
	gcc -c impresor.c
	
suma.o:
	gcc -c suma.c

clean:
	 rm ejecutar suma.o impresor.o