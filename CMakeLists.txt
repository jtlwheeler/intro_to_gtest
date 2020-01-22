cmake_minimum_required(VERSION 3.16)

project(Tutorial)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_subdirectory(test)

add_executable(main main.c)