cmake_minimum_required(VERSION 3.5.1)
project(algo)

enable_language(CXX)
enable_testing()
set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
find_package(Threads REQUIRED)

add_subdirectory(src)
