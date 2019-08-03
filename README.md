## Adobe's C++ Performance Benchmarks for modern compilers (and build systems)

Imported and cleaned up from http://stlab.adobe.com/performance/.

### Overview

This is a updated version of Adobe STL Labs' C++ Performance Benchmark.
The code has mostly been left untouched, the main goal of this version is to provide a simple CMake
build so that it can be run on any modern toolchain.

The original readme that includes the creator's intent can still be found under `docs/`.

### Build & run

Simply build it like any CMake project and run all tests through `ctest -V`.

### Credits

Original work by Chris Cox and Adobe STL Labs: http://stlab.adobe.com/performance/credits.html.

### License

This project is licensed under the MIT License.