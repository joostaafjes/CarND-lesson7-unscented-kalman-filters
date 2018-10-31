cmake_minimum_required(VERSION 3.12)
project(23_predict_mean_and_covariance)

set(CMAKE_CXX_STANDARD 14)

add_executable(23_predict_mean_and_covariance main.cpp ukf.cpp ukf.h)