cmake_minimum_required(VERSION 3.12)
project(
        HelloApp
        VERSION 0.0.1
        DESCRIPTION "The leading Hello World App2"
        LANGUAGES CXX
)

add_executable(HelloAppBinary src/main.cpp
        src/main.cpp)
target_compile_features(HelloAppBinary PRIVATE cxx_std_20)
