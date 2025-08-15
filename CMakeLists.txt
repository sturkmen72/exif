cmake_minimum_required(VERSION 3.10)

project (test-exif)

file(GLOB test-exif_srcs
    "*.h"
    "*.cpp")

add_executable (test-exif ${test-exif_srcs})
target_link_libraries(test-exif)
