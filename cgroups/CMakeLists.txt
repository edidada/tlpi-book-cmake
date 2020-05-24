cmake_minimum_required(VERSION 3.12)
project("cgroups")

include_directories(../lib)
link_directories(../lib)

add_executable(cgroups_alloc_mem alloc_mem.c)
add_executable(cgroups_fork_bomb fork_bomb.c)