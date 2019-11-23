cmake_minimum_required(VERSION 3.11)
project(nesproc)

set(CMAKE_CXX_STANDARD 17)

add_executable(nesproc
        CPU/Bus.cpp
        CPU/olc6502.cpp
        CPU/Bus.h
        CPU/olc6502.h
        CPU/olcNes_Video1_6502.cpp
        CPU/olcPixelGameEngine.h)
