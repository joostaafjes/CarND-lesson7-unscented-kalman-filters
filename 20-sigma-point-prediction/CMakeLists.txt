cmake_minimum_required(VERSION 3.12)
project(20_sigma_point_prediction)

set(CMAKE_CXX_STANDARD 14)

add_executable(20_sigma_point_prediction main.cpp ukf.cpp ukf.h)