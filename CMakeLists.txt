# Set the minimum required version of CMake
cmake_minimum_required(VERSION 3.10)

# Set the name of the project and its version
project(my_project VERSION 1.0)

# Add an executable target
add_executable(my_app main.cpp)

# Set the C++ standard to C++11
target_compile_features(my_app PUBLIC cxx_std_11)

