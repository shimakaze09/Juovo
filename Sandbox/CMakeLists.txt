cmake_minimum_required(VERSION 3.0)
project(Sandbox)
set(SRC_LIST src/Application.cpp)

add_subdirectory(Engine)

add_executable(${PROJECT_NAME} ${SRC_LIST})
target_link_libraries(${PROJECT_NAME} Engine)