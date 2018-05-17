cmake_minimum_required(VERSION 3.10)
project(untitled4)

set(CMAKE_CXX_STANDARD 11)

add_executable(untitled4 server.c)
find_package(Threads REQUIRED)
target_link_libraries(untitled4 Threads::Threads)