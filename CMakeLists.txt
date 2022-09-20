cmake_minimum_required(VERSION 3.4.1 FATAL_ERROR)
project(malloc_count)
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g -W -Wall -ansi -I..")
add_library(malloc_count malloc_count.h malloc_count.c)