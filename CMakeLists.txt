cmake_minimum_required(VERSION 2.8)

project(2DDVM++)

set(CMAKE_SOURCE_DIR ${PROJECT_SOURCE_DIR}/src)
set(CMAKE_BINARY_DIR ${PROJECT_SOURCE_DIR})
set(CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR}/bin)

set(DOC_DIR ${PROJECT_SOURCE_DIR}/doc)

add_subdirectory(${CMAKE_SOURCE_DIR})
add_subdirectory(${PROJECT_SOURCE_DIR}/doc)
