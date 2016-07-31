========
cv_algorithms
========

A Python package (Python3 ready!) that contains implementations of various OpenCV algorithms are are not
available in OpenCV or OpenCV-contrib. This package is intended to be used with OpenCV 3 (i.e. the `cv2` module).

Most implementations are written in optimized C code. The C code is accessed using [cffi](https://cffi.readthedocs.io/en/latest/).

Currently implemented: 
 
 - Guo-Hall thinning

As `cv2` represents images as `numpy` arrays, most algorithms generically work with numpy arrays.

Installation
============

Contributions
============

Contributions of any shape or form are welcome. Please submit a pull request.

Copyright (c) 2016 Uli Köhler <ukoehler@techoverflow.net>