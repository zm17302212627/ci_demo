cmake_minimum_required(VERSION 3.10)
project(ci_demo LANGUAGES CXX)

enable_testing()


add_executable(ci_demo src/main.cpp)

add_test(NAME base COMMAND ci_demo)
