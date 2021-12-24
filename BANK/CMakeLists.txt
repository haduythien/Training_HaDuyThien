cmake_minimum_required(VERSION 2.8.10)
project(BANK)

include_directories(include)

file(GLOB SOURCES "src/*.cpp")
add_executable(bank ${SOURCES})
