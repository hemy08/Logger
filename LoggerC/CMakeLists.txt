cmake_minimum_required(VERSION 3.13)
project(LoggerC C)

set(CMAKE_C_STANDARD 99)

add_executable(LoggerC main.c Debug/Debug.c Debug/Debug.h)