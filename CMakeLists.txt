cmake_policy(SET CMP0048 NEW)

project(e-voting VERSION 1.0)
cmake_minimum_required(VERSION 3.13)

add_subdirectory(core)
add_subdirectory(simulation)
add_subdirectory(did)