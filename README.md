# Template for CMake project with GoogleTest

## Basic usage

```bash
mkdir build && cd build
cmake ..
make && make test
```

## Pre-commit hook

This template contains simple pre-commit hook that runs `clang-format`, `cpplint` and `ctest`.

To enable simply run configure script:

```bash
./configure.sh
```

## Building documentation


### Install requirements

```bash
apt install doxygen graphviz
pip install -r requirements.txt
```

### Run build

```bash
cd docs/sphinx && make build-docs
```
