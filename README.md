# pom++
## Summary
This is a C++ pommerman port. It is **incompatible with PyPommerman**. 
It is a header-only library, and written with C++11 in mind however may work with legacy versions.

*Note:*  
Program only works when build for `x64`. If build for `Win32` it has problems with the random number generator and `std::cin.get()`.

## Structure
* main.cpp: This holds example code for a basic environment
* include/pommerman: The directory holding the code for the project 
## Incomplete Features
* Translation layer b/w pom++ and PyPommerman
* Partial Observations
* Radio