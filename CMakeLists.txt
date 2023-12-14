cmake_minimum_required(VERSION 3.20)

project(glad C)

include_directories(include)

add_library(glad STATIC src/glad.c)
