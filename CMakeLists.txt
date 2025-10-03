cmake_minimum_required(VERSION 3.10)
project(FaceRecognition CXX)

find_package(OpenCV REQUIRED)

add_executable(FaceRecognition main.cpp)
target_link_libraries(FaceRecognition ${OpenCV_LIBS})

