cmake_minimum_required(VERSION 3.30)
project(testing)

set(CMAKE_CXX_STANDARD 20)

add_executable(testing main.cpp
        cmake-build-debug/Student.cpp
        cmake-build-debug/Student.h)
