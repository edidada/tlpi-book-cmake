cmake_minimum_required(VERSION 3.12)
project("filelock")

include_directories(../lib)
link_directories(../lib)

add_executable(create_pid_file create_pid_file.c)
