cmake_minimum_required(VERSION 3.16)

project(lib2)

add_library(lib2 lib.cpp)

target_include_directories(lib2 PUBLIC .)
