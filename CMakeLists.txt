cmake_minimum_required(VERSION 3.4)
project(HeightAdapter)
add_executable(HeightAdapter main.cpp vec3.cpp HgtFilesGrid.cpp)
target_include_directories(HeightAdapter PRIVATE include)
