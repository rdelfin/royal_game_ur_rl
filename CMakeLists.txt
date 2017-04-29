cmake_minimum_required(VERSION 3.6)
project(royal_game_ur_rl)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES main.cpp)

add_executable(ur_rl ${SOURCE_FILES})