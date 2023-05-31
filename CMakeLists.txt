cmake_minimum_required(VERSION 3.22)
project(coroutine)

set(CMAKE_CXX_STANDARD 17)


add_executable(coroutine coroutine.c)
add_executable(main main.c)
target_link_libraries(main coroutine)