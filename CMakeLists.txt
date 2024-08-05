cmake_minimum_required(VERSION 3.13)

project(DrawCircle)

add_executable(DrawCircle WIN32
    main.cpp
    basewin.h
)

target_compile_definitions(DrawCircle
    PUBLIC
        UNICODE
        _UNICODE
)

target_link_libraries(DrawCircle
    d2d1)
