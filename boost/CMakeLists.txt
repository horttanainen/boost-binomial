cmake_minimum_required(VERSION 3.7.1)
project(boost)

add_library(
    ${PROJECT_NAME} INTERFACE
    )

set(
    ${PROJECT_NAME}_INCLUDE_DIRS
    ${PROJECT_SOURCE_DIR}/..
    CACHE INTERNAL "${PROJECT_NAME}: Include Directories" FORCE
    )


