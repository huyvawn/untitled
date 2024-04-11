cmake_minimum_required(VERSION 3.28)
project(untitled C)

set(CMAKE_C_STANDARD 11)

add_executable(untitled main.c
        chap03/calculate_square.cpp
        chap03/calculate_square.h
        chap03/toantu.cpp
        chap03/toantu.h
        chap03/toantu2.cpp
        chap03/toantu2.h
        session5/bai1.cpp
        session5/bai1.h
        session5/bai2.cpp
        session5/bai2.h
)
