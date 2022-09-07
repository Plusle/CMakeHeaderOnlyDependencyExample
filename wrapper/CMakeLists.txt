cmake_minimum_required(VERSION 3.15.1)

project(
    Wrapper
)

add_library(
    Wrapper
    INTERFACE
)

target_include_directories(
    Wrapper
    INTERFACE
    .
)

target_link_libraries(
    Wrapper
    INTERFACE
    HeaderOnly
    lib
)

add_subdirectory(external)