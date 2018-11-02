cmake_minimum_required(VERSION 3.12)
project(26_predict_radar_measurement)

set(CMAKE_CXX_STANDARD 14)

add_executable(26_predict_radar_measurement main.cpp ukf.cpp ukf.h)