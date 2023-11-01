cmake_minimum_required(VERSION 3.21)

project(HuffmanZipper)

set(CMAKE_CXX_STANDARD 17)

file(GLOB HZITargets *.cpp)

add_subdirectory(buffer)

add_library(HZAllIncludes ${HZITargets})

target_link_libraries(HZAllIncludes HZBufferIncludes)