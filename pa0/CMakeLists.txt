cmake_minimum_required (VERSION 3.16)
project (Transformation)

find_package(Eigen3 REQUIRED)
include_directories("/opt/homebrew/Cellar/eigen/3.4.0_1/include")

add_executable (Transformation main.cpp)

# target_link_libraries(${PROJECT_NAME} PRIVATE Eig)