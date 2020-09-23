cmake_minimum_required(VERSION 3.17)
project(RedBelt_final)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17 -pthread")

add_executable(RedBelt_final main.cpp test_runner.h profile.h
        parse.h parse.cpp
        iterator_range.h
        search_server.h search_server.cpp)