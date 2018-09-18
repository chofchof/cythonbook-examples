all:
	cython fib.pyx
	gcc -c fib.c -fPIC $(shell python-config --includes)
	gcc fib.o -o fib.so -shared

clean:
	-rm -r fib.{c,so}
