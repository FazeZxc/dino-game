cmake_minimum_required(VERSION 3.20)

project(dino)

set(CMAKE_CXX_STANDARD 17)

add_executable(dino src/main.cpp)

target_include_directories(dino PUBLIC include)
