cmake_minimum_required(VERSION 3.31)
project(.)

set(CMAKE_CXX_STANDARD 26)

add_library(library SHARED ../library.cpp)
