cmake_minimum_required(VERSION 3.13)

# set the project name and version
project(hello LANGUAGES CXX C VERSION 1.0)
set(TARGET_NAME ${CMAKE_PROJECT_NAME})

# specify the C++ standard
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED True)

add_executable(${TARGET_NAME})
target_sources(${TARGET_NAME} PRIVATE main.cpp)