cmake_minimum_required(VERSION 3.12)
project("filebuff")

include_directories(../lib)
link_directories(../lib)

add_executable(filebuff_copy copy.c)
add_executable(filebuff_direct_read direct_read.c)
add_executable(filebuff_mix23_linebuff mix23_linebuff.c)
add_executable(filebuff_mix23io mix23io.c)
add_executable(filebuff_write_bytes write_bytes.c)
