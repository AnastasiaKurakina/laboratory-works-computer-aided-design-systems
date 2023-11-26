cmake_minimum_required(VERSION 3.22.1)
project(lr1_1kurs)

#set(CMAKE_AUTOMOC ON)
set(CMAKE_CXX_STANDARD 14)

#set (CXXFLAGS "-Wall -Wextra")
#set (CMAKE_CXX_FLAGS "${CXXFLAGS}")

#set(INCLUDE_DIRS
 #   "."
#)
#include_directories(${INCLUDE_DIRS})

set(SOURCES
   main.cpp

)

add_executable(lr1_1kurs main.cpp)
