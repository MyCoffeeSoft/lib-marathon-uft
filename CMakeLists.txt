cmake_minimum_required(VERSION 3.2)
project(lib_mycoffeesoft)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(lib_mycoffeesoft ${SOURCE_FILES})