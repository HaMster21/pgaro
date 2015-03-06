cmake_minimum_required(VERSION 2.8)

set(CMAKE_DISABLE_SOURCE_CHANGES ON)
set(CMAKE_DISABLE_IN_SOURCE_BUILD ON)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${CMAKE_SOURCE_DIR}/cmake_modules)
set(CMAKE_CXX_FLAGS ${CMAKE_CXX_FLAGS} -std=gnu++11)

#project(P-Garo)

add_subdirectory(src)
add_subdirectory(test)
