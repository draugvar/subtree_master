# CMakeList.txt : CMake project for Subtree, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("Subtree")

# Add source to this project's executable.
add_executable (Subtree "slaveone/src/nested.cpp" "src/subtree.cpp")

# TODO: Add tests and install targets if needed.
