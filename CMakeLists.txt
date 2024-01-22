project(FreeRTOS_Posix_App)
cmake_minimum_required(VERSION 3.15)

# Compile definitions for freertos
add_compile_definitions(projCOVERAGE_TEST=1)

# The output needs to be stored directly in build folder
set (CMAKE_RUNTIME_OUTPUT_DIRECTORY ${CMAKE_BINARY_DIR})
include_directories(include)
add_subdirectory(src)