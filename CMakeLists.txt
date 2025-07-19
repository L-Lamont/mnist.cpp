cmake_minimum_required(VERSION 4.0)

project(mnist.cpp LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 23)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(mnist.cpp.bin src/main.cpp)
