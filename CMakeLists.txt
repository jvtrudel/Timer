cmake_minimum_required(VERSION 3.5)
project(Timer)

add_library(timer Timer.cpp Timer.h)
target_include_directories(timer PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
