cmake_minimum_required(VERSION 3.14)
project("Algorithms")

file(GLOB SOURCES 
    generalstuff/*.c
)

add_executable(Main main.c ${SOURCES})
target_include_directories(Main PUBLIC .)

