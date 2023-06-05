cmake_minimum_required(VERSION 3.0.0)
project(freebasic VERSION 0.1.0)

include(CTest)
enable_testing()

add_library(freebasic freebasic.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
