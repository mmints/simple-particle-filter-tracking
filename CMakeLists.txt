cmake_minimum_required(VERSION 3.10)
project(simple-particle-filter-tracking)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED TRUE)

find_package(OpenCV REQUIRED)

add_subdirectory(src)