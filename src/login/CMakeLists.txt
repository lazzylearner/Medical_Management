cmake_minimum_required(VERSION 3.20.0)
project(login)
add_library(login login_system.cpp)
target_include_directories(login PUBLIC .)
target_include_directories(login PUBLIC ./include)