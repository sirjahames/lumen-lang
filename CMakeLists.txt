cmake_minimum_required(VERSION 3.25)
project(lumen LANGUAGES CXX VERSION 1.0)

# ------------------------

add_executable(lumen-lang "lumen/src/Entrance.cpp")
target_compile_features(lumen-lang PUBLIC cxx_std_17)