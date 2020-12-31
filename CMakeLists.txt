# CMake 最低版本号要求
cmake_minimum_required (VERSION 3.12)
#项目信息
project(VEncoder)

#添加src子目录
add_subdirectory(vpx)
add_subdirectory(x264)
add_subdirectory(x265)

