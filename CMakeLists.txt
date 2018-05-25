cmake_minimum_required(VERSION 3.10)
project(ingeniaWrapper)

set(CMAKE_CXX_STANDARD 11)

add_library(ingeniaWrapper SHARED library.cpp library.h)