cmake_minimum_required(VERSION 3.0)
project(sample)
message(${PROJECT_SOURCE_DIR})
aux_source_directory(${PROJECT_SOURCE_DIR}/../ SRCS)
aux_source_directory(${PROJECT_SOURCE_DIR}/../sample SRCS)
add_executable(sample ${SRCS})
set(CMAKE_EXPORT_COMPILE_COMMANDS ON)

