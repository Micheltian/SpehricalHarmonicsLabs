﻿# CMakeList.txt : Top-level CMake project file, do global configuration
# and include sub-projects here.
#
cmake_minimum_required (VERSION 3.8)

set(CMAKE_CXX_STANDARD 11)
include_directories(/usr/local/include)
project ("SHTools")

# Include sub-projects.
add_subdirectory ("SHTools")
