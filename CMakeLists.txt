cmake_minimum_required(VERSION 3.7.2)

project(hello-cmake)

include_directories(include)

add_executable(hello-cmake src/main.c src/hello.c)

