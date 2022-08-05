cmake_minimum_required(VERSION 3.16)

project(lib1)

add_library(lib1 lib.cpp)

target_include_directories(lib1 PUBLIC .)
