cmake_minimum_required(VERSION 3.10)
project(glad)

set(CMAKE_CXX_STANDARD 17)

file(GLOB_RECURSE SRC_FILES src/glad.c)

add_library(glad STATIC ${SRC_FILES})