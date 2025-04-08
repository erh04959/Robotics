cmake_minimum_required(VERSION 3.10)
project(FeatureTracking)

find_package(OpenCV REQUIRED)
include_directories(${OpenCV_INCLUDE_DIRS})

add_executable(FeatureTracking main.cpp)
target_link_libraries(FeatureTracking ${OpenCV_LIBS})
