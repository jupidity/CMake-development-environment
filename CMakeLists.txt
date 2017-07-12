# CMake for C++ devel
# Sean Cassero 3/20/17

# CMakeLists files in this project can
# refer to the root source directory of the project as ${HELLO_SOURCE_DIR} and
# to the root binary directory of the project as ${HELLO_BINARY_DIR}.
cmake_minimum_required (VERSION 2.8.11)
# provide a name for your project. Here I have called it message, since the 
# library in the src directory passes a message to std out
project (main)



# specify where the source files will be 
add_subdirectory (src)
