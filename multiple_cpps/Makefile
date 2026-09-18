CXX = g++
CXXFLAGS = -Wall -Wextra -std=c++17

hello: main.cpp greeting.cpp greeting.h
	$(CXX) $(CXXFLAGS) main.cpp greeting.cpp -o hello

clean:
	rm -f hello

.PHONY: clean
