cmake_minimum_required(VERSION 4.3)

set(CMAKE_C_VERSION 17) 

project(hugox 
    VERSION 1.0.0
    LANGUAGES C)
    

add_executable(hugox src/main.c)

target_include_directories(hugox PRIVATE ${CMAKE_CURRENT_SOURCE_DIR}/include)