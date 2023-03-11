cmake_minimum_required(VERSION 3.24)
project(problem2)

set(CMAKE_CXX_STANDARD 20)

add_executable(problem2 main.cpp RingBuffer.cpp RingBuffer.hpp CustomExceptions.hpp)
