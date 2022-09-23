cmake_minimum_required(VERSION 3.22)

project(metal-cpp OBJCXX)

add_library(metal-cpp INTERFACE)
target_include_directories(metal-cpp INTERFACE include)
target_compile_features(metal-cpp INTERFACE cxx_std_17)
