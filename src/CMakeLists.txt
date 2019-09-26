cmake_minimum_required(VERSION 3.10)

add_executable(tracker main.cpp)

target_link_libraries(
        tracker
        ${OpenCV_LIBS}
        )