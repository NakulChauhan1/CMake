# CMake

Getting started Guide:
https://cmake.org/cmake/help/latest/guide/tutorial/index.html




cmake_minimum_required()
project()
add_executable(): command tells CMake to create an executable using the specified source code files.




Steps to BUILD:
1. Navigate to that build directory and run cmake to configure the project and generate a native build system.
cd BUILD;
cmake ../

2. Now call that build system to actually compile/link the project (ie it creates exe):
cmake --build .


 
