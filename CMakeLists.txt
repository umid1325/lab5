cmake_minimum_required(VERSION 3.29)
project(lab5)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(lab5
    main.cpp
    main.h
        random.cpp)
add_executable(random random.cpp)
