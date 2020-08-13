cmake_minimum_required(VERSION 3.8)


project (Hello)

set(CMAKE_C_STANDARD 99)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_POSITION_INDEPENDENT_CODE ON)

set(SOURCE
    Hello.c
)

add_executable(${PROJECT_NAME} ${SOURCE})
