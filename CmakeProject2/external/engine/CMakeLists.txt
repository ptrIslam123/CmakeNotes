cmake_minimum_required(VERSION 3.16)

project(engine)


add_library(engine engine.cpp)

target_link_libraries(engine PUBLIC lib1 lib2)

target_include_directories(engine PUBLIC .)
target_include_directories(engine PUBLIC ../)
