cmake_minimum_required(VERSION 3.19)
project(milan)

set(CMAKE_CXX_STANDARD 14)

add_executable(milan main.cpp parser.cpp scanner.cpp codegen.cpp)