cmake_minimum_required(VERSION 3.2)

project(bin2code)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(${PROJECT_NAME}
    "main.cxx"
)
