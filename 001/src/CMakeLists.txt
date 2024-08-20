cmake_minimum_required(VERSION 3.5)
project(HelloApp VERSION 1.0.0 DESCRIPTION "HELLOApp for Cmake" LANGUAGES CXX)
# specify the name of the application that we expects from .
add_executable(HelloAppBinary main.cpp)
# the version of c++ 20 or above.
target_compile_features(HelloAppBinary PRIVATE cxx_std_20)