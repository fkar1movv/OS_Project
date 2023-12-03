cmake_minimum_required(VERSION 3.26)
project(C_project)

set(CMAKE_CXX_STANDARD 14)

add_executable(C_project
        tcp_client.c
        tcp_server.c)
