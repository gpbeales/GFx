cmake_minimum_required(VERSION 3.25)

project(GFx VERSION 0.1.0 LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

add_executable(GFx src/main.cpp)

if(MSVC)
    target_compile_options(GFx PRIVATE /W4 /permissive-)
else()
    target_compile_options(GFx PRIVATE -Wall -Wextra -Wpedantic)
endif()
