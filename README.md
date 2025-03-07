# ArenaAllocator Library

A custom implementation of an Arena Allocator written in C++.

## Build

Run the following to build the project into the `./build` directory.

```bash
cmake . -B build
cmake --build build
```

Or as a single command.

```bash
cmake . -B build && cmake --build build
```

## Install

Run the following command chaning `<INSTALL_DIR>` to the directory of the project you want to use the library in. The project needs to be built before you can install it, see [BUILD](##Build).

```bash
cmake --install build --prefix <INSTALL_DIR>
```

## References
- [orosmatthew's custom arena allocator](https://github.com/orosmatthew/hydrogen-cpp/blob/master/src/arena.hpp)
