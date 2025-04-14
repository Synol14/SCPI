cmake_minimum_required(VERSION 3.10)

project(SCPI_lib)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)
set(CMAKE_CXX_EXTENSIONS OFF)
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall -Wextra -pedantic")

add_executable(${PROJECT_NAME} src/main.cpp)

# Add the include directory to the compiler's search path
include_directories(include)