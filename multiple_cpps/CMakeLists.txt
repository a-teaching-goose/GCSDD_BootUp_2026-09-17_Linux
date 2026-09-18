cmake_minimum_required(VERSION 3.16)

project(multiple_cpps LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(hello main.cpp greeting.cpp)
