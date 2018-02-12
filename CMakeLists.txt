cmake_minimum_required(VERSION 3.0.0)

# define the project
project(nlohmann_json VERSION 3.1.0 LANGUAGES CXX)



# create and configure the library target
add_library(json INTERFACE)
SET(CMAKE_CXX_STANDARD 11)
target_include_directories(json INTERFACE single_include/nlohmann)
