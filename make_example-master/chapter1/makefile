#this is a makefile example

depen=main.o testa testb clean

main:$(depen)
	gcc -o main main.o

main.o:main.c
	gcc -c main.c

testa:
	touch testa

testb:
	touch testb

clean:
	rm testa testb main.o

clean:
	-rm $(depen)