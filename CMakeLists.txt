cmake_minimum_required(VERSION 3.16)

project(pre-commit-test VERSION 0.1 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(pre-commit-test
    main.cpp
)
