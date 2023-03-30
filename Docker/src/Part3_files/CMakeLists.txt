cmake_minimum_required(VERSION 3.24)
project(Part3_files C)

set(CMAKE_C_STANDARD 11)

add_executable(Part3_files main.c)
target_link_libraries(Part3_files fcgi)

