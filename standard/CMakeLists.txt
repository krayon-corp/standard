# CMakeList.txt : CMake project for c++, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

# Add source to this project's executable.
add_library(KrayonStandard SHARED "krayon_standard.cpp" "krayon_standard.h")

# TODO: Add tests and install targets if needed.
