cmake_minimum_required(VERSION 3.5)
project(CMakeTestProject
        VERSION 0.0.1
        DESCRIPTION "CMake testing going on"
        LANGUAGES CXX)
add_executable(Test1 main.cpp)
target_compile_features(Test1 PRIVATE cxx_std_23)