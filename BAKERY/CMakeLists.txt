cmake_minimum_required(VERSION 2.8.10)
project(BAKERY)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")
add_executable(bakery ${SOURCES})
