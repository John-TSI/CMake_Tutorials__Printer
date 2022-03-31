cmake_minimum_required(VERSION 3.12)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

project(Printer VERSION 1.0.0)


#add_subdirectory(include)
#add_subdirectory(src)

include_directories(include)

add_executable(${PROJECT_NAME} src/main.cpp src/printer.cpp)


