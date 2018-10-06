cmake_minimum_required(VERSION 3.10)
project(cplusplus_zhengli_tsinghua)

set(CMAKE_CXX_STANDARD 11)
include_directories(./)
include_directories(basic)
add_executable(cplusplus_zhengli_tsinghua
        basic/main.cpp
        basic/programming_assginments/programmingAssignment02.h basic/programming_assginments/programmingAssignment03.h)
