CMAKE_MINIMUM_REQUIRED(VERSION 3.25 FATAL_ERROR)

PROJECT(glad)

add_library(glad STATIC include/glad/glad.h src/glad.c)
target_include_directories(glad PUBLIC include/)
