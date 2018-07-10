# CPP-FizzBuzz

Simple project for learning programming language in C++

# Preparation
  - Windows
  - Mac
    - `git clone https://github.com/google/googletest.git`
    - `cd googletest`
    - `mkdir build && cd build`
    - `cmake -DCMAKE_BUILD_TYPE=Release ..`
    - `make`
    - `make install`
  - Linux

# Compile & Run
  - go to source code dir
  - Mac
    - `clang++ -I/usr/local/include -L/usr/local/lib -lgtest src/FizzBuzzTest.cc -o build/FizzBuzzTest.out`
    - `./build/FizzBuzzTest.out`
