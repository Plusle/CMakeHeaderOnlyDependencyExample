cmake_minimum_required(VERSION 3.15.1)
project(
    HeaderOnly
    VERSION 1.0.0
)

add_library(
    HeaderOnly
    INTERFACE
)

target_include_directories(
    HeaderOnly
    INTERFACE
    .
)