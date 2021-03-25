fibonacci_func.so: fibonacci_func.o
	$(CXX) -shared $^ -o $@ -Wl,--whole-archive -Wl,--no-whole-archive

fibonacci_func.o : CXXFLAGS+=-fPIC
