cmake_minimum_required(VERSION 3.7.1)
project(boost)

file(
    GLOB_RECURSE SOURCE_FILES
    *.hpp
    *.h
    )

add_library(
    ${PROJECT_NAME} INTERFACE
    )
target_include_directories(
    ${PROJECT_NAME} INTERFACE
    ${PROJECT_SOURCE_DIR}/..
)
