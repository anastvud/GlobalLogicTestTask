cmake_minimum_required(VERSION 3.21)
project(GlobalLogicTestTask)

set(CMAKE_CXX_STANDARD 17)

set(SOURCE_FILES main.cpp)
add_library(GlobalLogicTestTask ${SOURCE_FILES})
