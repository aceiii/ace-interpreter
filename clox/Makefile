

main: src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c src/compiler.c src/scanner.c src/object.c
	${CC} src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c src/compiler.c src/scanner.c src/object.c -o main

run: main
	./main

clean:
	rm main

