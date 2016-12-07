Conda recipe to build [`protobuf`][1] Python bindings package.

**Note** Windows build only.

Build
=====

Install `conda-build`:

    conda install conda-build

Build recipe:

    conda build .


Install
=======

The [Windows 32-bit build][2] may be installed from the
[`wheeler-microfluidics`][3] channel using:

    conda install -c wheeler-microfluidics protobuf


[1]: https://github.com/google/protobuf
[2]: https://anaconda.org/wheeler-microfluidics/protobuf
[3]: https://anaconda.org/wheeler-microfluidics
