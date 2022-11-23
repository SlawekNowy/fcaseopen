cmake_minimum_required(VERSION 3.8)

project(fcaseopen)

set(LIB_SOURCES fcaseopen.c fcaseopen.h)

add_library(fcaseopen STATIC ${LIB_SOURCES})
