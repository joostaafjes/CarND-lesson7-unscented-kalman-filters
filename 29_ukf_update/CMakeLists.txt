cmake_minimum_required(VERSION 3.12)
project(29_ukf_update)

set(CMAKE_CXX_STANDARD 14)

add_executable(29_ukf_update main.cpp ukf.cpp ukf.h)