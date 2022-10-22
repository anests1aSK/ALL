cmake_minimum_required(VERSION 3.23)
project(C C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(C
        hackingnet.h
        hacking.h
        webserver.c)
