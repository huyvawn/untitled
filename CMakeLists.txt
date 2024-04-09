cmake_minimum_required(VERSION 3.28)
project(untitled C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled main.c
        chap03/calculate_square.cpp
        chap03/calculate_square.h
)
