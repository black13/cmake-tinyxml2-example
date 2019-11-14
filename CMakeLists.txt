cmake_minimum_required(VERSION 3.5)

# Set the project name
project (tinyxmlexample)

include_directories(${CMAKE_CURRENT_BINARY_DIR} ${CMAKE_CURRENT_SOURCE_DIR})


add_executable(tinyxmlexample
    main.cpp
    tinyxml2.cpp
    tinyxml2.h
)


