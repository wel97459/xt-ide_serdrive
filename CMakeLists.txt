cmake_minimum_required(VERSION 3.10)

project(serdrive)

include_directories(library)
include_directories(linux)

add_executable(${CMAKE_PROJECT_NAME}
    linux/Linux.cpp
    library/Checksum.cpp
    library/Image.cpp
    library/Process.cpp
    library/Serial.cpp
)