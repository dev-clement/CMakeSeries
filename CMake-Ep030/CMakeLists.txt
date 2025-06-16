cmake_minimum_required(VERSION 3.50)

project(HelloApp
        VERSION 0.0.1
        DESCRIPTION "A simple app that uses Conan"
        LANGUAGES CXX)

add_executable(${PROJECT_NAME} src/main.cpp)
target_link_libraries(${PROJECT_NAME} fmt::fmt)
