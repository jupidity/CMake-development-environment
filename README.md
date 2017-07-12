## Overview
---

a simple development environment for `C/C++` using `CMake` to glob custom libraries and and code in a `src` directory to generate an executable. 

## Setup
---
clone the repo:

    git clone https://github.com/jupidity/CMake-development-environment.git

create a build folder

    $ mkdir build
    $ cd build

From here, you can run `cmake` on the `src` directory

    $ cmake ../src

A makefile should have been generated in the build directory, along with other CMake files. Create and executable by running `make`

    $ make

the executable `main` should now be in the `/build` directory. You can run it using the shell `./` command

    $ ./main


if executed correctly, the terminal should print the message :

    "happy first day of the lunar cycle, cool kids!"

## Usage
---


  * main code is written in `main.cpp`

  * custom libraries ``.h`` and ``.cpp`` files are written in the `src` directory  

* debugging can be performed using `gdb`
