cmake_minimum_required(VERSION 3.6)
project(TerrainEngine CXX)
include_directories(include)

#set(SOURCE "src/main.cpp")
file(GLOB SOURCE "src/*.cpp")
add_executable(TerrainEngine ${SOURCE})

#install(TARGETS TerrainEngine DESTINATION bin)