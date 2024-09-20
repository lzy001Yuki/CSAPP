cmake_minimum_required(VERSION 3.22)
project(CSAPP)

set(CMAKE_CXX_STANDARD 17)

add_executable(CSAPP main.cpp
        dataLab/tests.c
        dataLab/ishow.c
        dataLab/fshow.c
        dataLab/decl.c
        dataLab/btest.h
        dataLab/btest.c
        dataLab/bits.c
dataLab/bits.h)
