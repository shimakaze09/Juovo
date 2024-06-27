cmake_minimum_required(VERSION 3.0)
project(Engine)
set(SRC_LIST src/Test.cpp)
add_library(Engine STATIC ${SRC_LIST})