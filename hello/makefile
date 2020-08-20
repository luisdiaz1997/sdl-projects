all: main.c
	gcc main.c -o main `pkg-config --cflags --libs sdl2`
run: main
	./main
clean: main
	rm main
