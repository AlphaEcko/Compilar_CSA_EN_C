cmake_minimum_required(VERSION 3.5)
project(Compilar_CSA_en_C__)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)
add_executable(Compilar_CSA_en_C__ ${SOURCE_FILES})