cmake_minimum_required(VERSION 3.6)
project(TerrainEngine CXX)

file(GLOB SOURCE "src/*.cpp")

add_executable(TerrainEngine ${SOURCE} include)

target_include_directories(TerrainEngine PRIVATE include)