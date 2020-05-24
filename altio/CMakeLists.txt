#
cmake_minimum_required(VERSION 3.12)
project("altio")

include_directories(../lib)
link_directories(../lib)
add_executable(altio_demo_sigio demo_sigio.c)
add_executable(altio_epoll_flags_fork epoll_flags_fork.c)
add_executable(altio_epoll_input epoll_input.c)
add_executable(altio_multithread_epoll_wait multithread_epoll_wait.c)