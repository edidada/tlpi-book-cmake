cmake_minimum_required(VERSION 3.12)
project("threads")

include_directories(../lib)
add_executable(detached_attrib detached_attrib.c ../lib/error_functions.c)
target_link_libraries(detached_attrib pthread)
