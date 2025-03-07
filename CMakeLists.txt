cmake_minimum_required(VERSION 3.28)

set(CMAKE_BUILD_TYPE Release)
set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

project(arena-allocator-lib VERSION 1.0.0)

add_library(arenaallocator INTERFACE)

target_include_directories(arenaallocator INTERFACE src)

install(FILES src/arena_allocator.hpp DESTINATION include)
