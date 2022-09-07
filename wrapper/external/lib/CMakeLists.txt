cmake_minimum_required(VERSION 3.15.1)

project(lib)

add_library(
    lib
    lib.cpp
)

target_include_directories(
    lib
    PUBLIC
    .
)