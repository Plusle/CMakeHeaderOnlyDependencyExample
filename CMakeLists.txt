cmake_minimum_required(VERSION 3.15.1)

project (
    CMakeHeaderOnlyDependencyExample
)

add_subdirectory(wrapper)
add_executable(
    main
    main.cpp
)

target_link_libraries(
    main
    PRIVATE
    Wrapper
)