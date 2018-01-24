# PyCurious

Magnetic data is one of the most common geophysics datasets available on the surface of the Earth. The Curie depth is most often interpreted to be the Curie point of magnetite, because it is the most magnetic mineral, thus Curie depth offers a very desirable isotherm in the lower crust. This is useful for many applications that require constraints on lithospheric geotherms.

## Dependencies

- Python 2.7 and above
- Numpy 1.9 and above
- Scipy 0.14 and above
- Cython

## Installation

To install:

`python setup.py install --user`

This will compile all C and Fortran sources and install them to the user directory (omit the `--user` flag to install to the system directory).

Remember to delete the `build` directory if you are upgrading this package.