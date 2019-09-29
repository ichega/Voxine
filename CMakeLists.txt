cmake_minimum_required(VERSION 3.15)
project(Voxine)

set(CMAKE_CXX_STANDARD 17)

add_executable(Voxine main.cpp)
target_link_libraries(${PROJECT_NAME} sfml-graphics sfml-window sfml-system)