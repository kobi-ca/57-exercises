cmake_minimum_required(VERSION 3.19)
project(57_exercises)

set(CMAKE_CXX_STANDARD 20)
enable_testing()
include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)
conan_basic_setup()

add_subdirectory(exercise-1)
