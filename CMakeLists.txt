cmake_minimum_required(VERSION 3.3)
project(EX3)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(EX3 ${SOURCE_FILES})