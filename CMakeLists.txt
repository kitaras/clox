cmake_minimum_required(VERSION 3.19)
project(clox C)

set(CMAKE_C_STANDARD 11)

add_executable(clox main.c chunk.c chunk.h common.h compiler.c compiler.h debug.c debug.h memory.c memory.h object.c object.h scanner.c scanner.h table.c table.h value.c value.h vm.c vm.h)