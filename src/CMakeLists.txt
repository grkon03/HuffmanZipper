cmake_minimum_required(VERSION 3.21)

project(HuffmanZipper)

set(CMAKE_CXX_STANDARD 17)

add_subdirectory(HuffmanZipper)

add_executable(HuffmanZipper main.cpp)

target_link_libraries(HuffmanZipper HZAllIncludes)