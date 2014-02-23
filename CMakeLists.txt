cmake_minimum_required (VERSION 2.6)
project (program)

set (CMAKE_CXX_FLAGS "-std=c++0x")
set (EXTRA_LIBS )

add_executable (program main.cpp)
target_link_libraries (program ${EXTRA_LIBS})
