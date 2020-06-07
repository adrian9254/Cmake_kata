cmake_minimum_required(VERSION 1.2)

project(cmake_example)

add_executable(cmake_example main.cpp modules/parser.cpp modules/equations.cpp)
