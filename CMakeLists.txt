cmake_minimum_required(VERSION 3.5)
project(gitDemo C)

set(CMAKE_C_STANDARD 11)

include_directories(.)

add_executable(gitDemo
        main.c
        main.h)
