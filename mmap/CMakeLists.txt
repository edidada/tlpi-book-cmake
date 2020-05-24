#
cmake_minimum_required(VERSION 3.12)
project("mmap")

include_directories(../lib)
link_directories(../lib)
#link_libraries()
add_executable(mmap mmcopy.c ../lib/error_functions.c ../lib/tty_functions.c)