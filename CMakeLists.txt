cmake_minimum_required(VERSION 3.27)
project(motif_labs)

set(CMAKE_CXX_STANDARD 20)

add_executable(motif_labs main.cpp)


target_link_libraries(motif_labs PRIVATE Xm Xt)
