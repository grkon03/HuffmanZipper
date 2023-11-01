cmake_minimum_required(VERSION 3.21)

project(HuffmanZipper)

set(CMAKE_CXX_STANDARD 17)

file(GLOB HZBufferTargets *.cpp)

add_library(HZBufferIncludes ${HZBufferTargets})