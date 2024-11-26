

main: src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c src/compiler.c src/scanner.c src/object.c src/table.c
	${CC} src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c src/compiler.c src/scanner.c src/object.c src/table.c -o main

run: main
	./main

clean:
	rm main

