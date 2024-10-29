cmake_minimum_required(VERSION 3.29)
project(Game_3D)

set(CMAKE_CXX_STANDARD 20)

find_package(OpenGL REQUIRED)

add_executable(Game_3D main.cpp)

target_link_libraries(Game_3D OpenGL::GL)