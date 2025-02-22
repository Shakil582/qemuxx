cmake_minimum_required(VERSION 3.10)

project(qemuxx)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED True)

set (SOURCE_FILES
     src/main.cpp)

add_executable(qemuxx ${SOURCE_FILES})
