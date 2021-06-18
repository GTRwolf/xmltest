cmake_minimum_required(VERSION 3.17)
project(xmltest)

set(CMAKE_CXX_STANDARD 11)

add_executable(xmltest xmltest.cpp tinyxml2.cpp)