cmake_minimum_required(VERSION 3.20)
project(maze_gen_algos VERSION 0.0.1)

set(CMAKE_CXX_STANDARD 20)

add_executable(maze_gen_algos main.cpp)

add_subdirectory(Algo)

target_include_directories(maze_gen_algos PUBLIC "${PROJECT_SOURCE_DIR}/Algo/include")