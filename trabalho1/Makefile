all: main.o registro.o
	gcc main.o registro.o -o main -lm

main.o: main.c registro.h
	gcc -c main.c -o main.o

registro.o: registro.c registro.h
	gcc -c registro.c -o registro.o

run:main
	./main 3 'nomeEscola' 'EE CANDIDA ALVARENGA MENDONCA'

clean:
	rm -rf *o main
