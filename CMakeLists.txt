cmake_minimum_required(VERSION 3.25...4.3)

project(jarvis-ai-chat LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

if(MSVC)
    add_compile_options(/utf-8 /W4)
endif()

add_executable(${PROJECT_NAME} main.cpp)
