# CMake 最低版本号要求
cmake_minimum_required (VERSION 3.12)
#项目信息
project(x265demo)

aux_source_directory(. SRC)
#set(SRC)

add_executable(x265Demo  ${SRC})

include_directories(/usr/local/include)

target_link_libraries(x265Demo x265)
