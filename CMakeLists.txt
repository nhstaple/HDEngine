cmake_minimum_required(VERSION 3.20)
project(sandbox)

set(CMAKE_CXX_STANDARD 17)
set(SOURCE_FILES main.cpp)

add_executable(sandbox main.cpp hmath/include/hmath.h hmath/lib/Matrix.cpp hmath/lib/Matrix.h)

