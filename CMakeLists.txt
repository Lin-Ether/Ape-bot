cmake_minimum_required (VERSION 3.6)
project(example)

add_executable(Ape-bot source.cpp)

add_subdirectory(deps/sleepy-discord)
target_link_libraries(Ape-bot sleepy-discord)