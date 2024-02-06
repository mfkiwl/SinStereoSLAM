cmake_minimum_required(VERSION 3.21)
project(SinStereoSLAM)

set(CMAKE_CXX_STANDARD 17)

find_package(Eigen3 REQUIRED)
find_package(OpenCV 4 REQUIRED)

#add_subdirectory(Thirdparty/argparse)

add_executable(${PROJECT_NAME}
        src/main.cpp
)