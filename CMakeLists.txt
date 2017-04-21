cmake_minimum_required(VERSION 3.7)
project(jetbrains_clion_cpp)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES src/main.cpp)
add_executable(jetbrains_clion_cpp ${SOURCE_FILES})