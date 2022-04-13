PHAS0100Assignment2
------------------

[![Build Status](https://travis-ci.com/[USERNAME]/PHAS0100Assignment2.svg?branch=master)](https://travis-ci.com/[USERNAME]/PHAS0100Assignment2)
[![Build Status](https://ci.appveyor.com/api/projects/status/[APPVEYOR_ID]/branch/master)](https://ci.appveyor.com/project/[USERNAME]/PHAS0100Assignment2)


Purpose
-------

This project serves as a starting point for the PHAS0100 Assignment 2 Gravitational N-body Simulation coursework. It has a reasonable folder structure for [CMake](https://cmake.org/) based projects,
that use [CTest](https://cmake.org/) to run unit tests via [Catch](https://github.com/catchorg/Catch2). 

Further information on the specific project is left as an exercise for the student.


Credits
-------

This project is maintained by [Dr. Jim Dobson](https://www.ucl.ac.uk/physics-astronomy/people/dr-jim-dobson). It is based on [CMakeCatch2](https://github.com/UCL/CMakeCatch2.git) that was originally developed as a teaching aid for UCL's ["Research Computing with C++"](http://rits.github-pages.ucl.ac.uk/research-computing-with-cpp/)
course developed by [Dr. James Hetherington](http://www.ucl.ac.uk/research-it-services/people/james)
and [Dr. Matt Clarkson](https://iris.ucl.ac.uk/iris/browse/profile?upi=MJCLA42).


Build Instructions
------------------

Ensure that  a "out-of-source" build is made.

Detailed of "out-of-source" build is shown below:

- mkdir build
- cd build
- cmake ..
- make

Command line Instructions
-------------------------

After above steps, you can now run the command line app from the build directory and pass the step_size and the number of timesteps. The format should be something as below:

**solarSystemSimulator [-s  step_size for the simulation] [-n  number of timesteps]**

And instruction should be something as followed:

**./bin/solarSystemSimulator -s 0.000274 -n 3650**

Unit test Instructions
-------------------------

Instructions for unit test: 
**./bin/nbsimUnitTest**

Results
-------

Screengrab: There is a screenshot called **Screengrap** in the package for question 3f.

**Benchmark**

A. Simulate 100 years of time with various step sizes:

|**step_size**|**kTotal**|**pTotal**|**eTotal**|**CPU time**|**Wall clock time**|
| :----: | :----: | :----: | :----: | :----: | :----: | 
| 0.1day  | 0.18736 | -0.0808182 | 0.106541 | |   ||   |
| 1day    | 0..187374 | -0.00874004 | 0.178634 ||   ||   |



