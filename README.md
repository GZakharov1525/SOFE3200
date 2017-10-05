# SOFE3200
Repository holds the contents of Labs for SOFE3200 any other code snippets that might be written or wrote during the course of the course.

## How to build and run the files

Make sure you have gcc installed `gcc --version`

### Install cmake-build system from a PPA(Ubuntu/Debian/Linux Mint).

``` shell
sudo apt-get install software-properties-common
sudo add-apt-repository ppa:george-edison55/cmake-3.x
sudo apt-get update
```

and then install cmake like this `sudo apt-get install cmake`

### Building the file with cmake

Make a new directory for build files
`mkdir build`

cd to build like this `cd build`

Generate the buid files like this `cmake ..`

Now that the make file is generated. So build the makefile like this `make`

Now the executable should be generated. So run it like this `./main`

GOOD.

Since we are using Cmake you can also build the programs for other platforms.
