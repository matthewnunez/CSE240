cmake_minimum_required(VERSION 3.6)
project(hw03)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES hw03.c)
add_executable(hw03 ${SOURCE_FILES})