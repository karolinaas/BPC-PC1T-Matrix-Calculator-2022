﻿# CMakeList.txt : CMake project for MaticovaKalkulacka, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("MaticovaKalkulacka")

# Add source to this project's executable.
add_executable (MaticovaKalkulacka "MaticovaKalkulacka.cpp" "MaticovaKalkulacka.h" "input.h" "input.cpp" "operations.h" "operations.cpp")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET MaticovaKalkulacka PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
