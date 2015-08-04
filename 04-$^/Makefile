all: impresor.o suma.o
	gcc $^ -o ejecutar
	
impresor.o: impresor.c
	gcc -c $^
	
suma.o: suma.c
	gcc -c $^

clean: ejecutar suma.o impresor.o
	 rm $^