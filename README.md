# Template for CMake project with GoogleTest

## Basic usage

```bash
mkdir build && cd build
cmake ..
make && make test
```

## Pre-commit hook

This template contains simple pre-commit hook that runs `clang-format`, `cpplint` and `ctest`.
Each time the checks are run for the entire project, for more advanced functionality switch to [pre-commit tool](https://pre-commit.com).

To enable simply run configure script:

```bash
./configure.sh
```
