cmake_minimum_required(VERSION 3.20)
project(ChatValidation)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_OSX_ARCHITECTURES arm64)

add_executable(ChatValidation
    src/main.cpp
    src/validators/message_validator.cpp
)

target_include_directories(ChatValidation PRIVATE src)
