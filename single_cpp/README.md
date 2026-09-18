# Hello World: C++ on Linux

## Compile with GCC

For C++, use `g++`, the C++ compiler included with GCC.

```bash
g++ hello.cpp -o hello
./hello
```

Expected output:

```text
Hello, World!
```

## Compile with Make

```bash
make
./hello
```

Remove the compiled program:

```bash
make clean
```

## Compile with CMake

Keep CMake output in a separate `build` directory:

```bash
mkdir build
cd build
cmake ..
cmake --build .
./hello
```
