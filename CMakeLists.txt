﻿cmake_minimum_required (VERSION 3.8)

include("cmake/HunterGate.cmake")
HunterGate(
    URL "https://github.com/cpp-pm/hunter/archive/v0.23.240.tar.gz"
    SHA1 "ca19f3769e6c80cfdd19d8b12ba5102c27b074e0"
)

project ("HunterDemo")

hunter_add_package(OpenCV)
add_subdirectory ("PrintImageSizeUtil")