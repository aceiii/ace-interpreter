

main: src/main.c src/common.h src/chunk.c src/chunk.h src/memory.c src/memory.h src/debug.c src/debug.h src/value.c src/value.h src/vm.c src/vm.h src/compiler.c src/compiler.h src/scanner.c src/scanner.h src/object.c src/object.h src/table.c src/table.h
	${CC} src/main.c src/chunk.c src/memory.c src/debug.c src/value.c src/vm.c src/compiler.c src/scanner.c src/object.c src/table.c -o main

run: main
	./main

clean:
	rm main

test: main input/test.lox
	./main input/test.lox
