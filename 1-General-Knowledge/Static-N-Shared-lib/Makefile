
static :
	ar rcs lib/static/libhello.a obj/hellothuy.o obj/helloWorld.o
link:
	gcc obj/main.o -L lib/static -lhello -o bin/exam
all :
	gcc -c main.c -o obj/main.o -I ./inc
	gcc -c src/hellothuy.c -o obj/hellothuy.o -I ./inc
	gcc -c src/helloWorld.c -o obj/helloWorld.o -I ./inc
clean:
	rm -rf obj *bin/*




