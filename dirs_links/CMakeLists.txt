cmake_minimum_required(VERSION 3.12)
project("dirs_links")

include_directories(../lib)
link_directories(../lib)

add_executable(dirs_links_bad_symlink bad_symlink.c)
add_executable(dirs_links_file_type_stats file_type_stats.c)
add_executable(dirs_links_list_files list_files.c)
add_executable(dirs_links_list_files_readdir_r list_files_readdir_r.c)
add_executable(dirs_links_nftw_dir_tree nftw_dir_tree.c)
add_executable(dirs_links_t_dirbasename t_dirbasename.c)
add_executable(dirs_links_t_unlink t_unlink.c)
add_executable(dirs_links_view_symlink view_symlink.c)
