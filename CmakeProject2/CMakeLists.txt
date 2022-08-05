cmake_minimum_required(VERSION 3.16)

project(main)

add_subdirectory(external/engine)
add_subdirectory(external/lib2)
add_subdirectory(external/lib1)

add_executable(main program/main.cpp)

target_include_directories(main PUBLIC external)

target_link_libraries(main PUBLIC engine)
