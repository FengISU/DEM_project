cmake_minimum_required(VERSION 3.3)
project(LIGGGHTS_3_2_1p_dev)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(LIGGGHTS_3_2_1p_dev ${SOURCE_FILES})