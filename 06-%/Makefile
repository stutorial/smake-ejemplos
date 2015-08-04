all: impresor.o suma.o
	gcc impresor.o suma.o -o ejecutar
	
%.o: %.c
	gcc -c $^ -o $@

clean: ejecutar suma.o impresor.o
	 rm ejecutar suma.o impresor.o