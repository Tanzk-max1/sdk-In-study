cmake_minimum_required(VERSION 3.27)
project(sdkInstudy)

set(CMAKE_CXX_STANDARD 11)

add_executable(sdkInstudy main.cpp
        examples/buried_example.cpp
        include/buried.h
        src/buried.cpp)
