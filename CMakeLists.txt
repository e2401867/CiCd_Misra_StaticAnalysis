cmake_minimum_required(VERSION 3.10)
project(CiCdMisraStaticAnalysis)

set(CMAKE_CXX_STANDARD 11)

# 指定头文件路径
include_directories(${PROJECT_SOURCE_DIR}/src)

add_executable(calculator src/calculator.cpp tests/test_calculator.cpp)