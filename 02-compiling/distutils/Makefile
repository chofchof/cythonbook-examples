all:
	python setup.py build_ext --inplace
	python setup_wrap.py build_ext --inplace

clean:
	-rm -r build fib.{c,*.so} wrap_fib.{c,*.so}
