cmake_minimum_required(VERSION 3.27)
set(PROJECT_NAME glad)
project(${PROJECT_NAME})

set(CMAKE_CXX_STANDARD 11)

add_library(${PROJECT_NAME} src/glad.c)
target_include_directories(${PROJECT_NAME} PUBLIC include)