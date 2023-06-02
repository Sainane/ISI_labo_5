cmake_minimum_required(VERSION 3.25)
project(ISI_labo_5)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-pie -m32")
add_executable(Partie_1
        main.cpp)
