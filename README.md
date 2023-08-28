# Template for CMake project with GoogleTest

## Basic usage

```bash
mkdir build && cd build
cmake ..
make && make test
```

Template also includes Github Action Workflow that runs the tests. 

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

### Deploying documentation

Template includes GitHub action that deploys buit docs to the repository page. (See `Settings->Pages` for reference).
You can see the docs page here: https://pbudzyns.github.io/cpp_tests_and_docs_template
