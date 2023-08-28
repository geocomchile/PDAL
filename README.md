PDAL
====


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.2616780.svg)](https://doi.org/10.5281/zenodo.2616780)

[![Join the chat at https://gitter.im/PDAL/PDAL](https://badges.gitter.im/PDAL/PDAL.svg)](https://gitter.im/PDAL/PDAL?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## Build Status

[![OSX](https://github.com/PDAL/PDAL/workflows/OSX/badge.svg)](https://github.com/PDAL/PDAL/actions?query=workflow%3AOSX)
[![Linux](https://github.com/PDAL/PDAL/workflows/Linux/badge.svg)](https://github.com/PDAL/PDAL/actions?query=workflow%3ALinux)
[![Windows](https://github.com/PDAL/PDAL/workflows/Windows/badge.svg)](https://github.com/PDAL/PDAL/actions?query=workflow%3AWindows)
[![Docs](https://github.com/PDAL/PDAL/workflows/Docs/badge.svg)](https://github.com/PDAL/PDAL/actions?query=workflow%3ADocs)
[![Conda](https://github.com/PDAL/PDAL/workflows/Conda/badge.svg)](https://github.com/PDAL/PDAL/actions?query=workflow%3AConda)

See https://pdal.io/ for more info


## Steps to compile with rxp and rdbx drivers:

Clone this repo

unzip the rxp and rdb library folder depending on the operating system

set RiVLib_DIR and rdb_DIR enviroment variables to the folder that contains /cmake/rivlib-config.cmake and /interface/cpp/rdb-config.cmake

run:

sudo apt install libgdal-dev

sudo apt install ninja-build

sudo apt install cmake


mkdir build

cd build

cmake -G Ninja ..

if there is not any error run:

ninja

test with:

bin/pdal --drivers







