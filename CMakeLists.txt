cmake_minimum_required(VERSION 3.27)
project(KSTCK)

set(CMAKE_CXX_STANDARD 17)

add_executable(KSTCK
        main.cpp
        reader.cpp
        algorithms.cpp        # <--- este tem de estar aqui

)