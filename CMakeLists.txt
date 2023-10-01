cmake_minimum_required(VERSION 3.26)
project(Tic_tac_toe)

set(CMAKE_CXX_STANDARD 20)

add_executable(Tic_tac_toe main.cpp
        Shapes.cpp
        Shapes.h)
