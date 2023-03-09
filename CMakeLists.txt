cmake_minimum_required(VERSION 3.0)
project(Linmath)

add_library(linmath linmath.h linmath_test.c)
target_include_directories(linmath PUBLIC include/)

