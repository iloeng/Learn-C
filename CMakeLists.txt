cmake_minimum_required(VERSION 3.15)
project(Learn_C)

set(CMAKE_CXX_STANDARD 14)

add_executable(Learn_C
        helloworld/hello.c helloworld/a.c helloworld/bool.c helloworld/define.c helloworld/auto.c helloworld/minipro/main.c helloworld/minipro/proj.c helloworld/minipro/proj.h helloworld/op.c)
