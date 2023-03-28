cmake_minimum_required(VERSION 3.23)
project(tut_01)

set(CMAKE_CXX_STANDARD 14)

add_executable(tut_01 main.cpp)
include_directories(src)
add_subdirectory(src)
target_link_libraries(tut_01 src)