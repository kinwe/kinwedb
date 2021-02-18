cmake_minimum_required(VERSION 3.17)
project(kinwedb)

set(CMAKE_CXX_STANDARD 20)

add_subdirectory(third_party/libevent)

add_executable(kinwedb main.cpp)