# Project setup
#project(hayai)
cmake_minimum_required(VERSION 2.8)

install(DIRECTORY src DESTINATION include)

# Sub projects
add_subdirectory(src)
add_subdirectory(sample)
