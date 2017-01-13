cmake_minimum_required(VERSION 2.8.4 FATAL_ERROR)

SET(sampleName MCBlockFinder)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

project(MCBlockFinder)

set(SOURCE_FILES src/main.cpp)
add_executable(MCBlockFinder ${SOURCE_FILES})