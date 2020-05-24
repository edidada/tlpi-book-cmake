#
cmake_minimum_required(VERSION 3.12)
project("acl")

include_directories(../lib)
link_directories(../lib)
add_executable(acl_acl_update acl_update.c ../lib/tty_functions.c)
add_executable(acl_view acl_view.c)