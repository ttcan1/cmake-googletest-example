cmake_minimum_required(VERSION 3.12.0)

set(CMAKE_CXX_STANDARD 11)
project(cmake-googletest-example)

enable_testing() 

add_subdirectory(thirdparty)
add_subdirectory(lib)
add_subdirectory(src)
add_subdirectory(test)

