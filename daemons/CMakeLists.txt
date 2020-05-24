cmake_minimum_required(VERSION 3.12)
project("daemons")

include_directories(../lib)
link_directories(../lib)

add_executable(daemons_become_daemon become_daemon.c)
add_executable(daemons_t_syslog t_syslog.c)
add_executable(daemons_test_become_daemon test_become_daemon.c)

