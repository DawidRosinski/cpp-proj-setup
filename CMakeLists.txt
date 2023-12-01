cmake_minimum_required(VERSION 3.25)

project(cpp_proj_setup LANGUAGES CXX)

add_executable(app)

target_sources(app
    PRIVATE
    src/main.cpp
)

set_target_properties(app
    PROPERTIES
    CXX_STANDARD 20
    CXX_STANDART_REQUIRED ON
)