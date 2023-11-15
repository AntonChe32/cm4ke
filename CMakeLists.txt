cmake_minimum_required(VERSION 3.22)
project(
    first_step
    VERSION 0.0.0
    DESCRIPTION "first step CMAKE"
    LANGUAGES CXX
    
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_BUILD_TYPE Debug)

add_executable(first_step)

set(sources 
    main.cpp
)

target_sources(first_step PRIVATE ${sources})
