cmake_minimum_required(VERSION 3.10)
project(SxiviRender)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

include_directories(src)

add_executable(SxiviRender src/main.cpp)