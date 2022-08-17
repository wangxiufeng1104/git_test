cmake_minimum_required(VERSION 3.15)
project(git_test)
aux_source_directory(. DIR_SRCS)

add_executable(${PROJECT_NAME} ${DIR_SRCS})
