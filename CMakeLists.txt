cmake_minimum_required(VERSION 3.13)
project(zhash-c C)

add_library(zhash-c src/zhash.c)

install(TARGETS zhash-c LIBRARY DESTINATION lib)