# CMake 最低版本号要求
cmake_minimum_required (VERSION 3.12)
#项目信息
project(x264demo)


set(SRC x264_encoder.c)

add_executable(x264Demo  ${SRC})

include_directories(/usr/local/include)

target_link_libraries(x264Demo x264)
