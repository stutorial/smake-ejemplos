all: impresor.o suma.o
	gcc impresor.o suma.o -o ejecutar
	
impresor.o: impresor.c
	gcc -c impresor.c -o $@
	
suma.o: suma.c
	gcc -c suma.c -o $@

clean: ejecutar suma.o impresor.o
	 rm ejecutar suma.o impresor.o