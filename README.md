PHAS0100Assignment2
------------------

[![Build Status](https://travis-ci.com/[USERNAME]/PHAS0100Assignment2.svg?branch=master)](https://travis-ci.com/[USERNAME]/PHAS0100Assignment2)
[![Build Status](https://ci.appveyor.com/api/projects/status/[APPVEYOR_ID]/branch/master)](https://ci.appveyor.com/project/[USERNAME]/PHAS0100Assignment2)


Purpose
-------

This project serves as a starting point for the PHAS0100 Assignment 2 Gravitational N-body Simulation coursework. It has a reasonable folder structure for [CMake](https://cmake.org/) based projects,
that use [CTest](https://cmake.org/) to run unit tests via [Catch](https://github.com/catchorg/Catch2). 

Further information on the specific project is left as an exercise for the student.


Build Instructions
------------------


Ensure that  a "out-of-source" build is made.

Detailed of "out-of-source" build is shown below:

- mkdir build
- cd build
- cmake ..
- make

Command line Instructions
------------------
After above steps, you can now run the command line app from the build directory and pass the step_size and the number of timesteps. The format should be something as below.

solarSystemSimulator [-s  step_size for the simulation] [-n  number of timesteps]

And instruction should be something as followed:
./bin/solarSystemSimulator -s 0.000274 -n 3650
