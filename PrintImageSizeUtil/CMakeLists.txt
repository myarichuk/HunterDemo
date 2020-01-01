cmake_minimum_required (VERSION 3.8)

find_package(OpenCV REQUIRED)
add_executable (PrintImageSizeUtil "PrintImageSizeUtil.cpp" "PrintImageSizeUtil.h")
target_link_libraries(PrintImageSizeUtil PRIVATE ${OpenCV_LIBS})