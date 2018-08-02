[![Travis CI Status](https://travis-ci.org/fonttools/skia-pathops.svg?branch=master)](https://travis-ci.org/fonttools/skia-pathops)
[![Appveyor CI Status](https://ci.appveyor.com/api/projects/status/jv7g1e0m0vyopbej?svg=true)](https://ci.appveyor.com/project/fonttools/skia-pathops/branch/master)

Python bindings for the [Google Skia](https://skia.org) library's [Path
Ops](https://skia.org/dev/present/pathops) module, performing boolean
operations on paths (intersection, union, difference, xor).

Build
=====

A recent version of [Cython](https://github.com/cython/cython) is
required to build the package (see the `pyproject.toml` file for
the minimum required version).

For developers we recommend installing in editable mode using
`pip install -e .`, and compiling the extension module in the same
source directory.
