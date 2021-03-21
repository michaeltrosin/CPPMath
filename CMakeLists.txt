cmake_minimum_required(VERSION 3.17)
project(Math)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
set(CMAKE_EXE_LINKER_FLAGS " -static")

add_library(Math
        math/mathf.h
        math/mathf.cpp
        math/color.h
        math/color.cpp
        )
