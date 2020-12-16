cmake_minimum_required(VERSION 3.17)
project(test1)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(test1
        a.cpp
        b.cpp)
