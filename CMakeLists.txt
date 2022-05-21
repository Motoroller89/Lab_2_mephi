cmake_minimum_required(VERSION 3.21)
project (lab3_2)

set(CMAKE_CXX_STANDARD 14)

add_executable(lab3_2 main.cpp DynamicArray.h LinkedList.h Tests.cpp Tests.h)
