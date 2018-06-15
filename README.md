Deep C
===

## About the Course
This repository is part of the C engineer course on Udemy [link here].
The course teaches C programming language for beginners with little to no coding experience. 

## About the repository
This repository contains a empty cmake project for future use.

## Setup Your First Project

First of all, grab a copy of this repository

```sh
$ git clone https://github.com/C-Engineer/cmake-skeleton
```

Compile it to test if you have everything setup.

```sh
$ cd cmake-skeleton
$ mkdir build
$ cd build
$ cmake ..
$ make
$ ./skeleton
Hello, world!
```

## Project Structure
- `source` Your `.c` files goes here
- `include` Your `.h` files goes here
- `CMakeLists.txt` CMake project file, each time you add a c file, you need to add it here as well, follow the `main.c` example. `.h` files are not required to be added as long as they are under `include` directory.
