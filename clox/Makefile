

main: src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c
	${CC} src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c -o main

run: main
	./main

clean:
	rm main

