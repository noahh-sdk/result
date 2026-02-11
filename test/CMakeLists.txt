cmake_minimum_required(VERSION 3.21 FATAL_ERROR)

project(NoahhResultTest LANGUAGES CXX)

add_executable(NoahhResultTest
    test.cpp
)

target_link_libraries(NoahhResultTest
    PRIVATE
    NoahhResult
)