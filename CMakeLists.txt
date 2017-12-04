cmake_minimum_required(VERSION 3.9)
project(dynamic)

set(CMAKE_CXX_STANDARD 11)

add_executable(dynamic main.cpp)

target_link_libraries(${PROJECT_NAME}
        opencv_video
        opencv_core
        opencv_highgui
        opencv_imgproc
        m )