cmake_minimum_required(VERSION 3.10)

project(lab1)

set(SOURCES
    main.cpp
    TestClass.cpp
)

set(HEADERS
    TestClass.hpp
)

add_executable(lab1 ${SOURCES} ${HEADERS})
