cmake_minimum_required(VERSION 3.8)
project(HuffmanTree)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp HuffmanTree.cpp HuffmanTree.h)
add_executable(HuffmanTree ${SOURCE_FILES})