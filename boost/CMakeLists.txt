cmake_minimum_required(VERSION 3.7.1)
project(boost)

file(
    RECURSIVE_GLOB SOURCE_FILES
    *.hpp
    *.h
    )

add_library(
    ${PROJECT_NAME} INTERFACE
    ${SOURCE_FILES}
    )
