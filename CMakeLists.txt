cmake_minimum_required(VERSION 3.24)

project(example CXX)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(example src/main.cpp)
