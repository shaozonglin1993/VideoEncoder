# CMake 最低版本号要求
cmake_minimum_required (VERSION 3.12)
#项目信息
project(vpxdemo)


set(SRC test.cpp)

add_executable(VPXDemo ${SRC})

include_directories(/usr/local/include)
include_directories(/usr/local/include/vpx)

target_link_libraries(VPXDemo vpx)
