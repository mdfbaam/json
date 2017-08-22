cmake_minimum_required(VERSION 3.0)

# define the project
project(nlohmann_json VERSION 2.1.1 LANGUAGES CXX)

# create and configure the library target
add_library(json INTERFACE)
SET(CMAKE_CXX_STANDARD 11)
target_include_directories(json INTERFACE src)
