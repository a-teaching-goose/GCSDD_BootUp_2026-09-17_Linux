# Hello World: Multiple C++ Files

This project separates the greeting from `main`.

- `main.cpp` calls `greeting()` and prints its returned text.
- `greeting.cpp` defines `greeting()`.
- `greeting.h` declares the function so both C++ files agree on it.

## Ubuntu Linux setup

On Ubuntu, install the C++ compiler and `make` once:

```bash
sudo apt update
sudo apt install build-essential
```

`build-essential` installs `g++`, `make`, and common C/C++ build tools.

## Compile without a Makefile

```bash
g++ main.cpp greeting.cpp -o hello
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
