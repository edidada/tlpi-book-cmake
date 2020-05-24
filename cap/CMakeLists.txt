cmake_minimum_required(VERSION 3.12)
project("cap")

include_directories(../lib)
link_directories(../lib)
add_executable(cap_cap_launcher cap_launcher.c)
add_executable(cap_demo_file_caps demo_file_caps.c)