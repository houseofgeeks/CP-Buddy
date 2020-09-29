cmake_minimum_required(VERSION 3.0.0)
project(CP-Buddy VERSION 0.1.0)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
set(PROJECT_SOURCE_DIR "/src")

include(CTest)
enable_testing()

file(GLOB CPB_SOURCE
    "src/*.hpp"
    "src/*.h"
    "src/*.cpp"
)

add_executable(${PROJECT_NAME} ${CPB_SOURCE})

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
